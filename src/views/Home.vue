<template>
  <div class="home">
    <HeaderLara />
    <HeroSectionLara />
    <BannerWomen />
    <InstaLara />
    <PartnerLara />
    <FooterLara />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderLara from "@/components/HeaderLara.vue";
import HeroSectionLara from "@/components/HeroSectionLara.vue";
import BannerWomen from "@/components/BannerWomen.vue";
import InstaLara from "@/components/InstaLara.vue";
import PartnerLara from "@/components/PartnerLara.vue";
import FooterLara from "@/components/FooterLara.vue";

export default {
  name: "home",
  components: {
    HeaderLara,
    HeroSectionLara,
    BannerWomen,
    InstaLara,
    PartnerLara,
    FooterLara,
  },
};
</script>
