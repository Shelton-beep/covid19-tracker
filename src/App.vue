<template>
  <HeaderComponent/>
  <div class="container">
  <router-view/>
  </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderComponent
  }
}
</script>
