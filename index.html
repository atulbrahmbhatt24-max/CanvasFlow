<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WorkConnect | Marketplace Dashboard</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Tailwind Configuration -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        dark: {
                            900: '#0f172a', // Main BG
                            800: '#1e293b', // Sidebar/Cards
                            700: '#334155', // Borders
                        },
                        brand: {
                            500: '#6366f1', // Primary Action
                            600: '#4f46e5', // Hover
                            400: '#818cf8', // Accent
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Custom Scrollbar for Dark Theme */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a; 
        }
        ::-webkit-scrollbar-thumb {
            background: #334155; 
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #475569; 
        }
        
        /* Transitions */
        .fade-in {
            animation: fadeIn 0.3s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="bg-dark-900 text-gray-300 font-sans antialiased h-screen flex overflow-hidden">

    <!-- Sidebar -->
    <aside id="sidebar" class="bg-dark-800 w-64 border-r border-dark-700 flex-shrink-0 hidden md:flex flex-col transition-all duration-300 z-20">
        <!-- Logo -->
        <div class="h-16 flex items-center justify-center border-b border-dark-700">
            <div class="flex items-center gap-2 text-brand-400 font-bold text-xl">
                <i class="fa-solid fa-bolt"></i>
                <span class="text-white">WorkConnect</span>
            </div>
        </div>

        <!-- Navigation -->
        <nav class="flex-1 py-6 space-y-1">
            <button onclick="switchTab('find-jobs')" id="nav-find-jobs" class="nav-btn w-full flex items-center gap-3 px-6 py-3 text-gray-300 hover:bg-dark-700 hover:text-white transition-colors border-r-2 border-transparent">
                <i class="fa-solid fa-briefcase w-5 text-center"></i>
                <span class="font-medium">Find Jobs</span>
            </button>

            <button onclick="switchTab('post-project')" id="nav-post-project" class="nav-btn w-full flex items-center gap-3 px-6 py-3 text-gray-300 hover:bg-dark-700 hover:text-white transition-colors border-r-2 border-transparent">
                <i class="fa-solid fa-pen-to-square w-5 text-center"></i>
                <span class="font-medium">Post a Project</span>
            </button>

            <button onclick="switchTab('freelancers')" id="nav-freelancers" class="nav-btn w-full flex items-center gap-3 px-6 py-3 text-gray-300 hover:bg-dark-700 hover:text-white transition-colors border-r-2 border-transparent">
                <i class="fa-solid fa-users w-5 text-center"></i>
                <span class="font-medium">Freelancers</span>
            </button>

            <button onclick="switchTab('analytics')" id="nav-analytics" class="nav-btn w-full flex items-center gap-3 px-6 py-3 text-gray-300 hover:bg-dark-700 hover:text-white transition-colors border-r-2 border-transparent">
                <i class="fa-solid fa-chart-line w-5 text-center"></i>
                <span class="font-medium">Analytics</span>
            </button>
        </nav>

        <!-- User Profile Mini -->
        <div class="p-4 border-t border-dark-700">
            <div class="flex items-center gap-3">
                <img src="https://i.pravatar.cc/150?img=11" alt="User" class="w-10 h-10 rounded-full border-2 border-brand-500">
                <div>
                    <p class="text-sm text-white font-semibold">Alex Doe</p>
                    <p class="text-xs text-gray-400">Pro Freelancer</p>
                </div>
            </div>
        </div>
    </aside>

    <!-- Main Content Wrapper -->
    <div class="flex-1 flex flex-col h-full w-full relative">
        
        <!-- Mobile Header -->
        <header class="md:hidden h-16 bg-dark-800 border-b border-dark-700 flex items-center justify-between px-4">
            <div class="flex items-center gap-2 text-brand-400 font-bold text-lg">
                <i class="fa-solid fa-bolt"></i>
                <span class="text-white">WorkConnect</span>
            </div>
            <button onclick="toggleSidebar()" class="text-white focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>
        </header>

        <!-- Main Content Area -->
        <main class="flex-1 overflow-y-auto p-4 md:p-8 relative" id="main-content">
            <!-- Dynamic Content loads here -->
            <div id="content-area" class="fade-in min-h-full"></div>

            <!-- Google AdSense Space (Bottom of Dashboard) -->
            <div id="adsense-container" class="mt-12 pt-8 border-t border-dark-700 text-center">
                <!-- Placeholder Box for AdSense -->
                <div class="bg-dark-800 border border-dashed border-gray-600 py-4 px-auto mx-auto rounded-lg text-gray-500 w-full h-[100px] flex flex-col items-center justify-center">
                    <i class="fa-solid fa-ad text-2xl mb-2 text-gray-600"></i>
                    <p class="text-sm font-medium">Google AdSense Banner Slot (728x90)</p>
                    <p class="text-xs text-gray-600 mt-1">Paste your <code>&lt;script&gt;</code> code here inside the container.</p>
                </div>
            </div>
        </main>
    </div>

    <!-- JavaScript Logic -->
    <script>
        // --- Content Data ---
        
        const tabsData = {
            'find-jobs': `
                <h2 class="text-2xl font-bold text-white mb-6">Find Jobs</h2>
                
                <!-- Search Filter -->
                <div class="bg-dark-800 p-4 rounded-lg border border-dark-700 mb-6 flex flex-col md:flex-row gap-4">
                    <div class="flex-1 relative">
                        <i class="fa-solid fa-search absolute left-3 top-3 text-gray-500"></i>
                        <input type="text" placeholder="Search for projects (e.g. React, Python)..." class="w-full bg-dark-900 border border-dark-700 text-gray-300 pl-10 pr-4 py-2 rounded focus:outline-none focus:border-brand-500 transition">
                    </div>
                    <select class="bg-dark-900 border border-dark-700 text-gray-300 px-4 py-2 rounded focus:outline-none focus:border-brand-500">
                        <option>All Categories</option>
                        <option>Web Development</option>
                        <option>Design</option>
                        <option>Writing</option>
                    </select>
                    <button class="bg-brand-600 hover:bg-brand-500 text-white px-6 py-2 rounded font-medium transition">Search</button>
                </div>

                <!-- Job List -->
                <div class="grid gap-4">
                    <!-- Job Card 1 -->
                    <div class="bg-dark-800 p-6 rounded-lg border border-dark-700 hover:border-brand-500 transition group">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="text-lg font-semibold text-white group-hover:text-brand-400">Full Stack E-Commerce Platform</h3>
                                <p class="text-sm text-gray-400 mt-1">Posted 2 hours ago • <span class="text-green-400">Active</span></p>
                            </div>
                            <span class="bg-dark-900 text-brand-400 px-3 py-1 rounded-full text-sm font-bold">$500-$1k</span>
                        </div>
                        <p class="text-gray-400 mt-3 text-sm line-clamp-2">Looking for an experienced developer to build a scalable e-commerce store using MERN stack. Must include payment gateway integration and admin dashboard.</p>
                        <div class="mt-4 flex gap-2">
                            <span class="text-xs bg-dark-700 text-gray-300 px-2 py-1 rounded">React</span>
                            <span class="text-xs bg-dark-700 text-gray-300 px-2 py-1 rounded">Node.js</span>
                            <span class="text-xs bg-dark-700 text-gray-300 px-2 py-1 rounded">MongoDB</span>
                        </div>
                        <div class="mt-4 pt-4 border-t border-dark-700 flex justify-end">
                            <button class="text-white border border-brand-500 hover:bg-brand-500 px-4 py-1.5 rounded text-sm transition">Apply Now</button>
                        </div>
                    </div>

                    <!-- Job Card 2 -->
                    <div class="bg-dark-800 p-6 rounded-lg border border-dark-700 hover:border-brand-500 transition group">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="text-lg font-semibold text-white group-hover:text-brand-400">Mobile App UI/UX Redesign</h3>
                                <p class="text-sm text-gray-400 mt-1">Posted 5 hours ago • <span class="text-green-400">Active</span></p>
                            </div>
                            <span class="bg-dark-900 text-brand-400 px-3 py-1 rounded-full text-sm font-bold">$200-$300</span>
                        </div>
                        <p class="text-gray-400 mt-3 text-sm line-clamp-2">Need a modern, clean UI redesign for our fitness tracking mobile application. Figma files required.</p>
                        <div class="mt-4 flex gap-2">
                            <span class="text-xs bg-dark-700 text-gray-300 px-2 py-1 rounded">Figma</span>
                            <span class="text-xs bg-dark-700 text-gray-300 px-2 py-1 rounded">UI/UX</span>
                        </div>
                        <div class="mt-4 pt-4 border-t border-dark-700 flex justify-end">
                            <button class="text-white border border-brand-500 hover:bg-brand-500 px-4 py-1.5 rounded text-sm transition">Apply Now</button>
                        </div>
                    </div>
                </div>
            `,

            'post-project': `
                <h2 class="text-2xl font-bold text-white mb-6">Post a Project</h2>
                
                <div class="bg-dark-800 p-6 rounded-lg border border-dark-700 max-w-3xl">
                    <form onsubmit="event.prevent
