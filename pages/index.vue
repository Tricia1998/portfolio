<template>
  <div>
    <Navbar />
    <v-spacer />
    <v-row class="mt-12"></v-row>
    <v-row class="text-h2 mt-12" align="center" justify="space-around"
      ><b> Designer & Frontend Developer </b>
    </v-row>
    <v-row class="text" align="center" justify="space-around">
      <p>
        I'm a junior web developer and a graphic designer based in Harare
        (Zimbabwe) & I create awesome and effective sites.
      </p>
    </v-row>
    <v-row class="mt-8" justify="space-around">
      <img
        src="../static/homesvg.svg"
        width="600"
        height="500"
        alt=""
        fade-img-on-scroll
    /></v-row>
    <v-row>
      <v-card height="500" width="1600" color="deep-purple accent-4" dense dark>
        <v-row class="text-h5 mt-15" align="center" justify="space-around">
        </v-row>
        <v-row class="text-h5 mt-15" align="center" justify="space-around">
        </v-row>
        <v-row class="text-h4 mt-15" align="center" justify="space-around">
          Hi, I’m Farie. Nice to meet you.
        </v-row>
        <v-row class="text mt-10" align="center" justify="space-around">
          <p>
            I have just recently begun my journey as a freelance designer as of
            May 2022, I've done remote work for agencies, consulted for
            startups,
          </p>
          <p>
            and collaborated with talented people to create dial products for
            both business and consumer use. I'm quietly confident,
          </p>
          <p>
            naturally curious, and perpetually working on improving my skills
            with one design problem at a time.
          </p>
        </v-row>
        <v-row>
          <v-spacer />
          <div class="div" ref="div1">
            <v-card md="12" width="1350" class="mt-15" color="white" flat>
              <v-row align="center" justify="space-around" class="mb-12">
                <v-col md="6" sm="12" flat>
                  <v-card
                    class="white black--text ma-15"
                    flat
                    align="center"
                    justify="space-around"
                  >
                    <img
                      class="mr-3"
                      :src="require('../static/image.png')"
                      width="123"
                      height="120"
                      aspect-ratio="2"
                    />
                    <h2>Frontend Developer</h2>
                    <p>
                      I like to code things from scratch, and enjoy bringing
                    </p>
                    <p>ideas to life in the browser.</p>
                    <p class="white purple--text mt-15">Languages I speak:</p>
                    <p>HTML, CSS,</p>
                    <p class="white purple--text mt-15">Development Tools:</p>
                    <p>Bootstrap</p>
                    <p>Vuetify</p>
                    <p>Vuejs</p>
                    <p>hub</p>
                    <p>Wordpress</p>
                    <p>Visual Studio</p>
                  </v-card>
                </v-col>
                <v-spacer />
                <v-col md="6" sm="12" flat>
                  <v-card
                    class="white black--text ma-8"
                    flat
                    align="center"
                    justify="space-around"
                  >
                    <img
                      class="mr-3"
                      :src="require('../static/image 2.png')"
                      width="123"
                      height="120"
                      aspect-ratio="2"
                    />
                    <h2>Graphic Designer</h2>
                    <p>
                      I value simple content structure, clean design patterns,
                    </p>
                    <p>and thoughtful interactions.</p>
                    <p class="white purple--text mt-15">
                      Things I enjoy designing:
                    </p>
                    <p>Fliers, Business Cards, Logos & Web</p>
                    <p class="white purple--text mt-15">Design Tools:</p>
                    <p>Adobe Lightroom</p>
                    <p>Adobe Photoshop</p>
                    <p>Figma</p>
                  </v-card>
                </v-col>
                <v-btn large a href="./resume.pdf" target="_blank">
                  View My Full cv
                  <v-icon dark right> mdi-arrow-right-bold-outline </v-icon>
                </v-btn>
              </v-row>

              <v-divider color="purple" inset></v-divider>
            </v-card>
            <v-card
              md="12"
              width="1350"
              class="mt-15 black--text"
              color="white"
              flat
            >
              <p class="text-h3 ma-6" align="center" justify="space-around">
                Portfolio
              </p>
              <p class="mt-8" align="center" justify="space-around">
                Here are a few past design projects I've worked on. Want to see
                more?
              </p>
              <p align="center" justify="space-around">
                View Our App Catalogue
                <v-btn
                  a
                  href="https://wa.me/c/263783108500"
                  color="deep-purple accent-4"
                  class="white--text"
                >
                  View
                </v-btn>
              </p>
            </v-card>
          </div>
          <v-spacer />
        </v-row>

        <v-row>
          <v-col md="4" sm="12">
            <v-hover v-slot="{ hover }" open-delay="200">
              <v-card
                :elevation="hover ? 16 : 2"
                :class="{ 'on-hover': hover }"
                class="ma-10 white black--text"
              >
                <img
                  alt="Vue logo"
                  src="../static/anixsys.png"
                  width="360"
                  height="230"
                />

                <v-expand-transition>
                  <div
                    v-if="hover"
                    class="d-flex transition-fast-in-fast-out deep-purple accent-4 v-card--reveal text-h6 white--text"
                    style="height: 100%"
                  >
                    <div class="align-self-center">
                      <v-btn text a href="https://anixsys.co.zw/">
                        <v-card-text class="pt-6" style="position: relative">
                          <div class="white--text text-h6 mb-2">
                            Anixsys System
                          </div>
                          <h3 class="text-h4 white--text mb-2">
                           
                          </h3>
                          <div class="text-h6 mb-2">
                            For all software development<br />
                            and graphic design projects
                          </div>
                        </v-card-text>
                      </v-btn>
                    </div>
                  </div>
                </v-expand-transition>
              </v-card>
            </v-hover>
          </v-col>
          <v-col md="4" sm="12">
            <v-hover v-slot="{ hover }" open-delay="200">
              <v-card
                :elevation="hover ? 16 : 2"
                :class="{ 'on-hover': hover }"
                class="ma-10 white black--text"
              >
                <img
                  alt="Vue logo"
                  src="../static/login.png"
                  width="360"
                  height="230"
                />

                <v-expand-transition>
                  <div
                    v-if="hover"
                    class="d-flex transition-fast-in-fast-out deep-purple accent-4 v-card--reveal text-h6 white--text"
                    style="height: 100%"
                  >
                    <div class="align-self-center">
                      <v-btn text a href="https://portal.praz.org.zw/" >
                        <v-card-text class="pt-6" style="position: relative">
                          <div class="white--text text-h6 mb-2">
                            PRAZ Website
                          </div>
                         
                          <div class="text-h6 mb-2">
                            For All online Registration and<br />
                            Tender Application
                          </div>
                        </v-card-text>
                      </v-btn>
                    </div>
                  </div>
                </v-expand-transition>
              </v-card>
            </v-hover>
          </v-col>
          <v-col md="4" sm="12">
            <v-hover v-slot="{ hover }" open-delay="200">
              <v-card
                :elevation="hover ? 16 : 2"
                :class="{ 'on-hover': hover }"
                class="ma-10 white black--text"
              >
                <img
                  alt="Vue logo"
                  src="../static/home.png"
                  width="360"
                  height="230"
                />

                <v-expand-transition>
                  <div
                    v-if="hover"
                    class="d-flex transition-fast-in-fast-out deep-purple accent-4 v-card--reveal text-h6 white--text"
                    style="height: 100%"
                  >
                    <div class="align-self-center">
                      <v-btn text>
                        <v-card-text class="pt-6" style="position: relative">
                          <div class="white--text text-h6 mb-2">
                            For the perfect meal
                          </div>
                          <h3 class="text-h4 white--text mb-2">
                            QW cooking utensils
                          </h3>
                          <div class="text-h6 mb-2">
                            Our Vintage kitchen utensils delight any chef.<br />
                            Made of bamboo by hand
                          </div>
                        </v-card-text>
                      </v-btn>
                    </div>
                  </div>
                </v-expand-transition>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
        <v-row>
          <v-col md="4" sm="12">
            <v-card class="ma-10 white black--text">
              <img
                alt="Vue logo"
                src="../static/flier.png"
                width="360"
                height="400"
              />
            </v-card>
          </v-col>
          <v-col md="4" sm="12">
            <v-card class="ma-10 white black--text">
              <img
                alt="Vue logo"
                src="../static/flier.png"
                width="360"
                height="400"
              />
            </v-card>
          </v-col>
          <v-col md="4" sm="12">
            <v-card class="ma-10 white black--text">
              <img
                alt="Vue logo"
                src="../static/flier.png"
                width="360"
                height="400"
              />
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col sm="6">
            <img
              src="../static/contact.svg"
              width="600"
              height="500"
              alt=""
              fade-img-on-scroll
          /></v-col>
          <v-col sm="6 deep-purple accent-4" dense dark>
            <v-card
              align="center"
              color="deep-purple accent-4"
              dense
              dark
              width="400"
              outlined
              class="mx-auto ma-12"
            >
              <v-form class="ma-8" ref="form" v-model="valid" lazy-validation action="https://formsubmit.co/faraisepete@gmail.com">
                <h2 class="ma=12">Contact Us</h2>
                <v-text-field
                  v-model="name"
                  :counter="10"
                  :rules="nameRules"
                  label="Name"
                  required
                ></v-text-field>

                <v-text-field
                  v-model="email"
                  :rules="emailRules"
                  label="E-mail"
                  required
                ></v-text-field>

                <v-text-field
                  v-model="phonenumber"
                  :counter="10"
                  :rules="phonenumberRules"
                  label="Phone Number"
                  required
                ></v-text-field>

                <v-btn
                  :disabled="!valid"
                  color="white"
                  class="mr-4 purple--text"
                  a href="https://formsubmit.co/el/faraisepete@gmail.com" target="_blank">
                >
                  Email Me
                </v-btn>

                <v-btn
                  color="deep-purple accent-4"
                  class="mr-4"
                  @click="Cancel"
                >
                  Cancel
                </v-btn>
              </v-form>
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-card
            md="12"
            width="1350"
            class="mt-15 black--text"
            color="white"
            flat
          >
            <p class="text-h3 ma-6" align="center" justify="space-around">
              Testimonial
            </p>
            <p align="center" justify="space-around" class="text-xl-center">
              People I've worked with have said some nice things...
            </p>
          </v-card>
        </v-row>

        <v-card max-width="444" class="mx-auto" flat color="white">
          <v-carousel
            :continuous="true"
            :cycle="cycle"
            :show-arrows="false"
            cycle="purple--text"
            hide-delimiter-background
            delimiter-icon="mdi-minus purple--text"
            height="400"
            align="center"
            justify="space-around"
            color="white"
          >
            <v-carousel-item color="white">
              <v-list color="white" class="black--text">
                <v-list-item color="white">
                  <v-list-item-content class="white black--text">
                    <v-avatar size="125" class="ma-6">
                      <img :src="require('../static/my pic.jpg')" />
                    </v-avatar>
                    <v-list-item-title><b>Farai Sepete </b></v-list-item-title>
                    <v-list-item-subtitle class="black--text"
                      >Author</v-list-item-subtitle
                    >
                  </v-list-item-content>
                </v-list-item>
              </v-list>

              <p class="white black--text">
                “Farie was a real pleasure to work with and we look forward to
              </p>
              <p class="white black--text">
                working with him again. He’s definitely the kind of designer
              </p>
              <p class="white black--text">
                you can trust with a project from start to finish.”
              </p>
            </v-carousel-item>
            <v-carousel-item color="white">
              <v-list color="white" class="black--text">
                <v-list-item color="white">
                  <v-list-item-content class="white black--text">
                    <v-avatar size="125" class="ma-6">
                      <img :src="require('../static/my pic.jpg')" />
                    </v-avatar>
                    <v-list-item-title><b>Farai Sepete </b></v-list-item-title>
                    <v-list-item-subtitle class="black--text"
                      >Author</v-list-item-subtitle
                    >
                  </v-list-item-content>
                </v-list-item>
              </v-list>

              <p class="white black--text">
                “Farie was a real pleasure to work with and we look forward to
              </p>
              <p class="white black--text">
                working with him again. He’s definitely the kind of designer
              </p>
              <p class="white black--text">
                you can trust with a project from start to finish.”
              </p>
            </v-carousel-item>
          </v-carousel>
        </v-card>
        <v-card>
          <v-footer dark padless flat>
            <v-card
              flat
              tile
              class="white--text text-center"
              color="deep-purple accent-4"
              dense
              dark
              width="100%"
            >
              <v-spacer></v-spacer>

              <v-card-text> </v-card-text>

              <v-row>
                <v-row
                  class="mt-5"
                  align="center"
                  md="6"
                  sm="12"
                  justify="space-around"
                >
                  <img
                    class="mr-3"
                    :src="require('../static/logo.png')"
                    height="40"
                  />
                </v-row>
              </v-row>
              <v-spacer></v-spacer>

              <v-divider class="mt-8"></v-divider>

              <v-card-text class="white--text mt-3">
                {{ new Date().getFullYear() }} —
                <strong>Farai Patricia Sepete</strong>
                <v-spacer></v-spacer>

                <v-btn
                  icon
                  a
                  href="https://www.facebook.com/profile.php?id=100011356793995"
                >
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
              </v-card-text>
            </v-card>
          </v-footer>
        </v-card>
      </v-card>
    </v-row>
    <v-spacer />
  </div>
</template>
<script>
export default {
  data: () => ({
    cycle: false,

    transparent: "rgba(255, 255, 255, 0)",
    valid: true,
    name: "",
    nameRules: [
      (v) => !!v || "Name is required",
      (v) => (v && v.length <= 10) || "Name must be less than 10 characters",
    ],
    email: "",
    emailRules: [
      (v) => !!v || "E-mail is required",
      (v) => /.+@.+\..+/.test(v) || "E-mail must be valid",
    ],
    phonenumberRules: [
      (v) => !!v || "Phone Number is required",
      (v) =>
        (v && v.length <= 10) || "Phone Number must be less than 10 characters",
    ],
    select: null,
  }),

  methods: {
    Send() {
      this.$refs.form.validate();
    },
    Cancel() {
      this.$refs.form.reset();
    },
  },
};
</script>
