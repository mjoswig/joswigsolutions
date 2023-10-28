<template>
  <div>
    <div class="flex flex-col space-y-4 md:flex-row md:space-x-8 md:space-y-0 items-center">
      <div class="flex flex-col items-center justify-center text-center md:block md:text-left w-full">
        <h1 class="text-2xl xl:text-3xl mb-2">Nuxt SaaS Boilerplate & Starter Kit – Launch your web app in days, not weeks</h1>
        <p class="text-lg mb-2">From zero to SaaS with no effort: This Nuxt 2 boilerplate comes with all the tools you need to build your next game-changing web app.</p>
        <p class="text-lg mb-4">Pre-order today and follow me <a href="https://twitter.com/manuel_joswig">@manuel_joswig</a> for updates. You can ask for a refund anytime.</p>
        <Btn class="w-fit" @click="preOrder">
          <span>Pre-order for <strike>$249.00</strike> $124.50</span>
        </Btn>
      </div>
      <div class="w-full">
        <img src="@/assets/images/nuxt-boilerplate.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtBoilerplatePage',
  head() {
    return {
      title: 'Nuxt SaaS Boilerplate & Starter Kit - Joswig Solutions'
    }
  },
  methods: {
    preOrder() {
      window.open('https://buy.stripe.com/00g6rs1gt0g11ri8wA?prefilled_promo_code=PREORDER50', '_blank')
    }
  }
}
</script>
