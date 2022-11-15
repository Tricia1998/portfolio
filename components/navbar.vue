<template>
    <div>
      <v-app-bar
        color="deep-purple accent-4"
        dense
        dark
        fixed
      >
      <img class="mr-3" :src="require('../static/logo.png')" height="40" />
      <v-spacer />
      <v-btn 
        text
        rounded
        class="mx-3 no-uppercase hidden-sm-and-down"
        @click="scrollToTop(), goToHome()">
        <span class="textcolor">Home</span></v-btn
      >
      <v-btn 
        text
        rounded
        class="mx-3 no-uppercase hidden-sm-and-down"
        @click="scrollTo(), goToAbout()">
        <span class="textcolor">About</span></v-btn
      >
      <v-btn
        text
        rounded
        class="mx-3 no-uppercase hidden-sm-and-down"
        @click="scroll(), goToPortfolio()">
        <span class="textcolor">Portfolio</span></v-btn
      >
      <v-btn
        text
        rounded
        class="mx-3 no-uppercase hidden-sm-and-down"
        @click="scrolled(), goToContactus()">
        <span class="textcolor">Contact Us</span></v-btn
      >
      <v-btn
        text
        rounded
        class="mx-3 no-uppercase hidden-sm-and-down"
        @click="scrolling(), goToTestimonies()">
        <span class="textcolor">Testimonies</span></v-btn
      >
          <v-spacer />
      <v-btn icon a href="https://www.facebook.com/profile.php?id=100011356793995">
        <v-icon>mdi-facebook</v-icon>
      </v-btn>

      <v-btn icon a href="https://www.instagram.com/">
        <v-icon>mdi-instagram</v-icon>
      </v-btn>

      <v-btn icon a href="https://twitter.com/home">
        <v-icon>mdi-twitter</v-icon>
      </v-btn>
      <v-btn icon a href="https://www.linkedin.com/notifications/">
        <v-icon>mdi-linkedin</v-icon>
      </v-btn>
      </v-app-bar>
    </div>
    
  </template>
  <script>
    export default {
      methods: {
        scrollToTop() {
            window.scrollTo(0, 0);
        },  goToHome() {
            this.$router.push('/');
        },
        scrollTo() {
            window.scrollTo(0, 800);
        },  goToAbout() {
            this.$router.push('/');
        },
        scroll() {
            window.scrollTo(0, 1970);
        },  goToPortfolio() {
            this.$router.push('/');
        },
        scrolled() {
            window.scrollTo(0, 2700);
        },  goToContactus() {
            this.$router.push('/');
        },
        scrolling() {
            window.scrollTo(0, 3300);
        },  goToTestimonies() {
            this.$router.push('/');
        }
      }
    };
    </script>
