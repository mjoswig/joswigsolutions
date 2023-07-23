<template>
  <div>
    <h1 class="text-2xl xl:text-3xl mb-6">Legal</h1>
    <div class="grid md:grid-cols-2 gap-4">
      <div>
        <h2 class="text-xl xl:text-2xl mb-2">Joswig Solutions UG</h2>
        <p class="mb-1">Schaperstraße 14</p>
        <p class="mb-1">10719 Berlin</p>
        <p class="mb-1">Germany</p>
        <p class="mb-1">Amtsgericht Charlottenburg (HRB 204652)</p>
        <p>VAT ID: DE321357009</p>
      </div>
      <div>
        <h2 class="text-xl xl:text-2xl mb-2">Joswig Solutions US, LLC</h2>
        <p class="mb-1">651 N Broad St</p>
        <p class="mb-1">Suite 201</p>
        <p class="mb-1">Middletown, DE 19709</p>
        <p>United States</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LegalPage',
  head() {
    return {
      title: 'Legal - Joswig Solutions'
    }
  }
}
</script>
