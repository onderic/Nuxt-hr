<template>
     <!-- navbar -->
     <nav class="bg-white border-b border-gray-200 fixed w-full z-30">
        <div class="px-3 py-3 lg:px-5 lg:pl-3">
          <div class="flex items-center justify-between">
            <div class="flex items-center justify-start">
                <label for="my-drawer" class="drawer-button lg:hidden"><Icon name="fa-bars" color="black" size="16" /></label>
                <div class="drawer lg:hidden ">
                    <input id="my-drawer" type="checkbox" class="drawer-toggle" />
                    <div class="drawer-contentpt-16">
                    </div> 
                    <div class="drawer-side">
                        <label for="my-drawer" class="drawer-overlay"></label>
                        <ul class="menu p-4 w-80 h-full bg-base-200 text-base-content">
                        <!-- Sidebar content here -->
                        <li><a>Sidebar Item 1</a></li>
                        <li><a>Sidebar Item 2</a></li>
                        
                        </ul>
                    </div>
                 </div>
            
              <a href="/" class="text-xl font-bold flex items-center lg:ml-2.5">
                <img src="../public/favicon.ico" class="h-6 mr-2" alt="Windster Logo">
                <span class="self-center whitespace-nowrap">Brand</span>
              </a>
              
              <form action="#" method="GET" class="hidden lg:block lg:pl-32">
              <label for="topbar-search" class="sr-only">Search</label>
              <div class="mt-1 relative lg:w-64">
                <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                    <Icon name="uil:search" color="black" size="16" />
                </div>
                <input type="text" name="email" id="topbar-search" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-cyan-600 focus:border-cyan-600 block w-full pl-10 p-2.5" placeholder="Search">
              </div>
            </form>
            </div>
            <div class="flex items-center">
              <button id="toggleSidebarMobileSearch" type="button" class="lg:hidden text-gray-500 hover:text-gray-900 hover:bg-gray-100 p-2 rounded-lg">
              <span class="sr-only">Search</span>
              <Icon name="uil:search" color="black" />

            </button>
            <div class="hidden lg:flex items-center">
              
              <a href="/" class="hidden sm:inline-flex ml-5 text-white bg-slate-700 hover:bg-slate-800 focus:ring-4 focus:ring-cyan-200 font-medium rounded-lg text-sm px-5 py-2.5 text-center items-center mr-3">
              <i class="fas fa-gem fa-xs -ml-1 mr-2"></i>
              Go To Home
            </a>
            </div>
            </div>
          </div>
        </div>
      </nav>
      
</template>