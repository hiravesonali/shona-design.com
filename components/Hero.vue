<template>
  <div class="mt-10 mx-auto max-w-screen-xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 xl:mt-28">
      <div class="text-left">
        <h2
          class="max-w-3xl mx-auto text-3xl tracking-tight leading-10 font-bold text-gray-900 sm:text-4xl sm:leading-none md:text-5xl mb-3"
        >
          Hi, I'm
          <a class="bg-teal-200 hover:bg-teal-300 cursor-pointer">Sonali</a>
        </h2>
        <h3
          class="max-w-3xl mx-auto text-3xl tracking-tight leading-10 text-gray-900 sm:text-4xl sm:leading-none md:text-5xl mt-12"
        >
          I
          <a
            href="https://shona-design.com/designs"
            class="shiny-text bg-green-200 hover:bg-green-300 cursor-pointer"
          >design</a>,
          <a
            href="https://shona-design.com/my-paintings"
            class="shiny-text bg-pink-200 hover:bg-pink-300 cursor-pointer"
          >paint</a>,
          <a
            href="https://shona-design.com/books-i-read"
            class="shiny-text bg-orange-200 hover:bg-orange-300 cursor-pointer"
          >read</a> &amp;
          <a
            href="https://shona-design.com/my-cooking"
            class="shiny-text bg-yellow-200 hover:bg-yellow-300 cursor-pointer"
          >cook</a>.
        </h3>
        <p
          class="mt-3 max-w-md mx-auto text-base text-gray-500 sm:text-lg md:mt-5 md:text-xl md:max-w-3xl"
        >
          I'm a product designer &amp; ProCreator based in Nuremberg, Germany with experience in delivering end-to-end UX/UI design for software products.
          I'm passionate about improving the lives of others through design and I am constantly looking to learn new things everyday.
        </p>
        <div class="mt-5 max-w-md mx-auto sm:flex sm:justify-center md:mt-8">
          <div class="rounded-md shadow">
            <a
              href="mailto:me@shona-design.com"
              class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-500 focus:outline-none focus:shadow-outline-indigo transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10"
            >
              Let's connect
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                viewBox="0 0 24 24"
                class="w-6 h-6 ml-2"
              >
                <path
                  d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
</template>

<style>
.shiny-text {
  display: inline-block;
  border-radius: 0;
  opacity: 1;
  color: #fff;
  text-decoration: none;
  text-shadow: 1px 1px 1px #000, 0 -1px 1px #000, 1px 1px 1px #000,
    -1px 0 0 #000, 1px 1px 0 #000, 1px 0 0 #000, 0 -1px 0 #000;
}
.shiny-text:focus,.shiny-text:hover{
  color:#161e2e;
  text-shadow:none;
}
</style>
