<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <body class="bg-gray-300">
    <div class="bg-gray-100 grid lg:grid-cols-2 2xl:grid-cols-5">
      <div class="px-8 py-12 max-w-md mx-auto sm:max-w-xl lg:px-12 lg:py-24 lg:max-w-full xl:mr-0 2xl:col-span-2">
        <div class="xl:max-w-xl">
          <img class="w-3/12" src="./assets/image1.jpg"/>
          <h1
            class="mt-6 text-2xl font-bold text-gray-900 sm:mt-8 sm:text-4xl lg:text-3xl xl:text-4xl"
          >
            Muhammad Adam Danish
            <br class="hidden lg:inline" />
          </h1>
          <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">
            Hello, my name is Adam and I'm currently studying in Politeknik Brunei taking Level 5 Diploma in Web Development, this is my portfolio.  
          </p>
          <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">I am interested in web development and would like to learn more about it in the future</p>
          <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">For inquiries, contact me at: 20FTT1452@student.pb.edu.bn</p>
        </div>
      </div>
    </div>
  </body>
</template>
