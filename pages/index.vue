<template>
<v-container>
  <v-row>
    <!---->
    <v-col md="4">
      
        <v-card
          class="mx-auto"
          max-width="320"
        >
          <v-carousel 
          :show-arrows="false"
          hide-delimiter-background
          delimiter-icon="mdi-minus"
          height="200"
          show-arrows-on-hover
          >
              <v-carousel-item
                src="https://i.pinimg.com/originals/d9/f1/5e/d9f15e78f0ac37de87d9b95b545ed03d.jpg"
              ></v-carousel-item>
              <v-carousel-item
                src="https://viagemeturismo.abril.com.br/wp-content/uploads/2016/12/lencoism16.jpeg?quality=70&strip=info&w=680&h=453&crop=1"
              ></v-carousel-item>
          </v-carousel>

          <div class="back-pacote-cinza">
            <v-row>
              <div class="col-12">
                <div class="d-flex align-center justify-space-between">
                  <span class="pacote-data-principal">
                    <span class="pacote-data-prox">Próxima Data:</span><br>
                    2 maio
                  </span>
                  <v-btn
                 
                    outlined
                    fab
                    color="teal"
                    
                  >
                    <v-icon>mdi-playlist-plus</v-icon>
                  </v-btn>
                </div>
              </div>
            </v-row>
          </div>
          <v-card-text>
            <v-row>
              <div class="col-12">
                <p class="pacote-p pacote-title">Santo Amaro</p>
                <p class="pacote-p pacote-sub">Saindo de <span class="pacote-cidade">São Luís</span></p>
              </div>
            </v-row>
            <v-row>
              <div class="col-12">
                <ul class="pacote-list-itens" >
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    Translado ida e volta
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    Hospedagem
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    Café da manhã
                  </li>
                </ul>
              </div>
            </v-row>
            <v-row>
              
              <div class="col-6 d-flex pacote-preco" style="flex-direction: column; justify-content: center;">
                <span class="pacote-preco-item">Individual<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2.900,00</span></span>
                <span class="pacote-preco-item">Casadinha<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 900,00</span></span>
              </div>
              <div class="col-6 d-flex align-center" style="flex-direction: column; justify-content: center;">

                <v-btn
                 
                  class="btn-roteiro"
                  color="color-roteiro"
                  @click="openRoteiro('<h1>Carolina</h1>')"
                >
                  Descrição
                  <v-icon right>
                    mdi-palm-tree
                  </v-icon>
                </v-btn>
                 
                <v-btn
               
                  color="success"
                  class="btn-roteiro"
                >
                  Whatsapp
                </v-btn>
              
              </div>
            </v-row>
            
           </v-card-text>

        </v-card>
      
    </v-col>
    <!-- -->
    <!---->
    <v-col md="4">
      
        <v-card
          class="mx-auto"
          max-width="320"
        >
          <v-carousel 
          :show-arrows="false"
          hide-delimiter-background
          delimiter-icon="mdi-minus"
          height="200"
          show-arrows-on-hover
          >
              <v-carousel-item
                src="https://media-cdn.tripadvisor.com/media/photo-c/2560x500/12/83/56/22/kite-school-and-club.jpg"
              ></v-carousel-item>
              <v-carousel-item
                src="https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg"
              ></v-carousel-item>
          </v-carousel>

          <div class="back-pacote-cinza">
            <v-row>
              <div class="col-12">
                <div class="d-flex align-center justify-space-between">
                  <span class="pacote-data-principal">
                    <span class="pacote-data-prox">Próxima Data:</span><br>
                    2 maio
                  </span>
                  <v-btn
                 
                    outlined
                    fab
                    color="teal"
                    
                  >
                    <v-icon>mdi-playlist-plus</v-icon>
                  </v-btn>
                </div>
              </div>
            </v-row>
          </div>
          <v-card-text>
            <v-row>
              <div class="col-12">
                <p class="pacote-p pacote-title">Atins - Vassouras e Caburé MA</p>
                <p class="pacote-p pacote-sub">Saindo de <span class="pacote-cidade">São Luís</span></p>
              </div>
            </v-row>
            <v-row>
              <div class="col-12">
                <ul class="pacote-list-itens" >
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                </ul>
              </div>
            </v-row>
            <v-row>
              
              <div class="col-6 d-flex pacote-preco" style="flex-direction: column; justify-content: center;">
                <span class="pacote-preco-item">Quarto Triplo<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
                <span class="pacote-preco-item">Quarto Casal<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
              </div>
              <div class="col-6 d-flex align-center" style="flex-direction: column; justify-content: center;">

                <v-btn
                 
                  class="btn-roteiro"
                  color="color-roteiro"
                  @click="openRoteiro('<h1>Carolina</h1>')"
                >
                  Descrição
                  <v-icon right>
                    mdi-palm-tree
                  </v-icon>
                </v-btn>

                <v-btn
               
                  color="success"
                  class="btn-roteiro"
                >
                  Whatsapp
                </v-btn>
              
              </div>
            </v-row>            
           </v-card-text>

        </v-card>
      
    </v-col>
    <!-- -->
    <!---->
    <v-col md="4">
      
        <v-card
          class="mx-auto"
          max-width="320"
        >
          <v-img
            height="200"
            src="https://i.pinimg.com/originals/d9/f1/5e/d9f15e78f0ac37de87d9b95b545ed03d.jpg"
          >
          </v-img>
          <div class="back-pacote-cinza">
            <v-row>
              <div class="col-12">
                <div class="d-flex align-center justify-space-between">
                  <span class="pacote-data-principal">
                    <span class="pacote-data-prox">Próxima Data:</span><br>
                    2 maio
                  </span>
                  <v-btn
                 
                    outlined
                    fab
                    color="teal"
                    
                  >
                    <v-icon>mdi-playlist-plus</v-icon>
                  </v-btn>
                </div>
              </div>
            </v-row>
          </div>
          <v-card-text>
            <v-row>
              <div class="col-12">
                <p class="pacote-p pacote-title">Atins - Vassouras e Caburé Maranhão - Interior</p>
                <p class="pacote-p pacote-sub">Saindo de <span class="pacote-cidade">São Luís</span></p>
              </div>
            </v-row>
            <v-row>
              <div class="col-12">
                <ul class="pacote-list-itens" >
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                </ul>
              </div>
            </v-row>
            <v-row>
              
            </v-row>
            <v-row>
              
              <div class="col-6 d-flex pacote-preco" style="flex-direction: column; justify-content: center;">
                <span class="pacote-preco-item">Individual<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
                <span class="pacote-preco-item">Casadinha<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
                <span class="pacote-preco-item">Casadinha<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
              </div>
              <div class="col-6 d-flex align-center" style="flex-direction: column; justify-content: center;">

                <v-btn
                 
                  class="btn-roteiro"
                  color="color-roteiro"
                  @click="openRoteiro('<h1>Carolina</h1>')"
                >
                  Descrição
                  <v-icon right>
                    mdi-palm-tree
                  </v-icon>
                </v-btn>

                <v-btn
               
                  color="success"
                  class="btn-roteiro"
                >
                  Whatsapp
                </v-btn>
              
              </div>
            </v-row>
            
           </v-card-text>

        </v-card>
      
    </v-col>
    <!-- -->
    <!---->
    <v-col md="4">
      
        <v-card
          class="mx-auto"
          max-width="320"
        >
          <v-img
            height="200"
            src="https://i.pinimg.com/originals/d9/f1/5e/d9f15e78f0ac37de87d9b95b545ed03d.jpg"
          >
          </v-img>
          <div class="back-pacote-cinza">
            <v-row>
              <div class="col-12">
                <div class="d-flex align-center justify-space-between">
                  <span class="pacote-data-principal">
                    <span class="pacote-data-prox">Próxima Data:</span><br>
                    2 maio
                  </span>
                  <v-btn
                 
                    outlined
                    fab
                    color="teal"
                    
                  >
                    <v-icon>mdi-playlist-plus</v-icon>
                  </v-btn>
                </div>
              </div>
            </v-row>
          </div>
          <v-card-text>
            <v-row>
              <div class="col-12">
                <p class="pacote-p pacote-title">Santo Amaro</p>
                <p class="pacote-p pacote-sub">Saindo de <span class="pacote-cidade">São Luís</span></p>
              </div>
            </v-row>
            <v-row>
              <div class="col-12">
                <ul class="pacote-list-itens" >
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                </ul>
              </div>
            </v-row>
            <v-row>
              
            </v-row>
            <v-row>
              
              <div class="col-6 d-flex pacote-preco" style="flex-direction: column; justify-content: center;">
                <span class="pacote-preco-item">Individual<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
              </div>
              <div class="col-6 d-flex align-center" style="flex-direction: column; justify-content: center;">

                <v-btn
                 
                  class="btn-roteiro"
                  color="color-roteiro"
                  @click="openRoteiro('<h1>Carolina</h1>')"
                >
                  Descrição
                  <v-icon right>
                    mdi-palm-tree
                  </v-icon>
                </v-btn>

                <v-btn
               
                  color="success"
                  class="btn-roteiro"
                >
                  Whatsapp
                </v-btn>
              
              </div>
            </v-row>
            
           </v-card-text>

        </v-card>
      
    </v-col>
    <!-- -->
    <!---->
    <v-col md="4">
      
        <v-card
          class="mx-auto"
          max-width="320"
        >
          <v-img
            height="200"
            src="https://i.pinimg.com/originals/d9/f1/5e/d9f15e78f0ac37de87d9b95b545ed03d.jpg"
          >
          </v-img>
          <div class="back-pacote-cinza">
            <v-row>
              <div class="col-12">
                <div class="d-flex align-center justify-space-between">
                  <span class="pacote-data-principal">
                    <span class="pacote-data-prox">Próxima Data:</span><br>
                    2 maio
                  </span>
                  <v-btn
                 
                    outlined
                    fab
                    color="teal"
                    
                  >
                    <v-icon>mdi-playlist-plus</v-icon>
                  </v-btn>
                </div>
              </div>
            </v-row>
          </div>
          <v-card-text>
            <v-row>
              <div class="col-12">
                <p class="pacote-p pacote-title">Santo Amaro</p>
                <p class="pacote-p pacote-sub">Saindo de <span class="pacote-cidade">São Luís</span></p>
              </div>
            </v-row>
            <v-row>
              <div class="col-12">
                <ul class="pacote-list-itens" >
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                </ul>
              </div>
            </v-row>
            <v-row>
              
            </v-row>
            <v-row>
              
              <div class="col-6 d-flex pacote-preco" style="flex-direction: column; justify-content: center;">
                <span class="pacote-preco-item">Individual<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
                <span class="pacote-preco-item">Casadinha<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
              </div>
              <div class="col-6 d-flex align-center" style="flex-direction: column; justify-content: center;">

                <v-btn
                 
                  class="btn-roteiro"
                  color="color-roteiro"
                  @click="openRoteiro('<h1>Carolina</h1>')"
                >
                  Descrição
                  <v-icon right>
                    mdi-palm-tree
                  </v-icon>
                </v-btn>

                <v-btn
               
                  color="success"
                  class="btn-roteiro"
                >
                  Whatsapp
                </v-btn>
              
              </div>
            </v-row>
            
           </v-card-text>

        </v-card>
      
    </v-col>
    <!-- -->
    <!---->
    <v-col md="4">
      
        <v-card
          class="mx-auto"
          max-width="320"
        >
          <v-img
            height="200"
            src="https://i.pinimg.com/originals/d9/f1/5e/d9f15e78f0ac37de87d9b95b545ed03d.jpg"
          >
          </v-img>
          <div class="back-pacote-cinza">
            <v-row>
              <div class="col-12">
                <div class="d-flex align-center justify-space-between">
                  <span class="pacote-data-principal">
                    <span class="pacote-data-prox">Próxima Data:</span><br>
                    2 maio
                  </span>
                  <v-btn
                 
                    outlined
                    fab
                    color="teal"
                    
                  >
                    <v-icon>mdi-playlist-plus</v-icon>
                  </v-btn>
                </div>
              </div>
            </v-row>
          </div>
          <v-card-text>
            <v-row>
              <div class="col-12">
                <p class="pacote-p pacote-title">Santo Amaro</p>
                <p class="pacote-p pacote-sub">Saindo de <span class="pacote-cidade">São Luís</span></p>
              </div>
            </v-row>
            <v-row>
              <div class="col-12">
                <ul class="pacote-list-itens" >
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                  <li>
                    <span><v-icon class="icon-color">mdi-clock</v-icon></span>
                    1 Dia
                  </li>
                </ul>
              </div>
            </v-row>
            <v-row>
              
            </v-row>
            <v-row>
              
              <div class="col-6 d-flex pacote-preco" style="flex-direction: column; justify-content: center;">
                <span class="pacote-preco-item">Individual<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
                <span class="pacote-preco-item">Casadinha<br><span class="pacote-preco-tipo"><span class="pacote-preco-moeda">R$</span> 2900</span></span>
              </div>
              <div class="col-6 d-flex align-center" style="flex-direction: column; justify-content: center;">

                <v-btn
                 
                  class="btn-roteiro"
                  color="color-roteiro"
                  @click="openRoteiro('<h1>Carolina</h1>')"
                >
                  Descrição
                  <v-icon right>
                    mdi-palm-tree
                  </v-icon>
                </v-btn>

                <v-btn
               
                  color="success"
                  class="btn-roteiro"
                >
                  Whatsapp
                </v-btn>
              
              </div>
            </v-row>
            
           </v-card-text>

        </v-card>
      
    </v-col>
    <!-- -->
    

    
    <!-- modal -->
    <v-dialog
      v-model="dialog"
      fullscreen
      hide-overlay
      transition="dialog-bottom-transition"
    >
      <v-card>
        <v-toolbar
          dark
          color="color-roteiro"
        >
          <v-btn
            icon
            dark
            @click="dialog = false"
          >
            <v-icon>mdi-close</v-icon>
          </v-btn>
          <v-toolbar-title>Roteiro</v-toolbar-title>
        </v-toolbar>
        <span v-html="roteiro"></span>
              
      </v-card>
    </v-dialog>
    <!-- fim modal -->

  </v-row>
</v-container>
</template>

<script>
export default {
  components: {
  },
  data: () => ({
      dialog: false,
      roteiro: ''
    }),
    methods: {
      openRoteiro: function(rot){
        this.dialog = true
        this.roteiro = rot
      }
    }
}
</script>
<style scoped>
.pacote-data-principal{
  font-weight: 800;
  color: #139e91;
  font-size: 20px;
  line-height: 1.3;
}
.pacote-data-prox {
  font-size: 14px;
  font-weight: 500;
  color: #a9a9a9;
}
.back-pacote-cinza{
  padding: 5px 16px;
  font-weight: 700;
  box-shadow: 0 0 2px rgb(130 189 199);
  background: #f9f9f9;
}
.back-pacote-cinza .v-btn--fab.v-size--default {
    height: 48px;
    width: 48px;
}
.pacote-list-itens{
  padding: 0;
  margin: 0;
  list-style: none;
  font-weight: 500;
}
.pacote-preco-item{
  padding: 5px 0px;
  font-weight: 600;
  color: rgb(0 0 0 / 60%);
}
.pacote-p {
  margin: 0;
  padding: 0;
}
.pacote-preco {
  font-size: 15px;
}
.pacote-preco-tipo{
   color: #d88304;
   font-size: 22px;
}
.pacote-title{
  font-size: 19px;
  color: #565656;
  font-weight: 600;
  line-height: 1.2;
}
.pacote-sub{
  color: #435b71;
  font-size: 14px;
  margin-bottom: -15px;
}
.btn-roteiro{
  margin: 5px 0px;
  min-width: 142px !important;
}
span.pacote-preco-moeda {
  font-size: 16px;
}
.pacote-cidade{
  font-weight: 600;
}
.icon-color{
  color: rgb(179 176 176);
  font-size: 20px !important;
}
.pacote-data{
  color: #ffffff;
  font-weight: 500;
  cursor: pointer;
  position: absolute;
  background: #737270;
  padding: 3px 8px;
  border-radius: 6px;
  right: 9px;
}
.pacote-data:hover{
  color: #d98509;
}
.color-roteiro {
  background-color: #139e91 !important;
  border-color: #139e91 !important;
  color: #fff !important;
}
</style>
