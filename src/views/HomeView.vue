<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <main>
    <section class="bg-white dark:bg-gray-900">
      <div class="py-4 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-12" mt-0>
        <p
          class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400"
        >
          Hey! I'am a
        </p>
        <h1
          class="mb-4 text-4xl font-extrabold tracking-tight leading-none  md:text-5xl lg:text-6xl"
        >
          data analyst
        </h1>
        <p
          class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400"
        >
          I've fervor for exploring and transforming raw data into actionable and valuable insights. <br>
          I’m open to work with individuals/organizations that want to make effective use of their data using cutting edge technologies.        </p>
        <div
          class="flex justify-center gap-5 mb-8 lg:mb-16 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4"
        >
          <a target="_blank"
            href="mailto: AbdullahAbubakar461@gmail.com"
            class="r inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-black rounded-lg bg-gray-100 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 dark:focus:ring-primary-900"
          >
            

            Contact 
          </a>
          <RouterLink
            to="/project"
            class="r inline-flex gap-2 justify-center items-center py-3 px-5 text-base font-medium text-center text-gray-900 rounded-lg border border-gray-300  focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800"
          >

            Projects</RouterLink
          >
        </div>
        <!-- <div class="px-4 mx-auto text-center md:max-w-screen-md lg:max-w-screen-lg lg:px-36">
          <span class="font-semibold text-gray-400 uppercase">TOOLS</span>
        </div> -->
          
          <div class="grid grid-cols-1 md:grid-cols-3 p-4 gap-8 cvp">
          <div class=" max-w-sm p-6 shadow hover:shadow-xl rounded-lg">
            <img src="../assets/static/datacollection.png" alt="" >
          <div class="text-start">
            <h5 class="mt-6 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Collect</h5>
          
          <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 mt-4">I have data collection and management experience with QuestionPro, Zonka, BeautifulSoup, Commcare and Airtable.</p>
          
          </div>
          
        </div>
        <div class="max-w-sm p-6 shadow hover:shadow-xl rounded-lg">
            <img src="../assets/static/natural-language-processing.png" alt="">
            <div class="text-start">
             <h5 class="mt-6 text-align-start mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Process</h5>
          <p class="mt-4 font-normal text-gray-500 dark:text-gray-400">I can offer support on improving existing workflows and creation of new processes, covering data transformation with SQL and predictive Analysis with Machine learning.</p>
          </div>
        </div>
        <div class="max-w-sm p-6 shadow hover:shadow-xl rounded-lg">
            <img src="../assets/static/statistics.png" alt="">
            <div class="text-start">
              <h5 class="mt-6 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Visualize</h5>
          
          <p class="mt-4 font-normal text-gray-500 dark:text-gray-400"> I have experience creating interactive Dashboards and charts that provide vaulable insights with Power-Bi, Microsoft Excel and Python.</p>
            </div>
        </div>
          
       </div>
        
      </div>
    </section>
  </main>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Kaushan+Script&family=Montserrat&family=Pacifico&display=swap');
/* font-family: 'Dancing Script', cursive;
font-family: 'Kaushan Script', cursive;
font-family: 'Pacifico', cursive; */
main{
font-family: 'Montserrat', sans-serif;

}
main h1{
  font-family: 'Zian', sans-serif;
  color: black;
}
.r:hover{
  color: white;
  background-color: black;
}
img{
  width: 50%;
  height: auto;
}
</style>