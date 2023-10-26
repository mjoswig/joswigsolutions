<template>
  <button class="font-bold shadow-md px-4 py-2 flex justify-center focus:outline-none" :class="buttonClasses" @click="onClick">
    <slot />
  </button>
</template>

<script>
export default {
  name: 'Btn',
  props: {
    type: {
      type: String,
      required: false,
      default: 'primary'
    },
    isDisabled: {
      type: Boolean,
      required: false
    }
  },
  computed: {
    buttonClasses() {
      return {
        'bg-gray-400 cursor-not-allowed text-white': this.isDisabled,
        'btn-bg-brand hover:btn-bg-brand-hover text-white': !this.isDisabled && this.type === 'primary',
        'bg-red-700 hover:bg-red-800 text-white': !this.isDisabled && this.type === 'danger',
        'bg-gray-200 hover:bg-gray-300 text-gray-700': !this.isDisabled && this.type === 'light'
      }
    }
  },
  methods: {
    onClick() {
      if (!this.isDisabled) {
        this.$emit('click')
      }
    }
  }
}
</script>

<style lang="postcss" scoped>
button {
  padding-left: 16px;
  padding-right: 16px;
  padding-top: 8px;
  padding-bottom: 8px;
  border-radius: 8px;
}

.btn-bg-brand {
  @apply text-white;
  background: #222222;
}

.btn-bg-brand.btn-disabled {
  background: gray;
  cursor: not-allowed;
}
</style>