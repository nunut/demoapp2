<template>

  <MenuComponent />
  <h1>Home page</h1>
  <router-view/>
  <FooterComponent />

</template>
<script>
  import MenuComponent from '@/components/MenuComponent.vue'
  import FooterComponent from '@/components/FooterComponent.vue'
 
  export default {
    components: {MenuComponent, FooterComponent}

}
</script>