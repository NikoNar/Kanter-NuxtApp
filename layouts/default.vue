<template>
  <div>

    <page-header></page-header>

    <Nuxt />

    <page-footer></page-footer>

  </div>
</template>



<script>
import PageHeader from '~/components/PageHeader.vue'
import PageFooter from '~/components/PageFooter.vue'
  export default {
  components: { PageHeader, PageFooter },
    
  }


  
</script>


