<template>
  <div>
    <div class="flex flex-col space-y-4 md:flex-row md:space-x-8 md:space-y-0 mb-6 md:mb-10">
      <div class="flex flex-col items-center justify-center text-center md:block md:text-left w-full md:pt-6">
        <h1 class="text-2xl xl:text-3xl mb-2">Nuxt SaaS Boilerplate & Starter Kit – Launch your web app in days, not weeks</h1>
        <p class="text-lg mb-2">From zero to SaaS with no effort: This Nuxt 2 boilerplate comes with all the tools you need to build your next game-changing web app.</p>
        <p class="text-lg mb-4">Pre-order today and follow me <a href="https://twitter.com/manuel_joswig">@manuel_joswig</a> for updates. You can ask for a refund anytime.</p>
        <Btn class="w-fit" @click="preOrder">
          <span>Pre-order for <strike>$249.00</strike> $124.50</span>
        </Btn>
      </div>
      <div class="flex justify-center w-full">
        <img src="@/assets/images/nuxt-boilerplate.svg" />
      </div>
    </div>
    <div class="mb-6 md:mb-10">
      <h2 class="text-xl xl:text-2xl mb-2">A new age of launching 🚀</h2>
      <p class="mb-4">You want to build software products and launch quickly, but you're left wasting months implementing commonplace functionality. On top of that, you're forced to learn countless new languages and frameworks to integrate the full stack.</p>
      <h3 class="text-base xl:text-lg mb-1">Introducing Nuxt SaaS</h3>
      <p>Nuxt SaaS Boilerplate & Starter Kit is a codebase that takes care of the fundamental structure and components standard to all SaaS applications. Now, you can focus on building unique features that generate revenue and provide value to customers.</p>
    </div>
    <div>
      <h2 class="text-xl xl:text-2xl mb-4">What is included in Nuxt SaaS?</h2>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">User Authentication</h3>
          <p>Manage your secure authentication system with Firebase and provide a seamless experience for end users.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">Password Reset</h3>
          <p>Allow your users to easily update their account credentials with a pre-built password reset email flow.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">Subscription Management</h3>
          <p>Monetize with Stripe right away and focus on marketing instead of troubleshooting payment workflows.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">Landing Page</h3>
          <p>Use beautifully pre-built feature and pricing card components to show customers why they need your app.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">Blog CMS</h3>
          <p>Effortlessly create and publish content to attract new users to your software product, directly in Notion.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">REST API</h3>
          <p>Connect your PostgreSQL database and add backend API routes to create, read, update, and delete your data.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">Easy Hosting</h3>
          <p>Deploy to any cloud provider with a single line of code. Nuxt SaaS runs on Vercel, Render, Heroku, and other platforms.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">SEO Meta Tags</h3>
          <p>Add site metadata and give search engines the important information about your web pages they need.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <h3 class="text-base xl:text-lg mb-1">Lifetime Updates & Support</h3>
          <p>Access our repository with lifetime updates. For guaranteed email support, please <a href="https://buy.stripe.com/eVaaHIaR33sd3zqfZ3" target="_blank">subscribe to a plan</a>! Cancel anytime <a href="https://billing.stripe.com/p/login/6oE8yOdEJ8On5TGdQQ" target="_blank">here</a>.</p>
        </div>
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
