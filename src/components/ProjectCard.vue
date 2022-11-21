<template>
  <article
    id="project"
    class="transition cursor-pointer my-6 md:hover:opacity-important md:hover:scale-110"
  >
    <a
      :href="project.link"
      target="_blank"
      class="bg-[#202022] p-8 rounded flex flex-col"
    >
      <span class="text-xs">{{ project.techStack }}</span>
      <span class="text-2xl font-bold tracking-wide">{{ project.name }}</span>
      <span>{{ project.description }}</span>
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
        <span class="-mt-px text-xs font-semibold leading-none tracking-wider"
          ><span class="sr-only mr-1">Year</span> {{ project.year }}</span
        >
      </div>
    </a>
  </article>
</template>
<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  props: {
    project: {
      type: Object,
      required: true,
      default() {
        return {};
      },
    },
  },
  //   setup() {},
});
</script>
