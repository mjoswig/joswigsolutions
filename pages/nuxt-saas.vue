<template>
  <div>
    <div class="flex flex-col space-y-4 md:flex-row md:space-x-8 md:space-y-0 mb-6 md:mb-10">
      <div class="flex flex-col items-center justify-center text-center md:block md:text-left w-full md:pt-6">
        <h1 class="text-2xl xl:text-3xl mb-2">Nuxt SaaS Boilerplate & Starter Kit – Launch your web app in days, not weeks</h1>
        <p class="text-lg mb-2">From zero to SaaS with no effort: This Nuxt 2 boilerplate comes with all the tools you need to build your next game-changing web app.</p>
        <p class="text-lg mb-4"><b>Pre-order</b> today and follow me <a href="https://twitter.com/manuel_joswig">@manuel_joswig</a> for updates. You can ask for a refund anytime.</p>
        <Btn class="w-fit" @click="preOrder">
          <span>Pre-order for <strike>$249.00</strike> $124.50</span>
        </Btn>
      </div>
      <div class="flex justify-center w-full">
        <img src="@/assets/images/nuxt-boilerplate.svg" />
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-2">A new age of launching 🚀</h2>
      <p class="mb-4">You want to build software products and launch quickly, but you're left wasting months implementing commonplace functionality. On top of that, you're forced to learn countless new frameworks to integrate the full stack.</p>
      <div class="flex flex-col-reverse md:flex-row">
        <div class="grid grid-cols-4 gap-8 md:gap-4 w-full mt-8 md:mt-4">
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/vuejs.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/nuxt.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/tailwind-css.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/javascript.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/nodejs.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/postgresql.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/firebase.svg" />
          </div>
          <div>
            <img class="h-8 md:h-10 w-auto" src="@/assets/images/technologies/stripe.png" />
          </div>
        </div>
        <div class="md:mt-2 w-full">
          <h3 class="text-base xl:text-lg mb-1">Introducing Nuxt SaaS</h3>
          <p>Nuxt SaaS Boilerplate & Starter Kit is a codebase that includes a fundamental structure and ready-made components for developing SaaS applications of any kind. Now, you can focus on building unique features that generate revenue and provide value to customers.</p>
        </div>
      </div>
    </div>
    <div class="mb-8 md:mb-12">
      <h2 class="text-xl xl:text-2xl mb-2">What's included in Nuxt SaaS?</h2>
      <p class="mb-4">Get unlimited access to the features below with a one-time payment. Receive all updates for free.</p>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-house-door h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4.5a.5.5 0 0 0 .5-.5v-4h2v4a.5.5 0 0 0 .5.5H14a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146ZM2.5 14V7.707l5.5-5.5 5.5 5.5V14H10v-4a.5.5 0 0 0-.5-.5h-3a.5.5 0 0 0-.5.5v4H2.5Z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">Landing Page</h3>
          <p>Use beautifully pre-built feature and pricing card components to show customers why they need your app.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-file-earmark h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M14 4.5V14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h5.5L14 4.5zm-3 0A1.5 1.5 0 0 1 9.5 3V1H4a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V4.5h-2z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">Blog CMS</h3>
          <p>Effortlessly create and publish content to attract new users to your software product, directly in Notion.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-person-lock h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M11 5a3 3 0 1 1-6 0 3 3 0 0 1 6 0ZM8 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4Zm0 5.996V14H3s-1 0-1-1 1-4 6-4c.564 0 1.077.038 1.544.107a4.524 4.524 0 0 0-.803.918A10.46 10.46 0 0 0 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h5ZM9 13a1 1 0 0 1 1-1v-1a2 2 0 1 1 4 0v1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-2Zm3-3a1 1 0 0 0-1 1v1h2v-1a1 1 0 0 0-1-1Z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">User Authentication</h3>
          <p>Manage your secure authentication system with Firebase and provide a seamless experience for end users.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-key h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M0 8a4 4 0 0 1 7.465-2H14a.5.5 0 0 1 .354.146l1.5 1.5a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 0 1-.708 0L13 9.207l-.646.647a.5.5 0 0 1-.708 0L11 9.207l-.646.647a.5.5 0 0 1-.708 0L9 9.207l-.646.647A.5.5 0 0 1 8 10h-.535A4 4 0 0 1 0 8zm4-3a3 3 0 1 0 2.712 4.285A.5.5 0 0 1 7.163 9h.63l.853-.854a.5.5 0 0 1 .708 0l.646.647.646-.647a.5.5 0 0 1 .708 0l.646.647.646-.647a.5.5 0 0 1 .708 0l.646.647.793-.793-1-1h-6.63a.5.5 0 0 1-.451-.285A3 3 0 0 0 4 5z"/>
            <path d="M4 8a1 1 0 1 1-2 0 1 1 0 0 1 2 0z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">Password Reset</h3>
          <p>Allow your users to easily update their account credentials with a pre-built password reset email flow.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-cart3 h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .49.598l-1 5a.5.5 0 0 1-.465.401l-9.397.472L4.415 11H13a.5.5 0 0 1 0 1H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5zM3.102 4l.84 4.479 9.144-.459L13.89 4H3.102zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4zm-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2zm7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">Subscription Management</h3>
          <p>Monetize with Stripe right away and focus on marketing instead of troubleshooting payment workflows.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-braces h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M2.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C3.25 2 2.49 2.759 2.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6zM13.886 7.9v.163c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456V7.332c-1.114 0-1.49-.362-1.49-1.456V4.352C13.51 2.759 12.75 2 11.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">REST API</h3>
          <p>Connect your PostgreSQL database and add backend API routes to create, read, update, and delete your data.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-globe h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855A7.97 7.97 0 0 0 5.145 4H7.5V1.077zM4.09 4a9.267 9.267 0 0 1 .64-1.539 6.7 6.7 0 0 1 .597-.933A7.025 7.025 0 0 0 2.255 4H4.09zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a6.958 6.958 0 0 0-.656 2.5h2.49zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5H4.847zM8.5 5v2.5h2.99a12.495 12.495 0 0 0-.337-2.5H8.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5H4.51zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5H8.5zM5.145 12c.138.386.295.744.468 1.068.552 1.035 1.218 1.65 1.887 1.855V12H5.145zm.182 2.472a6.696 6.696 0 0 1-.597-.933A9.268 9.268 0 0 1 4.09 12H2.255a7.024 7.024 0 0 0 3.072 2.472zM3.82 11a13.652 13.652 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5H3.82zm6.853 3.472A7.024 7.024 0 0 0 13.745 12H11.91a9.27 9.27 0 0 1-.64 1.539 6.688 6.688 0 0 1-.597.933zM8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855.173-.324.33-.682.468-1.068H8.5zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.65 13.65 0 0 1-.312 2.5zm2.802-3.5a6.959 6.959 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5h2.49zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7.024 7.024 0 0 0-3.072-2.472c.218.284.418.598.597.933zM10.855 4a7.966 7.966 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4h2.355z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">Easy Hosting</h3>
          <p>Deploy to any cloud provider with a single line of code. Nuxt SaaS runs on Vercel, Render, Heroku, and other platforms.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-search h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">SEO Meta Tags</h3>
          <p>Add site metadata and give search engines the important information about your web pages they need.</p>
        </div>
        <div class="bg-white border p-4 rounded-md shadow-sm">
          <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-box2-heart h-6 w-auto xl:h-8 mb-2" viewBox="0 0 16 16">
            <path d="M8 7.982C9.664 6.309 13.825 9.236 8 13 2.175 9.236 6.336 6.31 8 7.982Z"/>
            <path d="M3.75 0a1 1 0 0 0-.8.4L.1 4.2a.5.5 0 0 0-.1.3V15a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V4.5a.5.5 0 0 0-.1-.3L13.05.4a1 1 0 0 0-.8-.4h-8.5Zm0 1H7.5v3h-6l2.25-3ZM8.5 4V1h3.75l2.25 3h-6ZM15 5v10H1V5h14Z"/>
          </svg>
          <h3 class="text-base xl:text-lg mb-1">Lifetime Updates & Support</h3>
          <p>Access our repository with lifetime updates. For guaranteed email support, please <a href="https://buy.stripe.com/eVaaHIaR33sd3zqfZ3" target="_blank">subscribe to a plan</a>. Cancel anytime <a href="https://billing.stripe.com/p/login/6oE8yOdEJ8On5TGdQQ" target="_blank">here</a>.</p>
        </div>
      </div>
    </div>
    <div>
      <h1 class="text-xl xl:text-2xl mb-2">Hey, it's Manuel 👋</h1>
      <p class="mb-2">After many years of developing SaaS projects, I realized I was doing the same thing over and over: set up DNS records, listen to Stripe webhooks, design pricing section...</p>
      <p class="mb-2">So I decided to build Nuxt SaaS for 3 reasons:</p>
      <ol class="flex flex-col space-y-1 list-decimal ml-5 mb-2">
        <li><b>Save time</b> and focus on what matters: building a business</li>
        <li><b>Avoid headaches</b> like dealing with user login or spending days to set up a blog.</li>
        <li><b>Get profitable fast</b> – the more you ship, the more you learn, the more you earn.</li>
      </ol>
      <p class="mb-6">Follow me on Twitter/X, if you have any questions before pre-ordering Nuxt SaaS.</p>
      <ContactInfo />
    </div>
  </div>
</template>

<script>
import ContactInfo from '@/components/ContactInfo'

export default {
  name: 'NuxtBoilerplatePage',
  head() {
    return {
      title: 'Nuxt SaaS Boilerplate & Starter Kit - Joswig Solutions'
    }
  },
  components: {
    ContactInfo
  },
  methods: {
    preOrder() {
      window.open('https://buy.stripe.com/00g6rs1gt0g11ri8wA?prefilled_promo_code=PREORDER50', '_blank')
    }
  }
}
</script>
