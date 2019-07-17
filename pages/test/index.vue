<template>
  <div


    class="hide-overflow"
    style="position: relative;"
  >



    <v-toolbar
      absolute
      color="teal lighten-3"
      dark
      scroll-off-screen
      scroll-target="#scrolling-techniques"
    >
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>Title</v-toolbar-title>
      <v-spacer></v-spacer>

      <v-btn flat>Link One</v-btn>
      <v-btn flat>Link Two</v-btn>
      <v-btn flat>Link Three</v-btn>

    </v-toolbar>


    <div
      id="scrolling-techniques"
      class="scroll-y"
      style="max-height: 600px;"
    >


  <v-layout row wrap class="pa-0 ma-0">
        <v-img src="https://salon-de-luxage.netlify.com/img/shop/IMG_2001.JPG"/>
  </v-layout>



  <v-container fluid>
    <v-layout justify-space-around>
      <v-flex xs5>
        <v-layout column>
          <v-img src="\img\logo\logo_tentoshiyou1.png" aspect-ratio="1.7" contain></v-img>
        </v-layout>
      </v-flex>
    </v-layout>
  </v-container>




  <v-layout row wrap class=" ">
    <v-flex
      shrink
      pa-1
    >
      <h2 class="display-2 font-weight-medium primary--text">GALLERY</h2>
    </v-flex>
    <v-flex
      grow
      pa-1
      px-2
    ><v-card-text><h3 class="subheading" >by your side,by your self</h3></v-card-text>
    </v-flex>
  </v-layout>


  <div class="" >
    <v-divider color="#FFCDD2"></v-divider>

    <!-- <v-card-text class="my-3">
      NADESICOの会社情報です。会社概要、トップメッセージ、企業沿革などの情報を掲載しています。
    </v-card-text> -->

  </div>


  <template>
  <v-layout>
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-container grid-list-sm fluid>
          <v-layout row wrap>
            <v-flex
              v-for="n in 9"
              :key="n"
              xs4
              d-flex
            >
              <v-card flat tile class="d-flex">
                <v-img
                  :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
                  :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                  aspect-ratio="1"
                  class="grey lighten-2"
                >
                  <template v-slot:placeholder>
                    <v-layout
                      fill-height
                      align-center
                      justify-center
                      ma-0
                    >
                      <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                    </v-layout>
                  </template>
                </v-img>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-card>
    </v-flex>
  </v-layout>
</template>




<template>
  <div>
      <v-flex xs12 sm8 offset-sm2>
    <v-btn color="info">Short</v-btn>
    <v-btn color="info">Medium</v-btn>
    <v-btn color="info">Long</v-btn>
    <v-btn color="info">Mens</v-btn>
    </v-flex>
  </div>
</template>



<v-layout row wrap class=" ">
  <v-flex
    shrink
    pa-1
  >
    <h2 class="display-2 font-weight-medium primary--text">PRICE</h2>
  </v-flex>
  <v-flex
    grow
    pa-1
    px-2
  ><v-card-text><h3 class="subheading" >Smile is free</h3></v-card-text>
  </v-flex>
</v-layout>
<div class="" >
  <v-divider color="#FFCDD2"></v-divider>
</div>




<template>
  <v-expansion-panel>
    <v-expansion-panel-content
      v-for="(item,i) in 5"
      :key="i"
    >
      <template v-slot:header>
        <div>Item</div>
      </template>
      <v-card>
        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</v-card-text>
      </v-card>
    </v-expansion-panel-content>
  </v-expansion-panel>
</template>




    </div>
  </div>
</template>
