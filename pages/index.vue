<template>
  <div class="flex flex-col">
    <div class="text-center mb-6 md:mb-10">
      <h1 class="text-2xl xl:text-3xl mb-2">Joswig Solutions</h1>
      <p class="text-lg xl:text-xl mb-4 xl:mb-6">We are a web development company creating custom websites and web-based software.</p>
      <div class="flex justify-center text-sm xl:text-base">
        <Btn @click="openCalendly">Book a Discovery Call</Btn>
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Services</h2>
      <p class="text-base xl:text-lg mb-4">Would you like to hire us for a web project? Here is what we can do:</p>
      <div class="grid grid-cols gap-4">
        <Card
          title="Digital Strategy Consulting"
          description="If you need business advice on design, development, or marketing, we can come up with a solution for you."
          icon="services/it-marketing-consulting.png"
        />
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
      <p class="text-base xl:text-lg mb-4">We design, build, and grow digital platforms and online services.</p>
      <div class="grid gap-4">
        <Card
          title="Wishlist Page"
          description="A safe platform for creators, where fans can grant your wishes, adopt your bills, and pay for exclusive rewards."
          label="2022"
          icon="solutions/wishlistpage.png"
          url="https://wishlistpage.com/"
        />
        <Card
          title="PDF Public"
          description="A simple and secure service for sharing PDF files. Get your documents distributed fast and optimized for any device."
          label="2024"
          icon="solutions/pdfpublic.png"
          url="https://pdfpublic.com/"
        />
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Portfolio</h2>
      <p class="text-base xl:text-lg mb-4">Explore our past projects to get an idea of what we can accomplish together.</p>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <PortfolioSite
          title="Alibaba Germany"
          thumbnail="portfolio/alibaba-min.png"
          description="WordPress Website Relaunch for Alibaba Germany"
          label="2022"
          url="https://de.alibabagroup.com/"
        />
        <PortfolioSite
          title="Siemens Stiftung"
          thumbnail="portfolio/siemes-stiftung-min.png"
          description="WordPress Website Relaunch for Siemens Stiftung"
          label="2018"
          url="https://siemens-stiftung.org/"
        />
        <PortfolioSite
          title="XING"
          thumbnail="portfolio/deinjobleben-min.png"
          description="Landing Page for a marketing campaign by XING"
          label="2020"
          url="https://deinjobleben.xing.com/"
        />
        <PortfolioSite
          title="TriCAT"
          thumbnail="portfolio/tricat-min.png"
          description="WordPress Website Relaunch for TriCAT, a VR software company"
          label="2021"
          url="https://tricat.net/"
        />
        <PortfolioSite
          title="IP7 Technologies"
          thumbnail="portfolio/ip7-min.png"
          description="WordPress Website Relaunch for IP7 Technologies, an IP software startup"
          label="2022"
          url="https://ip7.tech/"
        />
        <PortfolioSite
          title="Traumanwalt"
          thumbnail="portfolio/traumanwalt-min.png"
          description="Directory that connects lawyers and law firms in Germany with clients"
          label="2023"
          url="https://traumanwalt.com/"
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
