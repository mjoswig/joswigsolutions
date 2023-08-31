<template>
  <div>
    <h1 class="text-2xl xl:text-3xl mt-5 xl:mt-0 mb-6">Legal</h1>
    <div class="grid md:grid-cols-2 gap-6 mb-6">
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
    <div class="mb-6">
      <h2 class="text-xl xl:text-2xl mb-2">Board of Directors</h2>
      <p class="mb-1">Manuel Joswig</p>
      <p>Email: manuel@joswigsolutions.com</p>
    </div>
    <div>
      <h2 class="text-xl xl:text-2xl mb-2">Copyright Notice</h2>
      <p>All contents of this website, in particular texts, photographs and graphics, are protected by copyright. Unless otherwise expressly indicated, the copyright is held by Joswig Solutions. Please contact us if you wish to use the contents of this website. Contents published under the "Creative Commons License" are marked as such. They may be used in accordance with the stated license conditions.</p>
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
