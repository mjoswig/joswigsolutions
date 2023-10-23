<template>
  <div class="bg-white border p-4 rounded-md shadow-sm flex flex-col space-y-2 sm:flex-row sm:space-x-4 sm:space-y-0">
    <div class="w-max">
      <img class="h-auto sm:mt-1" :class="{ 'w-12': !iconWidth }" :style="{ width: iconWidth }" :src="imageSrc" />
    </div>
    <div class="w-full">
      <h3 class="text-base mb-1">{{ title }}</h3>
      <p class="text-sm">{{ description }}</p>
      <a v-if="url" class="inline-block mt-1 text-sm" :href="url" target="_blank">{{ url.replace('https://', '').replace('/', '') }}</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: ['title', 'description', 'icon', 'iconWidth', 'url'],
  computed: {
    imageSrc() {
      return require(`@/assets/images/${this.icon}`)
    }
  }
}
</script>