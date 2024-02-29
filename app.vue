<template>
  <div class="w-full flex flex-wrap bg-gradient-to-b from-sky-50 to-sky-100	content-start skew-b-12">
    <header class="md:w-9/12 w-11/12 flex flex-wrap">
      <nav class="w-full flex flex-row items-center justify-center py-4">
        <div class="w-6/12 flex flex-col items-center justify-start px-4">
          <a href=""><img src="~/assets/images/cube.png" class="h-11" alt="logo"></a>
        </div>
        <ul
          class="md:w-5/12 md:items-end items-start justify-end text-gray-500 flex md:flex-row gap-x-6 text-sm font-medium">
          <li>
            <a class="text-cyan-800" href="#">About</a>
          </li>
          <li>
            <a href="#">Pricing</a>
          </li>
          <li>
            <a href="#">Contact Us</a>
          </li>
          <li>
            <a href="#">Login</a>
          </li>
          <li>
            <button
              class="py-0.5 px-2 outline outline-2 text-violet-400 outline-violet-500 rounded-lg text-xs font-bold">Get
              Started</button>
          </li>
        </ul>
      </nav>
    </header>
    <div class="md:w-10/12 w-11/12 flex md:flex-row flex-col md:p-6 p-2 mt-6 mx-auto">
      <div class="md:w-1/3 text-start w-full p-4 md:mx-auto">
        <span class="py-1 px-3 bg-purple-200 rounded-lg text-xs">
          V3.1 released. <a href="" class="text-purple-800 underline">Learn More</a>
        </span>
        <h1 class="text-4xl font-bold text-indigo-800 mt-2">
          Your data with real time analytics
        </h1>
        <p class="font-normal text-sm mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime, unde
          saepe adipisci cumque modi error cupiditate, nostrum fugit.
        </p>
        <button type="button"
          class="py-1.5 px-4 bg-indigo-700 text-sm text-white font-semibold rounded-full shadow mt-4 mr-4">Start
          trial</button>
        <button type="button"
          class="py-1.5 px-4 bg-white text-sm text-gray-900 font-semibold rounded-full shadow mt-4">Learn More</button>
      </div>
      <div class="md:w-1/5 flex items-start w-full p-4 md:mx-auto">
        <img class="md:-ml-24 h-auto" src="~/assets/images/digital.svg" alt="">
      </div>
    </div>
  </div>
  <div class="w-full flex flex-col py-4 bg-white md:mt-12 mt-4">
    <h4 class="font-medium text-xs px-4 py-1 mx-auto rounded-full text-violet-500 bg-violet-200 mt-6">Why Qubly</h4>
    <div class="md:w-1/4 w-full mt-6 mx-auto text-center">
      <h4 class="font-extrabold text-2xl text-gray-900 mx-auto">
        Get actionable insights from Big Data in 3 steps
      </h4>
      <p class="text-sm font-semibold text-gray-400 mt-3">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Exercitationem ipsa dolor corrupti sapiente, ullam eos
        facilis aperiam veniam? Molestias incidunt dolorem tempora quis iusto veritatis cum voluptatibus quam velit
        libero.
      </p>
    </div>
    <div class="md:w-8/12 w-full flex md:flex-row flex-col mx-auto justify-around md:mt-12 mt-4">
      <div class="md:w-1/4 w-full p-4 flex flex-col">
        <div class="h-10 w-10 bg-green-400 rounded-full flex justify-center items-center p-2">
          <img class="w-6 h-6" src="~/assets/images/ethernet.png" alt="">
        </div>
        <h3 class="font-bold text-base text-gray-800 mt-1">Data in real-time</h3>
        <p class="text-xs text-gray-400 font-medium mt-1">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deleniti ab itaque pariatur saepe blanditiis, beatae
          fugiat maiores exercitationem expedita similique ipsa totam laudantium omnis magni, optio quas explicabo facilis
          quasi.
        </p>
      </div>
      <div class="md:w-1/4 w-full p-4 flex flex-col">
        <div class="h-10 w-10 bg-red-200 rounded-full flex justify-center items-center p-2">
          <img class="w-6 h-6" src="~/assets/images/email.png" alt="">
        </div>
        <h3 class=" font-bold text-base text-gray-800 mt-1">Powerful Algorithm</h3>
        <p class="text-xs text-gray-400 font-medium mt-1">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deleniti ab itaque pariatur saepe blanditiis, beatae
          fugiat maiores exercitationem expedita similique ipsa totam laudantium omnis magni, optio quas explicabo facilis
          quasi.
        </p>
      </div>
      <div class="md:w-1/4 w-full p-4 flex flex-col">
        <div class="h-10 w-10 bg-violet-200 rounded-full flex justify-center items-center p-2">
          <img class="w-6 h-6" src="~/assets/images/chart.png" alt="">
        </div>
        <h3 class=" font-bold text-base text-gray-800 mt-1">Valuable Business Insights</h3>
        <p class="text-xs text-gray-400 font-medium mt-1">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Deleniti ab itaque pariatur saepe blanditiis, beatae
          fugiat maiores exercitationem expedita similique ipsa totam laudantium omnis magni, optio quas explicabo facilis
          quasi.
        </p>
      </div>
    </div>
  </div>
  <div class="md:w-8/12 w-full flex md:flex-row flex-col items-center md:mt-12 mt-4 mx-auto">
    <div class="md:w-1/2 overflow-visible">
      <img class="w-auto md:h-96 w-full" src="~/assets/images/launch.png" alt="">
    </div>
    <div class="md:flex-1 flex flex-col items-start md:px-1 px-4">
      <h4 class="text-xs font-medium text-rose-500 py-1 px-4 bg-rose-100 rounded-full">For Product Teams</h4>
      <h4 class="md:w-48 w-full text-2xl font-bold mt-1">Launch with the best stack</h4>
      <p class="md:w-96 w-full text-xs font-medium text-gray-400 mt-2">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Nihil architecto eligendi amet illum eius sequi?</p>
    </div>
  </div>
  <div class="md:w-8/12 w-full flex md:flex-row flex-col items-center md:mt-12 mt-4 mx-auto">
    <div class="md:w-1/3 flex flex-col items-start md:px-1 px-4">
      <h4 class="text-xs py-1 px-3 rounded-full font-medium text-rose-500 bg-rose-100">For engineering teams</h4>
      <h4 class="w-56 text-lg font-bold">Data-driven pipeline in minutes</h4>
      <p class="text-xs font-medium text-gray-400">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Commodi similique placeat reiciendis iure doloribus,
        nihil ea! Suscipit nam excepturi nulla est nihil aspernatur ipsa,
        odio officiis porro! Magnam, ut repudiandae.
      </p>
    </div>
    <div class="md:flex-1 w-full px-3">
      <img src="~/assets/images/launch.png" alt="">
    </div>
  </div>
</template>
