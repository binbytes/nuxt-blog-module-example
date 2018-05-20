<template>
  <section class="home-container">
    <div>
      <h2 class="home-slogan">
        Welcome.
      </h2>
      <div class="home-links">
        <nuxt-link
          to="/blog"
          class="button--green">Blogs</nuxt-link>

        <nuxt-link
          to="/blog/collections/nuxtjs"
          class="button--green">Blogs By Cateogry/Collection</nuxt-link>

        <nuxt-link
          to="/blog/tags/laravel"
          class="button--green">Blogs By Tag</nuxt-link>
      </div>
    </div>
  </section>
</template>

<style>
.home-container {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.home-slogan {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.home-links {
  padding-top: 15px;
}
</style>