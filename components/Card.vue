<template>
  <div class="bg-white border p-4 rounded-md shadow-sm flex flex-col space-y-2 sm:flex-row sm:space-x-4 sm:space-y-0">
    <div class="w-max">
      <img class="h-auto sm:mt-1" :class="{ 'w-12': !iconWidth }" :style="{ width: iconWidth }" :src="imageSrc" />
    </div>
    <div class="w-full">
      <div class="flex items-center space-x-2 mb-1">
        <h3 class="text-base">{{ title }}</h3>
        <span v-if="label" class="bg-gray-100 font-bold px-2 py-1 rounded-xl text-xs">{{ label }}</span>
      </div>
      <p class="text-sm">{{ description }}</p>
      <a v-if="url" class="inline-block mt-1 text-sm" :href="url" target="_blank">{{ url.replace('https://', '').replace('/', '') }}</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: ['title', 'description', 'label', 'icon', 'iconWidth', 'url'],
  computed: {
    imageSrc() {
      return require(`@/assets/images/${this.icon}`)
    }
  }
}
</script>