<template>
  <div class="flex flex-col">
    <div class="text-center mb-6 md:mb-10">
      <h1 class="text-2xl xl:text-3xl mb-2">Joswig Solutions</h1>
      <p class="text-lg xl:text-xl">We build leading internet and technology solutions.</p>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-1">Solutions</h2>
      <p class="text-base xl:text-lg mb-4">Here is a brief overview of our digital platforms and products.</p>
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
      <p class="text-base xl:text-lg mb-4">Would you like to hire us for a web project? These are things we can do.</p>
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
  }
}
</script>
