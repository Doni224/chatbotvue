<template>
  <div class="home">
    <NavbarBaru />
    <HeroHead/>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Hero />
    <SemuaKoleksi/>
    <TentangKami/>
    <UlasanKami/>
    <KontakKami/>
  </div>
</template>

<script>
import NavbarBaru from '@/components/NavbarBaru.vue'
import HeroHead from '@/components/HeroHead.vue'
import SemuaKoleksi from '@/components/SemuaKoleksi.vue'
import TentangKami from '@/components/TentangKami.vue'
import UlasanKami from '@/components/UlasanKami.vue'
import KontakKami from '@/components/KontakKami.vue'
export default{
  name: 'HomeView',
  components: {
    NavbarBaru,
    HeroHead,
    SemuaKoleksi,
    TentangKami,
    UlasanKami,
    KontakKami
  }
}
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'HomeView',
//   components: {
//     HelloWorld
//   }
// }
</script>
