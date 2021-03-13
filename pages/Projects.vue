<template>
    <div class="h-screen">
        <section class="text-gray-600 body-font mt-5 container">
         <h1 class="font-bold heading text-4xl font-black flex items-center justify-center">Projects I did!</h1>
         <div class="container px-5 mx-auto">
    <div class="flex flex-wrap">
<div class="container flex mx-auto px-4 md:px-12">
<div class="flex">
 <img class="" src="@/assets/svgs/github.svg"/>
  </div> 
   <span class="font-bold mt-10 p-10 self-center">
         <h4 class="font-bold text-xl font-black items-center justify-center self-center">I made some projects. Although I did'nt work on some Great project yet, But I'm looking forward to it.</h4>
 See my 
   <a href="https://github.com/Abdurrahman-Alizada" class="title-font flex items-center sm:text-4xl text-3xl font-medium">
  GitHub
   <svg class="h-10 w-10 animate-ping" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 9l3 3m0 0l-3 3m3-3H8m13 0a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
   </a>
 </span>

</div>

    </div>
  </div>
        </section>
    </div>
</template>

<script>

export default{

  data(){
    return{
      projects : [
        {
        title : 'Lara-Start',
        desc  : 'It is multiuser Blog website built in Vue and laravel',
        link  : 'https://github.com/Abdurrahman-Alizada/lara-start',
        avatar: require('@/assets/svgs/lav.svg')
        },

        {
        title : 'Book Store Management system 2',
        desc  : 'It was my first project which can maintain all necessary actions for a book store. Developed in Laravel and Vue.js.',
        link  : 'https://github.com/Abdurrahman-Alizada/bookStoreManagementSystem',
         avatar: require('@/assets/svgs/lav.svg')
        },

        {
        title : 'React Quiz',
        desc  : 'React MCQs type Quiz website. which is taking data from an API. Built in React',
        link  : 'https://github.com/Abdurrahman-Alizada/react-quiz',
            avatar: require('@/assets/svgs/react.svg')

        },

      ],
    }
  }
}
</script>

<style scoped>
 .heading{
       font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  color: #35495e;
  letter-spacing: 1px;
 }
</style>
