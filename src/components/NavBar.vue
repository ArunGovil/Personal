<script setup lang="ts">
import { isDark } from "~/logics";
</script>

<template>
  <header class="header z-40">
    <router-link
      class="w-10 h-10 absolute lg:fixed m-6 select-none outline-none"
      to="/"
      focusable="false"
    >
      <feather-activity />
    </router-link>
    <nav class="nav">
      <div class="spacer" />
      <div class="right">
        <a href="https://rb.gy/duljna" title="Resume" target="_blank">
          <span class="lt-md:hidden">Resume</span>
          <div i-ri-file-text-line md:hidden />
        </a>
        <router-link to="/posts" title="Blog">
          <span class="lt-md:hidden">Blog</span>
          <div i-ri-cast-line md:hidden />
        </router-link>
        <router-link to="/projects" title="Projects">
          <span class="lt-md:hidden">Projects</span>
          <div i-ri-lightbulb-line class="md:hidden" />
        </router-link>
        <a
          href="https://twitter.com/be_like_arun"
          target="_blank"
          title="Twitter"
          class="lt-md:hidden"
        >
          <feather-twitter />
        </a>
        <a
          href="https://github.com/ArunGovil"
          target="_blank"
          title="GitHub"
          class="lt-md:hidden"
        >
          <div i-uil-github-alt />
        </a>
        <toggle-theme />
      </div>
    </nav>
  </header>
</template>

<style scoped>
.header h1 {
  margin-bottom: 0;
}

.logo {
  position: absolute;
  top: 1.5rem;
  left: 1.5rem;
}

.nav {
  padding: 2rem;
  width: 100%;
  display: grid;
  grid-template-columns: auto max-content;
  box-sizing: border-box;
}

.nav > * {
  margin: auto;
}

.nav img {
  margin-bottom: 0;
}

.nav a {
  cursor: pointer;
  text-decoration: none;
  color: inherit;
  transition: opacity 0.2s ease;
  opacity: 0.6;
  outline: none;
}

.nav a:hover {
  opacity: 1;
  text-decoration-color: inherit;
}

.nav .right {
  display: grid;
  grid-gap: 1.2rem;
  grid-auto-flow: column;
}

.nav .right > * {
  margin: auto;
}
</style>
