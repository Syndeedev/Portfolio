<template>
  <div class="">
    <div class="max-w-screen-xl m-auto">
      <div class="flex flex-col md:flex-row px-6 md:pr-0 md:pl-10">
        <div
          class="static text-white flex flex-col justify-between w-full md:w-1/2 lg:w-2/5 md:fixed md:h-screen md:max-w-496 py-10 md:py-14 lg:py-24 lg:pl-20"
        >
          <div class="md:max-w-[390px] lg:max-w-[420px] flex flex-col">
            <span class="text-6xl font-bold">Cynthia Ineh</span>
            <span class="text-2xl font-semibold mt-4">Software Engineer</span>
            <span class="mt-8 text-[#949495]"
              >I'm a Frontend Software engineer with 4+ years experience working
              with JS, VueJS, NuxtJs, and Tailwind.
            </span>
            <span class="mt-4 text-[#949495]"
              >I’m self-sufficient, experienced, and most importantly a good
              teammate. I have worked on several solutions across different
              industries giving me the experience to think far and wide.
            </span>
            <a
              href="#resume"
              class="mb-4 w-fit mt-8 text-xs cursor-pointer tracking-widest text-[#949495] flex items-center hover:text-white transition-all ease-in-out duration-500 group"
            >
              <span>01 </span>
              <span
                class="w-8 h-px mx-3 bg-[#949495] group-hover:w-16 group-hover:bg-white transition-all ease-in-out duration-500"
              ></span>
              <span>PROJECTS</span>
            </a>
            <div
              class="my-4 w-fit text-xs cursor-pointer tracking-widest text-[#949495] flex items-center hover:text-white transition-all ease-in-out duration-500 group"
            >
              <span>02 </span>
              <span
                class="w-8 h-px mx-3 bg-[#949495] group-hover:w-16 group-hover:bg-white transition-all ease-in-out duration-500"
              ></span>
              <span>RESUME</span>
            </div>
            <div
              class="my-4 w-fit text-xs cursor-pointer tracking-widest text-[#949495] flex items-center hover:text-white transition-all ease-in-out duration-500 group"
            >
              <span>03 </span>
              <span
                class="w-8 h-px mx-3 bg-[#949495] group-hover:w-16 group-hover:bg-white transition-all ease-in-out duration-500"
              ></span>
              <span>CONTACT</span>
            </div>
          </div>
        </div>
        <div class="w-full md:w-1/2"></div>
        <div
          class="w-full md:w-1/2 py-10 lg:py-20 text-white md:pl-10 md:pr-10"
        >
          <router-view />
          <div class="group">
            <article
              id="project"
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
            <article
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
            <article
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
            <article
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
            <article
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
            <article
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
            <article
              id="resume"
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript - Resume</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>

            <article
              id="contact"
              class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
            >
              <div class="bg-[#202022] p-8 rounded flex flex-col">
                <span>Typescript</span>
                <span class="text-2xl font-bold tracking-wide">Rilicare</span>
                <span>A solution in the health industry.</span>
                <div class="flex items-center mt-4">
                  <div class="w-5 h-5 p-1 mr-1">
                    <svg
                      viewBox="0 0 46.4 46.4"
                      aria-hidden="true"
                      class="w-full h-full -mt-px fill-current"
                    >
                      <path
                        d="M21.6 2c.3-.6.9-1 1.6-1 .7 0 1.3.4 1.6 1l5.8 11.7c.3.5.8.9 1.4 1l12.8 1.9c.7.1 1.2.6 1.4 1.2.2.6 0 1.4-.5 1.8l-9.3 9.1c-.4.4-.6 1-.5 1.6l2.2 12.9c.1.7-.2 1.4-.7 1.8-.6.4-1.3.5-1.9.1L24 39c-.5-.3-1.1-.3-1.7 0l-11.5 6.1c-.6.3-1.3.3-1.9-.1-.6-.4-.8-1.1-.7-1.8l2.2-12.9c.1-.6-.1-1.2-.5-1.6l-9.4-9c-.5-.5-.7-1.2-.5-1.8.2-.6.8-1.1 1.4-1.2l12.9-1.9c.6-.1 1.1-.5 1.4-1L21.6 2z"
                      ></path>
                    </svg>
                  </div>
                  <span
                    class="-mt-px text-xs font-semibold leading-none tracking-wider"
                    ><span class="sr-only mr-1">Year</span> 2022</span
                  >
                </div>
              </div>
            </article>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  //   setup() {},
});
</script>

<style></style>
