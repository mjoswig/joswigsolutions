<template>
  <div class="flex flex-col">
    <div class="text-center mb-6 md:mb-10">
      <h1 class="text-2xl xl:text-3xl mb-2">Joswig Solutions</h1>
      <p class="text-lg xl:text-xl">We are a web development company creating custom websites and web-based software.</p>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Solutions</h2>
      <p class="text-base xl:text-lg mb-4">We design, build, and grow digital platforms and online services.</p>
      <div class="grid gap-4">
        <Card
          title="Wishlistpage"
          description="A safe platform for creators, where fans can grant your wishes, adopt your bills, and pay for exclusive rewards."
          label="2022"
          icon="solutions/wishlistpage.png"
          url="https://wishlistpage.com/"
        />
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Services</h2>
      <p class="text-base xl:text-lg mb-4">Would you like to hire us for a web project? Here is what we can do:</p>
      <div class="grid md:grid-cols-2 gap-4">
        <Card
          title="Digital Strategy Consulting"
          description="We create a roadmap for your project and connect you to the right partners to help you achieve your business objectives."
          icon="services/digital-strategy-consulting.png"
        />
        <Card
          title="Digital Product Design"
          description="Together with our clients, we challenge traditional business models and bring new ones to profitable fruition."
          icon="services/digital-product-design.svg"
        />
        <Card
          title="Custom Web Development"
          description="We develop websites and business applications tailored individually to reflect and resolve the needs of our clients."
          icon="services/software-development.svg"
        />
        <Card
          title="Hosting & Maintenance"
          description="We take care of your project and guarantee a high level of availability, performance, flexibility, and scalability."
          icon="services/hosting-maintenance.svg"
        />
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
