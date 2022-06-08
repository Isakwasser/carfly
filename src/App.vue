<template>
  <div class="d-flex flex-column min-vh-100">
    <HeaderView></HeaderView>
    <FormView class="d-none"></FormView>
    <ServicesView></ServicesView>
    <FooterView class="mt-auto"></FooterView>
  </div>
</template>

<script>
import HeaderView from './views/HeaderView.vue';
import FooterView from './views/FooterView.vue';
import FormView from './views/FormView.vue';
import ServicesView from './views/ServicesView.vue';
export default {
    name: "App",
    components: { HeaderView, FooterView, FormView, ServicesView }
}
</script>
