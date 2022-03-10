<template>
  <div>
    <wordPress/>
    <div class="picSection">
        <leftBar/>
        <picZone/>
    </div>
    <phone/>
  </div>
</template>


<script>
import phone from '~/components/webShop/phone.vue'
import wordPress from '~/components/webShop/wordPress.vue'
import leftBar from '~/components/webShop/leftBar.vue'
import picZone from '~/components/webShop/picZone.vue'
export default {
  components:{
    phone,
    wordPress,
    leftBar,
    picZone,
  }
}
</script>
<style scoped>
.picSection{
  width: 1220px;
  display: grid;
  grid-template-columns: 340px 1fr;
  position: relative;
  grid-gap: 17px;
  margin: 0px 110px;
}
</style>