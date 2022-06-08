<template>
  <div class="d-flex flex-column min-vh-100">
    <HeaderView></HeaderView>
    <FooterView class="mt-auto"></FooterView>
  </div>
</template>

<script>
import HeaderView from './views/HeaderView.vue';
import FooterView from './views/FooterView.vue';
export default {
    name: "App",
    components: { HeaderView, FooterView }
}
</script>
