<template>
  <div>
  <navbarSection/>
  <nuxt/>
  <footerInfo/>
  <footerPolicy/>
  </div>
</template>


<script>
import navbarSection from '~/components/navbarSection.vue'
import footerPolicy from '~/components/footerPolicy.vue'
import footerInfo from '~/components/footerInfo.vue'
export default {
  components:{
    navbarSection,
    footerPolicy,
    footerInfo,
  }
    
}
</script>