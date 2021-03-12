<template>
    <header class="bg-purple-100 shadow-md  z-50 w-full px-5 py-2 flex justify-between items-center  text-gray-600 body-font">
  <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <NuxtLink to="/" class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
      <img src="@/assets/svgs/1.svg" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full"/>
      <span class="ml-3 text-xl">Abdur Rahman Alizada</span>
    </NuxtLink>

    <nav class="md:ml-auto md:mr-auto   ">
     <ul class="flex flex-wrap items-center justify-center text-base">
    <li>
      <NuxtLink to="/" class="text-black mr-5 hover:text-blue-700">Home</NuxtLink>
    </li>
    <li>  
      <NuxtLink to="/projects" class="text-black mr-5 hover:text-blue-700">My Projects</NuxtLink>
    </li>
    <li>
      <NuxtLink to="/Education" class="text-black mr-5 hover:text-blue-700">Education</NuxtLink>

    </li>
     <li>
        <NuxtLink to="/Contact" class="text-black mr-5 hover:text-blue-700" >Contact me</NuxtLink>
     </li>
     </ul>
    </nav>
 <main>
   <Nuxt />
 </main>
  </div>
</header>
</template>

<script>

</script>
