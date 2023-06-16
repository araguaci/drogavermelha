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
      const pdfUrl = '/droga_vermelha_josepf_douglass' + file + '.pdf'
      // window.open(pdfUrl, '_blank')
    }
  }
}
</script>
