<template>
  <div class="home">
    <HeaderHB />
    <HeroHB />
    <ProductHB />
    <IklanHB />
    <FooterHB />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderHB from '@/components/HeaderHB.vue'
import HeroHB from '@/components/HeroHB.vue'
import ProductHB from '@/components/ProductHB.vue'
import IklanHB from '@/components/IklanHB.vue'
import FooterHB from '@/components/FooterHB.vue'


export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderHB,
    HeroHB,
    ProductHB,
    IklanHB,
    FooterHB
    
  }
}
</script>
