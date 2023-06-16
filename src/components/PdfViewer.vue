<template>
  <div></div>
</template>

<script>
export default {
  mounted() {
    this.openPdf()
  },
  methods: {
    openPdf() {
      const file = this.$route.params.file
      const pdfUrl = '/ponerologia-psicopatas-no-poder' + file + '.pdf'
      // window.open(pdfUrl, '_blank')
    }
  }
}
</script>
