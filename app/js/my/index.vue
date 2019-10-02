<template>
  <div>
    <home-header />
    <slider />
    <novice />
    <borrow />
    <money />
    <product />
    <life />
    <home-footer />
    <home-navbar />
  </div>
</template>
<script>
import HomeHeader from "../public/header.vue"
import HomeFooter from "../public/footer.vue"
import HomeNavbar from "../public/navbar.vue"
import slider from "./hslider"
import Novice from "./novice"
import Borrow from "./borrow"
import Money from "./money"
import Product from "./product"
import Life from "./life"

export default {
  components: {
    HomeHeader,
    slider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    HomeFooter,
    HomeNavbar
  }
}
</script>

<style lang="scss">
</style>
