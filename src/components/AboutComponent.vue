<script setup lang="ts"></script>
<template>
  <div class="flex flex-col py-28 justify-center flex-wrap items-center">
    <h1 class="font-black text-5xl text-center text-white">My Bio</h1>

    <div class="flex flex-row gap-12 py-28 justify-center flex-wrap items-center">
      <div class="border-[#8381B0] border-5 rounded-2xl p-10 h-[35rem] w-[25rem] flex justify-center
      items-center">
        <h1 class="text-[1.5rem] font-light text-white">
          I’m a web developer and software engineer specializing in Javascript, Html, Css, Vue.js and Python. I build
          dynamic, responsive web applications with a focus on quality and scalability. Always eager to learn, I’m
          constantly enhancing my skills to deliver effective, modern solutions.</h1>
      </div>
      <div class="grid grid-rows-2 gap-10">
        <div class="border-[#6EDE70] border-5 w-[25rem] p-10 rounded-2xl h-[15rem]">
          <hi class="text-white text-3xl w-[3rem] font-bold">Known Langueges</hi>
          <div class="flex flex-row gap-5 mt-5 ">
            <img src="../assets/icons8-python-50.png" alt="" class="w-[3rem] mt-4  h-[3rem] ">
            <img src="../assets/icons8-rust-96.png" alt="" class="w-[3rem] mt-4  h-[3rem] ">
            <img src="../assets/icons8-vue.js-96.png" alt="" class="w-[3rem] mt-4  h-[3rem] ">
          </div>
        </div>
        <div class="border-[#6EDE70] border-5 w-[25rem] p-10 rounded-2xl ">
          <h1 class="text-white text-3xl w-[3rem] font-bold">Experience</h1>
          <div class="progress mt-10">
            <div class="w-78 h-7 border-[#6EDE70] border-2 mb-2  rounded-2xl">
              <div class="h-6 w-30  bg-[#6EDE70] rounded-2xl"></div>v
            </div>
            <div class="textDiv text-white">
              <span class="float-left font-light text-sm"> 1 year</span>
              <span class="float-right font-light text-sm">More than 4 years</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <svg width="489" height="100" class="mt-30" viewBox="0 0 489 418" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path fill-rule="evenodd" clip-rule="evenodd"
        d="M318.462 313.25C312.309 313.25 294.657 325.187 279.231 339.775L251.187 366.3L239.803 358.227C233.542 353.79 224.812 344.401 220.412 337.371L212.398 324.587L230.149 335.208C239.909 341.046 250.561 345.828 253.825 345.828C257.081 345.828 259.75 273.993 259.75 186.195C259.75 84.115 256.997 26.5625 252.125 26.5625C247.267 26.5625 244.5 79.8277 244.5 173.333V320.098L222.006 310.162C209.63 304.695 190.759 300.219 180.068 300.219C169.37 300.219 160.625 302.434 160.625 305.151C160.625 307.862 181.128 328.783 206.192 351.64L251.759 393.197L288.16 358.807C308.184 339.892 325.706 321.903 327.101 318.834C328.504 315.765 324.615 313.25 318.462 313.25Z"
        fill="#8381B0" />
    </svg>

  </div>
</template>
