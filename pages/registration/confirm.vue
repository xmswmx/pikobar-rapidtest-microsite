<template>
  <div class="container mx-auto p-6">
    <h2 class="text-xl text-gray-900 text-center">
      Periksa Isian Data
    </h2>

    <p class="mt-4 text-sm">
      Klik tombol <strong>Kirim</strong> untuk menyelesaikan proses pendaftaran Anda.
    </p>

    <div class="mt-12">
      <nuxt-link to="/registration/done" class="block items-center justify-center px-5 py-3 text-base leading-6 font-medium rounded-lg text-white bg-brand-orange text-center">
        Kirim
      </nuxt-link>
      <nuxt-link to="/registration/additional" class="block items-center justify-center px-5 py-3 text-base leading-6 font-medium rounded-lg border border-brand-green-dark text-brand-green-dark text-center mt-2">
        Kembali
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  //
}
</script>
