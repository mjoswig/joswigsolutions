<template>
  <div class="flex flex-col">
    <div class="text-center mb-6 md:mb-10">
      <h1 class="text-2xl xl:text-3xl mb-2">Joswig Solutions</h1>
      <p class="text-lg xl:text-xl">We build and invest in internet & technology solutions.</p>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Solutions</h2>
      <p class="text-base xl:text-lg mb-4">Explore our digital platforms and software products.</p>
      <div class="grid grid-cols gap-4">
        <Card
          title="Wishlistpage"
          description="A privacy-focused platform for creators to accept gift funds and tips from fans."
          label="2022"
          icon="solutions/wishlistpage.png"
          url="https://wishlistpage.com/"
        />
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Services</h2>
      <p class="text-base xl:text-lg mb-4">Would you like to hire us for a web project? Here is what we can do.</p>
      <div class="grid md:grid-cols-2 gap-4">
        <Card
          title="Digital Strategy Consulting"
          description="We create a roadmap and introduce you to the right partners to help you achieve your business objectives."
          icon="services/digital-strategy-consulting.png"
        />
        <Card
          title="Digital Product Design"
          description="We craft high-end digital products for desktop and mobile devices that your customers will fall in love with."
          icon="services/digital-product-design.svg"
        />
        <Card
          title="Website & Software Development"
          description="We develop websites and software applications tailored individually to reflect and resolve the needs of your business."
          icon="services/software-development.svg"
        />
        <Card
          title="Hosting & Maintenance"
          description="We take care of your project and guarantee a high level of availability, performance, flexibility, and scalability."
          icon="services/hosting-maintenance.svg"
        />
      </div>
    </div>
    <div class="mb-8 md:mb-16">
      <h2 class="text-xl xl:text-2xl mb-1">Technologies</h2>
      <p class="text-base xl:text-lg mb-6">Below are the front-end and back-end technologies that we work with.</p>
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
          <img class="h-10 w-auto" src="@/assets/images/technologies/react.svg" />
          <span>React</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/nextjs.svg" />
          <span>Next.js</span>
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
          <img class="h-10 w-auto" src="@/assets/images/technologies/postgresql.svg" />
          <span>PostgreSQL</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/mysql.svg" />
          <span>MySQL</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/php.svg" />
          <span>PHP</span>
        </div>
        <div class="flex flex-col items-center space-y-2">
          <img class="h-10 w-auto" src="@/assets/images/technologies/wordpress.svg" />
          <span>WordPress</span>
        </div>
      </div>
    </div>
    <div class="md:mb-8 xl:mb-4">
      <h1 class="text-xl xl:text-2xl mb-2">Let's turn your idea into reality</h1>
      <p class="text-base xl:text-lg mb-6">Get in touch for a quick chat about your project. I'm looking forward to meet you!</p>
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
