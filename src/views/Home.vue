<template>
  <div>
    <homeSection />
    <exploreSection />
    <createSection />
    <footerSection />
  </div>
</template>

<script>
  // @ is an alias to /src
  
  import homeSection from '@/components/HomeSection.vue'
  import exploreSection from '@/components/ExploreSection.vue'
  import createSection from '@/components/CreateSection.vue'
  import footerSection from '@/components/FooterSection.vue'
  
  export default {
    name: 'home',
    components: {
      homeSection,
      exploreSection,
      createSection,
      footerSection,
    }
  }
</script>
