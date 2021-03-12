<template>
    <div class="h-screen">
        <section class="text-gray-600 body-font mt-5 container">
         <h1 class="font-bold heading text-4xl font-black flex items-center justify-center">Projects I did!</h1>
         <div class="container px-5 mx-auto">
    <div class="flex flex-wrap">
<div class="container mx-auto px-4 md:px-12">
    <div class="flex flex-wrap -mx-1 lg:-mx-4">

        <!-- Column -->
        <div  v-for="project in projects" :key='title' class="my-1 flex px-1 w-full md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3 min-h-full">

            <!-- Article -->
            <article class="overflow-hidden rounded-lg shadow-2xl">
                    <img alt="Placeholder" class="block h-auto w-full" :src='project.avatar'>
                <header class="items-center justify-between leading-tight p-2 md:p-4">
                    <h1 class="text-xl">
                      {{project.title}}
                    </h1>
                  <p class="p-2">{{project.desc}}</p>
                </header>

                <footer class="flex items-center justify-between leading-none p-2 md:p-4">
                <div class="p-2 w-full">
                <a :href='project.link' class="flex m-auto text-white bg-gray-700 border-0 py-2 px-20 focus:outline-none hover:bg-gray-900 rounded text-lg">See on GitHub</a>
              </div>
                </footer>

            </article>
            <!-- END Article -->

        </div>
        <!-- END Column -->
     
     


    </div>
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