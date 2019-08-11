<template>
  <div>
    <!-- <a href="/users">Users</a> -->
    <!-- It loaded brand new page  -->
    <!-- router-link uses a tag behind the scenes -->

    <!-- <nuxt-link to="/users">Users with nuxt link</nuxt-link> -->

    <h1>My task from lesson number 14 module:2</h1>
    <nuxt-link to="/products">Go to products page</nuxt-link>

    <div class="next-line">
      <span>Questions to be asked</span>
      <h1>How "nuxt-link" link didn't load the entire page.</h1>
      <h2>How it got pre-rendered.</h2>
    </div>
    <div class="next-line">
      <ul>
        <li>
          <h1>Things i learned</h1>
        </li>
        <li>
          <ul>
            <li>
              <h1 class="folder">Pages folder</h1>
            </li>
            <li>Routing system which nuxt gives out of the box.</li>
            <li>Dynamic routing system</li>
            <li>$route.params.id</li>
            <li>this.$router.push('/url')</li>
            <li>
              Learned special property from pages which is available in users=>_id=>index.vue file
              validate(data){
              console.log(data);
              }
            </li>
            <li>return /^\d+$/.test(data.params.id);</li>
            <li>
              Token for git:
              205839fdc1d7d7a31dea3215b283c67249fb8be7
            </li>
            <li>Learned about nuxt-child for nested content</li>
          </ul>
        </li>
        <li>
          <ul>
            <li>
              <h1 class="folder">Layouts folder</h1>
            </li>
            <li>
              Layouts
              =>Pages
              =>components
            </li>
            <li>Learned new property called layout which is available in users.vue files</li>
            <li>Learned new layout file called ERROR by craeting a file name as error.vue file.</li>
          </ul>
        </li>
        <li>
          <ul>
            <li>
              <h1 class="folder">Component folder</h1>
            </li>
            <li>Module 20 header not found</li>
            <li>Here i learned that we can use re-usable component in Layout folder</li>
          </ul>
        </li>
        <li>
          <ul>
            <li>
              <h1 class="folder">Styling Nuxt app Assets folder</h1>
            </li>
            <li>Learned to put the main.css folder availbale in assets folder to nuxt.config.js file</li>
            <li>First time entered to nuxt.config.js file</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
// import Logo from "~/components/Logo.vue";

export default {
  components: {}
};
</script>

<style>
.folder {
  color: brown;
}
</style>
