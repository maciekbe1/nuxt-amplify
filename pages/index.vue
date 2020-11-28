<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">nuxt-amplify</h1>
      <div class="links">
        <nuxt-link
          to="/about"
          class="px-3 py-2 rounded-lg text-white bg-gray-800 active:bg-gray-600 hover:bg-white hover:text-black border-2 border-transparent hover:border-gray-800"
        >
          About
        </nuxt-link>
        <br />
        <br />
        <button
          class="px-3 py-2 rounded-lg text-white bg-gray-800 hover:bg-white active:bg-gray-500 hover:text-black border-2 border-transparent hover:border-gray-800 focus:outline-none"
        >
          button
        </button>
        <button
          class="px-3 py-2 rounded-lg text-white bg-green-500 active:bg-green-700 focus:outline-none"
        >
          Click me
        </button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
