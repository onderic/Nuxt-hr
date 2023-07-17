<template>
    
      <div class="flex overflow-hidden bg-white pt-16">
        
     <aside
        class="fixed z-20 h-full top-0 left-0 pt-16 flex lg:flex flex-shrink-0 flex-col w-64 transition-width duration-500"
        
        >
      <div class="relative flex-1 flex flex-col min-h-0 border-r border-gray-200 bg-white pt-0">
        <div class="flex-1 flex flex-col pt-5 pb-4 overflow-y-auto">
          <div class="flex-1 px-3 bg-white divide-y space-y-1">
            <ul class="space-y-2 pb-2">
          <li>
            <form action="#" method="GET" class="lg:hidden">
              <label for="mobile-search" class="sr-only">Search</label>
              <div class="relative">
                <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                  <i class="fas fa-search text-gray-500"></i>
                </div>
                <input type="text" name="email" id="mobile-search" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-cyan-600 focus:ring-cyan-600 block w-full pl-10 p-2.5" placeholder="Search">
              </div>
            </form>
          </li>
          <li>
      
          <a href="#" class="text-base text-gray-900 font-normal rounded-lg flex items-center p-2 hover:bg-gray-100 group" :class="{ 'bg-gray-200': $route.name === 'dashboard' }">
            <i class="fas fa-tachometer-alt w-6 h-6 text-gray-500 group-hover:text-gray-900 transition duration-75"></i>
            <span class="ml-3">Dashboard</span>
          </a>
       
          </li>
          <li>
            <a href="#" target="_blank" class="text-base text-gray-900 font-normal rounded-lg hover:bg-gray-100 flex items-center p-2 group">
              <i class="fas fa-columns w-6 h-6 text-gray-500 flex-shrink-0 group-hover:text-gray-900 transition duration-75"></i>
              <span class="ml-3 flex-1 whitespace-nowrap">Kanban</span>
              <span class="bg-gray-200 text-gray-800 ml-3 text-sm font-medium inline-flex items-center justify-center px-2 rounded-full">Pro</span>
            </a>
          </li>
          <li>
         
              <a href="#" target="_blank" class="text-base text-gray-900 font-normal rounded-lg hover:bg-gray-100 flex items-center p-2 group" :class="{ 'bg-gray-200': $route.name === 'account' }">
                <i class="fas fa-inbox w-6 h-6 text-gray-500 flex-shrink-0 group-hover:text-gray-900 transition duration-75"></i>
                <span class="ml-3 flex-1 whitespace-nowrap">Settings</span>
                <span class="bg-gray-200 text-gray-800 ml-3 text-sm font-medium inline-flex items-center justify-center px-2 rounded-full">Pro</span>
              </a>
          
          </li>
          <li>
            
              <a href="#" class="text-base text-gray-900 font-normal rounded-lg hover:bg-gray-100 flex items-center p-2 group" :class="{ 'bg-gray-200': $route.name === 'users' }">
                <i class="fas fa-users w-6 h-6 text-gray-500 flex-shrink-0 group-hover:text-gray-900 transition duration-75"></i>
                <span class="ml-3 flex-1 whitespace-nowrap">Users</span>
              </a>
          
          </li>
          <li>
           
            <a href="#" class="text-base text-gray-900 font-normal rounded-lg hover:bg-gray-100 flex items-center p-2 group" :class="{ 'bg-gray-200': $route.name === 'products' }">
              <i class="fas fa-shopping-cart w-6 h-6 text-gray-500 flex-shrink-0 group-hover:text-gray-900 transition duration-75"></i>
              <span class="ml-3 flex-1 whitespace-nowrap">Products</span>
            </a>
         
          </li>
          <li>
        
              <a href="#" class="text-base text-gray-900 font-normal rounded-lg hover:bg-gray-100 flex items-center p-2 group" :class="{ 'bg-gray-200': $route.name === 'logout' }">
                <i class="fas fa-sign-in-alt w-6 h-6 text-gray-500 flex-shrink-0 group-hover:text-gray-900 transition duration-75"></i>
                <span class="ml-3 flex-1 whitespace-nowrap">Sign In</span>
              </a>
           
          </li>
          <li>
          
              <a href="#" class="text-base text-gray-900 font-normal rounded-lg hover:bg-gray-100 flex items-center p-2 group" :class="{ 'bg-gray-200': $route.name === 'signup' }">
                <i class="fas fa-user-plus w-6 h-6 text-gray-500 flex-shrink-0 group-hover:text-gray-900 transition duration-75"></i>
                <span class="ml-3 flex-1 whitespace-nowrap">Sign Up</span>
              </a>
         
          </li>

        </ul>
          </div>
        </div>
      </div>
    </aside>
    
</div>
</template>