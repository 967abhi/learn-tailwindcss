# learn-tailwindcss
<main class="p-5">
  <h1 class="text-center text-lg text-green-400">Hello World</h1>
  <div class="my-4 h-10 w-full rounded-md border-2 border-violet-600 bg-violet-200 p-2">
    <p class="text-center font-mono text-lg font-extrabold">A div</p>
  </div>
  <!-- <--layout--->
  <div class="fixed top-0 h-10 w-10 bg-red-500"></div>
  <div class="flex justify-between">
    <div class="h-16 w-16 rounded-full bg-blue-500"></div>
    <div class="h-16 w-16 rounded-full bg-blue-500"></div>
    <div class="h-16 w-16 rounded-full bg-blue-500"></div>
    <div class="h-16 w-16 rounded-full bg-blue-500"></div>
  </div>
  <div class="grid grid-cols-5 gap-2">
    <div class="h-12 bg-violet-500"></div>
    <div class="h-12 bg-violet-500"></div>
    <div class="h-12 bg-violet-500"></div>
    <div class="h-12 bg-violet-500"></div>
    <div class="h-12 bg-violet-500"></div>
  </div>
  <div class="hidden md:block">
    <p>I will appear for the device resolution greater the 768px</p>
  </div>
  <div class="hidden max-md:block">
    <p>I will appear for the device resolution which is less than screen size of 768 px</p>
  </div>
  <button class="my-2 rounded-lg bg-blue-500 px-4 py-2 text-white hover:bg-blue-700 focus:outline-none focus:ring-blue-300 active:bg-blue-800">Click me</button>

  <ul class="my-2 space-y-2 ">
    <li class="bg-white p-2 first:bg-yellow-100">Item1</li>
    <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-300 even:bg-green-300">Item1</li>
     <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-300 even:bg-green-300">Item1</li> <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-300 even:bg-green-300">Item1</li> <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-300 even:bg-green-300">Item1</li> <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-300 even:bg-green-300">Item1</li> <li class="bg-white p-2 first:bg-yellow-100 odd:bg-blue-300 even:bg-green-300">Item1</li>
  </ul>
  <!-- theme dark :"" -->
  <div class="m-10 rounded-lg bg-white px-6 py-8 shadow-xl ring-slate- 900/5 ">
    <h3 class="text-base font-medium tracking-tight text-slate-900"> This is text -element </h3>
    <p class="mt-2 text-sm text-slate-500 "> This is an even longer p tag element </p>

    <button id="toggledark " class="text-blue-900 px-4 py-2 text-sm font-medium mt-8 bg-blue-100 rounded-md " onclick="document.body.classList.toggle('dark mode')"> Toggle dark mode </button>
  </div>
</main>
