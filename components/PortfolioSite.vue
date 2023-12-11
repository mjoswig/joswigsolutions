<template>
  <div class="bg-cover bg-center border rounded-md shadow-sm">
    <img class="border-b rounded-t-md h-auto w-full" :src="imageSrc" />
    <div class="bg-white p-4 w-full">
      <div class="flex items-center space-x-2 mb-1">
        <h3 class="text-base">{{ title }}</h3>
        <span class="bg-gray-100 font-bold px-2 py-1 rounded-xl text-xs">{{ label }}</span>
      </div>
      <p class="text-sm">{{ description }}</p>
      <a v-if="url" class="inline-block mt-1 text-sm" :href="url" target="_blank">{{ url.replace('https://', '').replace('/', '') }}</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PortfolioSite',
  props: ['title', 'description', 'label', 'thumbnail', 'url'],
  computed: {
    imageSrc() {
      return require(`@/assets/images/${this.thumbnail}`)
    }
  }
}
</script>