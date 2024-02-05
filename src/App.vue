<script setup>
import Login from './views/auth/LoginView.vue';
// import AccountView from './views/auth/AccountView.vue';
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
// import WishlistView from './views/WishlistView.vue';
// import ThanksView from './views/ThanksView.vue';

// import CompareView from './views/CompareView.vue';
// import CartView from './views/CartView.vue';
// import CheckoutView from './views/CheckoutView.vue';



</script>

<template>
  <Header/>
  <Login />
  <!-- <CartView /> -->
  <!-- <CheckoutView /> -->
  <!-- <CompareView /> -->
  <!-- <AccountView /> -->
  <!-- <WishlistView /> -->
  <!-- <ThanksView /> -->
  <Footer/>
  <RouterView />
</template>

<style scoped>

</style>
