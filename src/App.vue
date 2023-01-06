<template>
  <div class="container mx-auto">
    <header class="shadow-lg">
      <ul class="p-12 py-6">
        <li class="space-x-4">
          <!--ROUTER LINKS-->
          <RouterLink to="/" class="hover:text-red-500 transition duration-300"> Home </RouterLink>
          <RouterLink to="/about" class="hover:text-red-500 transition duration-300"> About </RouterLink>
        </li>
      </ul>
    </header>
    <!--ROUTER VIEW-->
    <RouterView></RouterView>
  </div>
</template>