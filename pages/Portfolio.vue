<template>
  <div>
    <NavbarComponent></NavbarComponent>
    <main></main>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
//  import { Carousel, Slide } from 'vue-carousel';
// import BackToTop from 'vue-backtotop'

export default {
  name: "Portfolio",
  // data: function() {
  //   return {
  //     specialty: 0,
  //     //   contentVisible: true
  //   };
  // },
  // created() {
  //   this.slider();
  // },
  // methods: {
  //   //   toggle: function(){
  //   //       this.contentVisible = !this.contentVisible
  //   //   }
  //   showSpecialty: function(e) {
  //     let value = Number(e.target.id);
  //     if (this.specialty == value) {
  //       this.specialty = 0;
  //     } else {
  //       this.specialty = value;
  //     }
  //   },
  //   backToTop() {
  //     window.scroll({
  //       top: 0,
  //       behavior: "smooth",
  //     });
  //   },
  // },
  components: {
    NavbarComponent,
    FooterComponent,
    //   Carousel,
    //  Slide,
    // BackToTop
  },
};
</script>
