<template>
  <div>
    <div
      class="fixed inset-0 md:hidden bg-blur bg-gray-900 bg-opacity-50 transition-all duration-300 z-20"
      :class="{ 'opacity-0 invisible': !menu, 'opacity-100 visible': menu }"
    ></div>
    <ul
      class="p-8 fixed transform inset-y-0 md:hidden font-sourcecode text-sm right-0 w-56 bg-white dark:bg-gray-900 flex flex-col justify-center transition-all duration-300 z-20 overflow-hidden"
      :class="{
        'translate-x-56 invisible': !menu,
        'translate-x-0 visible shadow-lg': menu
      }"
    >
      <li class="absolute top-4 right-8">
        <menu-toggle />
      </li>
      <li class="mx-auto mb-8">
        <theme-toggle />
      </li>
      <li>
        <nuxt-link
          to="/#about"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >About</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#skills"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >Skills</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#experience"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >Experience</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#education"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >Education</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#projects"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >Projects</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#achievements"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >Achievements</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#testimonials"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
          >Testimonials</nuxt-link
        >
      </li>
      <li>
        <nuxt-link
          to="/#contact"
          class="mb-8 px-4 py-2 text-center block w-full transition hover:text-blue-500 dark:hover:text-cyan-400 focus:text-blue-500 dark:focus:text-cyan-400"
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
  </div>
</template>

<script>
import { mapGetters } from 'vuex';
import MenuToggle from '@/components/Controls/MenuToggle.vue';
import ThemeToggle from '@/components/Controls/ThemeToggle.vue';

export default {
  name: 'MobileNavbar',
  components: { ThemeToggle, MenuToggle },
  computed: mapGetters({
    menu: 'menu'
  })
};
</script>
