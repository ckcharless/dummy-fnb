<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="../assets/1.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <!-- <h5 class="red--text text--darken-4 top">Hello Im Agetha</h5> -->
          <h1 class="black--text top">Warung Kopi Asoy</h1>
          <p class="grey--text">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. <br />
            Adipisci explicabo, cupiditate necessitatibus iure hic omnis est ab
            <br />
            At nihil et temporibus ratione!
          </p>
          <v-btn tile color="#A7121D" dark> about us </v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="about">
            <h1 class="white--text">Tentang Kami</h1>
            <v-row style="margin-top: 10px;">
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-palette-swatch</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Warung Kami</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                    elit.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark
                    >mdi-book-open-page-variant</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Menu</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                    elit.
                  </p>
                  <v-btn color="" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-map</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Location</h3>
                  <p class="grey--text ml-3 mt-6">
                    Lorem, ipsum dolor sit amet <br />consectetur adipisicing
                    elit.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="red--text text--darken-4 mt-4 number">12</h1>
                  <h3 class="white--text mt-4">Years Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">60+</h1>
                        <p class="grey--text">Menu</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">5</h1>
                        <p class="grey--text">Branch</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">08</h1>
                        <p class="grey--text">franchise</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">10</h1>
                        <p class="grey--text">Achievements</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="menu">
          <h4 class="black--text">MENU</h4>
          <p class="grey--text">Lorem ipsum dolor Lorem ipsum dolor</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#A7121D" dark> View All </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="3.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="2.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="black" dark text class="ml-n4"> Cappuccino </v-btn
          ><br />
        </v-col>
        <v-col md="3">
          <v-btn color="black" dark text class="ml-n4"> Latte </v-btn><br />
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="4.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="5.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="black" dark text class="ml-n4"> Americano </v-btn
          ><br />
        </v-col>
        <v-col md="3">
          <v-btn color="black" dark text class="ml-n4"> Affogato </v-btn><br />
        </v-col>
        <v-col cols="12" class="padd">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">
                    Contact Us
                  </h1>
                  <p class="grey--text">
                    <v-icon color="#A7121D" x-large class="ml-3">mdi-phone-in-talk</v-icon> (+62)8234353xxx
                    <br>
                    <v-icon color="#A7121D" x-large class="ml-3">mdi-near-me</v-icon> Together Street 158
                    <br>
                    <v-icon color="#A7121D" x-large class="ml-3">mdi-mail</v-icon> asoy.kopi@email.com
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-img src="../assets/map.png" contain max-height="210"></v-img>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Home</v-btn>
              <v-btn text>About</v-btn>
              <v-btn text>Menu</v-btn>
              <v-btn text>Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/FooterView.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  /* margin-top: 10px; */
  text-align: center;
}
.first {
  width: 100%;
  height: 700px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 1rem 2rem;
}
.secondchild1 {
  width: 50%;
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 50px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #ce1d2a;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>