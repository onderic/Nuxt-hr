<template>
  <div>
    <AdminNav></AdminNav>
    <div class="hidden lg:block">
      <Aside></Aside>
    </div>
    <div id="main-content" class="h-full  bg-gray-50 relative overflow-y-auto lg:ml-64">
    <main>
    <div class="pt-8 px-4">
     
      <slot />
    </div>
  </main>
  </div>
    
  </div>
</template>
