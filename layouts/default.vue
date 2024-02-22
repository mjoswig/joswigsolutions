<template>
  <div class="flex items-center justify-center p-4 lg:p-12 w-full" style="background-color: #f8f8f8;">
    <div class="wrapper flex flex-col w-full">
      <header class="flex flex-col items-center justify-center mb-5 xl:mb-10">
        <nuxt-link to="/">
          <img class="h-24 w-auto" src="@/assets/images/joswigsolutions-logo.png" />
        </nuxt-link>
      </header>
      <main class="mb-8 xl:mb-12">
        <Nuxt />
      </main>
      <footer class="flex flex-col justify-center space-y-2 md:text-center text-sm">
        <div class="flex flex-col-reverse sm:flex-row sm:items-center  md:justify-center sm:space-x-4">
          <span class="text-gray-500">© Joswig Solutions</span>
          <div class="flex space-x-4 mb-1 sm:mb-0">
            <nuxt-link to="/legal">Legal Information</nuxt-link>
            <nuxt-link to="/privacy">Privacy Policy</nuxt-link>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout'
}
</script>


<style lang="postcss">
html {
  font-family: "Open Sans", "Helvetica Neue", Helvetica, arial;
  font-size: 18px;
  line-height: 1.5;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  color: #2d3748;
}

*,
*::before,
*::after {
  -webkit-tap-highlight-color: transparent;
  box-sizing: border-box;
  margin: 0;
}

h1 {
  @apply text-4xl font-bold;
}

h2 {
  @apply text-3xl font-bold;
}

h3 {
  @apply text-2xl font-bold;
}

h4 {
  @apply text-xl font-bold;
}

.wrapper {
  max-width: 1000px;
}

a {
  @apply font-bold text-gray-500;
  /*color: #daba6b;*/
}

a:hover {
  @apply underline text-gray-600;
  /*color: #cfa53b;*/
}

mark {
  background-position: 0 calc(100% - .1rem);
  background-size: 1.25rem 1.25rem;
  background-image: linear-gradient(transparent 50%,rgba(226,201,138,.5) 0);
  background-repeat: repeat-x;
  background-color: transparent;
  color: inherit;
}

@media (max-width: 1280px) {
  h1 {
    @apply text-2xl;
  }

  h2 {
    @apply text-xl;
  }

  h3 {
    @apply text-lg;
  }

  h4 {
    @apply text-base;
  }
}
</style>