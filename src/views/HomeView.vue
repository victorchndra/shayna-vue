<template>
  <div class="home">
    <HeaderShayna></HeaderShayna>
    <HeroShayna></HeroShayna>
    <WomenBannerShayna></WomenBannerShayna>
    <InstaShayna></InstaShayna>
    <PartnerLogoShayna></PartnerLogoShayna>
    <FooterShayna></FooterShayna>
  </div>
</template>

<script>
import HeaderShayna from '../components/HeaderShayna.vue';
import HeroShayna from '../components/HeroShayna.vue';
import WomenBannerShayna from '../components/WomenBannerShayna.vue';
import InstaShayna from '../components/InstaShayna.vue';
import PartnerLogoShayna from '../components/PartnerLogoShayna.vue';
import FooterShayna from '../components/FooterShayna.vue';
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBannerShayna,
    InstaShayna,
    PartnerLogoShayna,
    FooterShayna
}
}
</script>