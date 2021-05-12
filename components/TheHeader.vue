<template>
  <div>
    <div class="logo-empresa">
         <v-avatar class="logo-empresa-img">
            <img
              src="~/assets/imagem_1569525449.jpg"
              alt="John"
            >
          </v-avatar>
          <p class="text-empre">TÔ de folga</p>
          <p class="text-empre-desc">Somos uma plataforma super fácil e rápida para vender online.</p>
          
    </div>
    <div class="container-search">
      <v-toolbar
        dark
        color="teal"
      >
        <!--<v-toolbar-title>Filtro</v-toolbar-title>-->
        <v-icon>mdi-briefcase-search-outline</v-icon>
        <v-autocomplete
          v-model="select"
          :items="items"
          cache-items
          class="mx-4"
          flat
          hide-no-data
          hide-details
          label="Qual o seu destino?"
          solo-inverted
        ></v-autocomplete>
      </v-toolbar>
    </div>
  </div>
</template>
<script>
  export default {
    data: () => ({
      items: ['Foo', 'Bar', 'Fizz', 'Buzz'],
      select: '',
    }),
  }
</script>
<style>
.logo-empresa {
  display: flex;
  align-items: center;
  flex-direction: column;
  margin-top: 15px;
}
.logo-empresa-img {
  height: 115px !important;
  min-width: 115px !important;
  width: 115px !important;
  margin: 10px;
  float: right;
  box-shadow: 0px 0px 6px rgb(0 0 0 / 50%);
}
.text-empre{
  color: #435b71;
  font-weight: 600;
  font-size: 23px;
  margin: 0px !important;
}
.container-search{
  max-width: 500px;
  margin: 13px auto;
  padding: 0px 5px;
}
.text-empre-desc {
  padding: 2px 5px;
  font-size: 18px;
}
</style>