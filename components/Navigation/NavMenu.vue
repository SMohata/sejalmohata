<template>
  <ul
    class="hidden static font-sourcecode text-sm md:flex justify-start items-center"
  >
    <li>
      <nuxt-link
        to="/#about"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >About</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#skills"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Skills</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#experience"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Experience</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#education"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Education</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#projects"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Projects</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#achievements"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Achievements</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#testimonials"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Testimonials</nuxt-link
      >
    </li>
    <li>
      <nuxt-link
        to="/#contact"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
        >Contact</nuxt-link
      >
    </li>
    <li>
      <a
        href="https://drive.google.com/file/d/1EEF1wEzLhmY8oYGv5_v-1VWNr13_r7Rp/view?usp=sharing"
        target="_blank"
        rel="noreferrer"
        class="px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
      >
        Resume
      </a>
    </li>
  </ul>
</template>

<script>
export default {
  name: 'NavMenu'
};
</script>
