<template>
  <div class="flex flex-col">
    <div class="md:text-center mb-6 xl:mb-8">
      <h1 class="text-2xl xl:text-3xl mb-2">About Joswig Solutions</h1>
      <p class="text-lg xl:text-xl">We are a web development company with a focus on web solutions and client services.</p>
    </div>
    <div class="mb-8 xl:mb-10">
      <h2 class="text-xl xl:text-2xl mb-1">Solutions</h2>
      <p class="text-base xl:text-lg mb-4">We operate a portfolio of indie projects and micro-startups.</p>
      <div class="grid grid-cols gap-4">
        <Card
          title="Wishlist Page"
          description="A privacy-first gifting platform for content creators, where fans can fund your next wishes or adopt your monthly bills."
          icon="solutions/wishlistpage.png"
          url="https://wishlistpage.com/"
        />
        <Card
          title="smsbrew"
          description="A simple text messaging software for businesses to send notifications, alerts, reminders, and confirmations via SMS."
          icon="solutions/smsbrew.png"
          url="https://smsbrew.com/"
        />
        <Card
          title="Handelszeiten.com"
          description="A German website that lists the trading hours of stock exchanges worldwide."
          icon="solutions/handelszeiten.png"
          url="https://handelszeiten.com/"
        />
      </div>
    </div>
    <div class="mb-8 xl:mb-10">
      <h2 class="text-xl xl:text-2xl mb-1">Services</h2>
      <p class="text-base xl:text-lg mb-4">Would you like to hire us for a web project? Here is what we can do for you:</p>
      <div class="grid grid-cols gap-4">
        <Card
          title="Digital Product Design"
          description="Together with our clients, we challenge traditional business models and bring new ones to profitable fruition."
          icon="services/digital-product-design.svg"
        />
        <Card
          title="Website Development"
          description="With a fresh website relaunch, we accompany our clients in establishing a lasting presence as a digital brand."
          icon="services/website-development.svg"
        />
        <Card
          title="Software Development"
          description="We develop business applications tailored individually to reflect and resolve the needs of our clients."
          icon="services/software-development.svg"
        />
        <Card
          title="Hosting & Maintenance"
          description="We take care of your project and guarantee a high level of availability, performance, flexibility, and scalability."
          icon="services/hosting-maintenance.svg"
        />
      </div>
    </div>
    <div class="mb-8 xl:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Technologies</h2>
      <p class="text-base xl:text-lg mb-6">These are the technologies that we prefer working with when building new projects from scratch:</p>
      <div class="text-gray-500 font-bold grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-8">
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/vuejs.svg" />
          <span>Vue.js</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/nuxt.svg" />
          <span>Nuxt</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/nodejs.svg" />
          <span>Node.js</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/tailwind-css.svg" />
          <span>Tailwind CSS</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/postgresql.svg" />
          <span>PostgreSQL</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/wordpress.svg" />
          <span>WordPress</span>
        </div>
      </div>
    </div>
    <div>
      <h1 class="text-xl xl:text-2xl md:text-center mb-4">Let's build great projects together 🚀</h1>
      <div class="flex flex-col space-y-4 sm:flex-row sm:items-center md:justify-center sm:space-x-6 sm:space-y-0">
        <div>
          <div class="h-24 w-24 bg-cover rounded-full" :style="`background-image: url(${require('@/assets/images/manuel-joswig.jpeg')}); background-position: center 20%;`"></div>
        </div>
        <div>
          <b class="block xl:text-lg mb-1">Manuel Joswig</b>
          <ul class="flex flex-col space-y-1">
            <li class="flex items-center space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-envelope" viewBox="0 0 16 16">
                <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
              </svg>
              <span>manuel@joswigsolutions.com</span>
            </li>
            <li class="flex items-center space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
              </svg>
              <span>@manuel_joswig</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Card from '@/components/Card'

export default {
  name: 'IndexPage',
  components: {
    Card
  }
}
</script>
