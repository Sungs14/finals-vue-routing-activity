<template>
  <nav class="navbar navbar-expand navbar-dark bg-primary">
    <div class="container">
      <router-link class="nav-link text-white" to="/">Home</router-link>
      <router-link class="nav-link text-white" to="/blog">Blog</router-link>
      <router-link class="nav-link text-white" to="/gallery">Gallery</router-link>
      <router-link class="nav-link text-white" to="/about">About</router-link>
      <router-link class="nav-link text-white" to="/contact">Contact</router-link>
    </div>
  </nav>
  <router-view />
</template>