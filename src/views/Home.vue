<template>
  <div class="home">
    <headerSection/>
    <photo/>
  
  <stuff/>
  <footerSection/>
  </div>
</template>

<script>
// @ is an alias to /src
import headerSection from "@/components/headerSection.vue";
import photo from "@/components/photo.vue";
import stuff from "@/components/stuff.vue";
import footerSection from "@/components/footerSection.vue";





export default {
  name: "home",
  components: {
    headerSection,
    photo,
    
    stuff,
    footerSection
  }
};
</script>
