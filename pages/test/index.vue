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
      <!-- <v-container style="height: 1000px;"></v-container> -->



      <template>
        <v-container fluid>
          <v-layout justify-space-around>
            <v-flex xs12>
              <!-- <div class="title mb-1">Contain</div> -->
              <v-layout column>
                <!-- <div class="subheading">Matching</div> -->
                <v-img src="\img\shop\IMG_2001.JPG" aspect-ratio="1.2" contain></v-img>
              </v-layout>
            </v-flex>
          </v-layout>
        </v-container>
      </template>


    </div>
  </div>
</template>
