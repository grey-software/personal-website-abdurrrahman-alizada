<template>
  <div class="">

   <Hero />
    

  </div>
</template>

<script>
import Hero from '@/pages/Hero'
import Navbar from '@/pages/Navbar'
export default {
  components : {
    Navbar,
    Hero,
  }
}
</script>

<style>
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
