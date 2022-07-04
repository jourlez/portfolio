<template>
  <article
    class="hidden text-gray-500 dark:text-gray-400 lg:block fixed left-8 bottom-0 z-10"
  >
    <ul class="p-4">
      <li>
        <a
          href="https://github.com/jourlez"
          target="_blank"
          rel="noreferrer"
          class="mb-2 h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1 focus:outline-none"
        >
          <git-hub class="h-2/3 w-2/3" />
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/jourlez"
          target="_blank"
          rel="noreferrer"
          class="mb-2 h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1 focus:outline-none"
        >
          <twitter class="h-2/3 w-2/3" />
        </a>
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/jourlez/"
          target="_blank"
          rel="noreferrer"
          class="mb-2 h-8 w-8 grid place-items-center hover:text-blue-500 focus:text-blue-500 dark:hover:text-cyan-400 dark:focus:text-cyan-400 rounded-full transform transition duration-300 hover:-translate-y-1 focus:-translate-y-1 focus:outline-none"
        >
          <linked-in class="h-2/3 w-2/3" />
        </a>
      </li>
    </ul>
    <div class="mx-auto h-24 w-px bg-gray-400 dark:bg-gray-500"></div>
  </article>
</template>

<script>
import GitHub from '../Icons/GitHub.vue';
import LinkedIn from '../Icons/LinkedIn.vue';
import Twitter from '../Icons/Twitter.vue';

export default {
  name: 'SocialHandles',
  components: { GitHub, Twitter, LinkedIn }
};
</script>
