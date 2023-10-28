<template>
  <div class="flex flex-col">
    <div class="text-center mb-6 md:mb-10">
      <h1 class="text-2xl xl:text-3xl mb-2">About Joswig Solutions</h1>
      <p class="text-lg xl:text-xl mb-4 xl:mb-6">We are a web development company with a focus on client services and web solutions.</p>
      <div class="flex flex-col space-y-3 md:flex-row items-center justify-center md:space-x-4 md:space-y-0 text-sm xl:text-base">
        <Btn @click="openCalendly">Launch Your MVP in 30 Days for $10K</Btn>
        <nuxt-link to="/nuxt-saas">Pre-order SaaS Boilerplate for $124.50</nuxt-link>
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
      <p class="mb-2">As your web development partner, we take full ownership of the applications we build, ensuring the implementation of proper design patterns to maintain clean and manageable code over time.</p>
      <p class="mb-2">Our websites are crafted with a focus on smooth user experiences, responsiveness, performance, and search engine optimization.</p>
      <p class="mb-6">Feel free to reach out for a chat about your project.</p>
      <ContactInfo />
    </div>
  </div>
</template>

<script>
import Btn from '@/components/Btn'
import Card from '@/components/Card'
import ContactInfo from '@/components/ContactInfo'
import PortfolioSite from '@/components/PortfolioSite'

export default {
  name: 'IndexPage',
  components: {
    Btn,
    Card,
    ContactInfo,
    PortfolioSite
  },
  methods: {
    openCalendly() {
      window.open('https://calendly.com/joswigsolutions/discovery-call', '_blank')
    }
  }
}
</script>
