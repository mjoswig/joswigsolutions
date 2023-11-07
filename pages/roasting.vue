<template>
  <div>
    <div class="flex flex-col space-y-4 mb-10">
      <div class="flex flex-col items-center justify-center text-center mb-4 md:mb-8 w-full">
        <h1 class="text-2xl xl:text-3xl mb-3">Want more customers?<br />Get a <mark>landing page roast</mark> 🔥</h1>
        <p class="text-lg mb-2">I will give you <b>actionable feedback</b> on design and marketing in Figma.</p>
        <p class="text-lg mb-5">48-hour turnaround time.</p>
        <Btn class="w-fit mb-3" @click="checkOut">
          <span>Get your roast for $49.99</span>
        </Btn>
        <span class="text-gray-500 text-xs md:text-sm">If you're not happy, I will refund the full cost of your roast. No questions asked.</span>
      </div>
      <div class="flex items-start justify-center w-full">
        <img class="border rounded-md shadow-sm" src="@/assets/images/roasting.png" />
      </div>
    </div>
    <div class="grid md:grid-cols-2 gap-10 mb-8">
      <div class="border bg-white p-4 rounded-md shadow-sm">
        <h1 class="text-xl xl:text-2xl mb-2">How it works 🚀</h1>
        <ol class="list-decimal flex flex-col space-y-2 ml-5">
          <li>Purchase the roasting service via Stripe. Mention the URL of your landing page.</li>
          <li>Wait 1-2 days. I'm getting many requests and don't work on weekends.</li>
          <li>You will receive an email from me. It will include the Figma link with my feedback.</li>
        </ol>
      </div>
      <div class="border bg-white p-4 rounded-md shadow-sm">
        <h1 class="text-xl xl:text-2xl mb-2">Roast examples 🌶️</h1>
        <ul class="list-disc flex flex-col space-y-2 ml-5">
          <li><a href="https://www.figma.com/file/mET33O1D84NHSQ1rkhNlri/Roasting-vidify.cloud?type=design&node-id=0%3A1&mode=design&t=Oy1q6rTOrOkBJTlP-1" target="_blank">Roasting vidify.cloud</a></li>
          <li><a href="https://www.figma.com/file/Qq4ln6Hds8bCjyBxVZMojT/Roasting-landix.art?type=design&node-id=0%3A1&mode=design&t=OeXnaXNcehU4yJlm-1" target="_blank">Roasting landix.art</a></li>
          <li><a href="https://www.figma.com/file/Q81PRakITr1UBqhtguVYrR/Roasting-docupull.com?type=design&node-id=0%3A1&mode=design&t=cUfO5KHwAV0GHJfo-1" target="_blank">Roasting docupull.com</a></li>
          <li><a href="https://www.figma.com/file/SiA052EjRHt5Onxrcx3nOQ/Roasting-dypt.app?type=design&node-id=0%3A1&mode=design&t=nIQyA3f9slzYcyNi-1" target="_blank">Roasting dypt.app</a></li>
          <li><a href="https://www.figma.com/file/idAw6k3i8LSYecsYts6D4n/Roasting-buildfolio.io?type=design&node-id=0%3A1&mode=design&t=3TQSe7nhNbyzOTaJ-1">Roasting buildfolio.io</a></li>
        </ul>
      </div>
    </div>
    <div>
      <h1 class="text-xl xl:text-2xl mb-2">Hey, it's Manuel 👋</h1>
      <p class="mb-2">I'm a solopreneur with over 10 years of experience in design, development, and marketing. When I was freelancing for digital agencies, I accompanied hundreds of website relaunches. I know how a good landing page should look like!</p>
      <p class=""></p>
      <p class="mb-6">Contact me on Twitter/X, if you have questions or concerns before purchasing your roast.</p>
      <ContactInfo />
    </div>
  </div>
</template>

<script>
import ContactInfo from '@/components/ContactInfo'

export default {
  name: 'RoastMyLandingPage',
  head() {
    return {
      title: 'Roast My Landing Page - Joswig Solutions'
    }
  },
  components: {
    ContactInfo
  },
  methods: {
    checkOut() {
      window.open('https://buy.stripe.com/fZe4jk8IV6Epb1SbIO', '_blank')
    }
  }
}
</script>
