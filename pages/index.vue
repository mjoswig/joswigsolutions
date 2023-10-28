<template>
  <div class="flex flex-col">
    <div class="text-center mb-6 md:mb-10">
      <h1 class="text-2xl xl:text-3xl mb-2">About Joswig Solutions</h1>
      <p class="text-lg xl:text-xl mb-4 xl:mb-6">We are a web development company with a focus on client services and web solutions.</p>
      <div class="flex flex-col space-y-2 md:flex-row items-center justify-center md:space-x-4 md:space-y-0 text-sm xl:text-base">
        <Btn @click="openCalendly">Launch Your MVP in 30 Days for $10K</Btn>
        <nuxt-link to="/nuxt-saas">Pre-order Boilerplate for $124.50</nuxt-link>
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Services</h2>
      <p class="text-base xl:text-lg mb-4">Would you like to hire us for a web project? Here is what we can do:</p>
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
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Solutions</h2>
      <p class="text-base xl:text-lg mb-4">We operate two online platforms, one for creators and one for lawyers.</p>
      <div class="grid sm:grid-cols-2 gap-4">
        <Card
          title="Wishlist Page"
          description="A privacy-first gifting platform for content creators, where fans can fund your wishes or adopt your monthly bills."
          icon="solutions/wishlistpage.png"
          url="https://wishlistpage.com/"
        />
        <Card
          title="Traumanwalt"
          description="A legal tech platform that connects lawyers and law firms in Germany with people looking for legal advice."
          icon="solutions/traumanwalt.png"
          icon-width="64px"
          url="https://traumanwalt.com/"
        />
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Portfolio</h2>
      <p class="text-base xl:text-lg mb-4">Here are websites that we have built for our clients and agency partners.</p>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <PortfolioSite
          title="Alibaba Germany (2022)"
          thumbnail="portfolio/alibaba-min.png"
          description="WordPress Website Relaunch for Alibaba Germany"
          url="https://de.alibabagroup.com/"
        />
        <PortfolioSite
          title="Siemens Stiftung (2018)"
          thumbnail="portfolio/siemes-stiftung-min.png"
          description="WordPress Website Relaunch for Siemens Stiftung"
          url="https://siemens-stiftung.org/"
        />
        <PortfolioSite
          title="XING – Dein Job Leben (2020)"
          thumbnail="portfolio/deinjobleben-min.png"
          description="Landing Page for a marketing campaign by XING"
          url="https://deinjobleben.xing.com/"
        />
        <PortfolioSite
          title="TriCAT (2021)"
          thumbnail="portfolio/tricat-min.png"
          description="WordPress Website Relaunch for TriCAT, a VR software company"
          url="https://tricat.net/"
        />
        <PortfolioSite
          title="IP7 Technologies (2022)"
          thumbnail="portfolio/ip7-min.png"
          description="WordPress Website Relaunch for IP7 Technologies, an IP software startup"
          url="https://ip7.tech/"
        />
        <PortfolioSite
          title="cvwizard (2023)"
          thumbnail="portfolio/cvwizard-min.png"
          description="Web App for building professional CVs online in just a few minutes"
          url="https://cvwizard.netlify.app/"
        />
      </div>
    </div>
    <div class="mb-8 md:mb-16">
      <h2 class="text-xl xl:text-2xl mb-1">Technologies</h2>
      <p class="text-base xl:text-lg mb-6">These are the technologies that we prefer working with when starting new projects from scratch:</p>
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-8">
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/vuejs.svg" />
          <span>Vue.js</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/nuxt.svg" />
          <span>Nuxt</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/tailwind-css.svg" />
          <span>Tailwind CSS</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/javascript.svg" />
          <span>JavaScript</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/typescript.svg" />
          <span>TypeScript</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/nodejs.svg" />
          <span>Node.js</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/php.svg" />
          <span>PHP</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/postgresql.svg" />
          <span>PostgreSQL</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/mysql.svg" />
          <span>MySQL</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/wordpress.svg" />
          <span>WordPress</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/firebase.svg" />
          <span>Firebase</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/stripe.png" />
          <span>Stripe</span>
        </div>
      </div>
    </div>
    <div class="md:mb-8 xl:mb-4">
      <h1 class="text-xl xl:text-2xl mb-2">Let's turn your idea into reality</h1>
      <div class="text-base xl:text-lg mb-6">
        <p class="mb-2">As your web development partner, we take full ownership of the applications we build, ensuring the implementation of proper design patterns to maintain clean and manageable code over time.</p>
        <p class="mb-2">Our websites are crafted with a focus on smooth user experiences, responsiveness, performance, and search engine optimization.</p>
        <p>Feel free to reach out for a chat about your project.</p>
      </div>
      <div class="flex flex-col space-y-4 sm:flex-row sm:items-center sm:space-x-6 sm:space-y-0">
        <div>
          <div class="h-28 w-28 sm:h-32 sm:w-32 bg-cover rounded-full" :style="`background-image: url(${require('@/assets/images/manuel-joswig.jpeg')}); background-position: center 20%;`"></div>
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
              <a href="https://twitter.com/manuel_joswig" target="_blank">@manuel_joswig</a>
            </li>
            <li class="flex items-center space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-github" viewBox="0 0 16 16">
                <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
              </svg>
              <a href="https://github.com/mjoswig" target="_blank">@mjoswig</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Btn from '@/components/Btn'
import Card from '@/components/Card'
import PortfolioSite from '@/components/PortfolioSite'

export default {
  name: 'IndexPage',
  components: {
    Btn,
    Card,
    PortfolioSite
  },
  methods: {
    openCalendly() {
      window.open('https://calendly.com/joswigsolutions/discovery-call', '_blank')
    }
  }
}
</script>
