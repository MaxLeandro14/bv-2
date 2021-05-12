<template>
  <v-app id="app">
     <TheHeader />
     <nuxt />
     <v-fab-transition>
      <v-btn
        fab
        dark
        right
        absolute
        class="v-btn-whats"
      >
        <v-icon>mdi-whatsapp</v-icon>
      </v-btn>
    </v-fab-transition>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>
<style>
#app {
  font-family: 'Roboto', sans-serif;
  background: #f5f5f5;
}
.v-btn-whats {
    bottom: 0;
    position: fixed;
    margin: 0 5px 5px 0;
    background-color: #23a728 !important;
    border-color: #23a728 !important;
  }
  .v-btn-whats .v-icon {
    font-size: 33px !important;
  }
</style>
