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
          <div class="group">
            <div v-for="(project, index) in projects" :key="index">
              <project-card :project="project" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";
import ProjectCard from "./ProjectCard.vue";
import Project from "@/Project";
export default defineComponent({
  components: { ProjectCard },
  setup() {
    const projects = ref<Project[]>([
      {
        name: "Kneenk",
        description:
          "Design and fund-raise with custom merch designs in few clicks",
        year: "2022",
        techStack: "VueJS",
        link: "https://kneenk-superhero.herokuapp.com/",
      },
      {
        name: "Rilicare",
        description: "A website to help patients access healthcare online",
        year: "2022",
        techStack: "VueJS",
        link: "https://rilicare.netlify.app/",
      },
      {
        name: "TRN",
        description: "A consulting firm for organizations.",
        year: "2022",
        techStack: "VueJS",
        link: "https://www.trn.com.ng/",
      },
      {
        name: "ZURI",
        description:
          "A Law firm website to help you take care of all legal problems",
        year: "2021",
        techStack: "VueJS",
        link: "https://zuri-zuri.netlify.app/",
      },
      {
        name: "ENUM",
        description:
          "A platform housing curate courses on various skills and recruitment opportunities for corporate organizations, content providers, and individuals in all fields.",
        year: "2021",
        techStack: "VueJS",
        link: "https://enum.africa/",
      },
    ]);
    return {
      projects,
    };
  },
});
</script>

<style></style>
