<template>
  <div id="homepage">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item src="./../../dude with backpackpexels-linkedin-sales-navigator-1251861.jpg" cover></v-carousel-item>

          <v-carousel-item
            src="./../../pexels-helena-lopes-697244.jpg"
            cover
          ></v-carousel-item>

          <v-carousel-item
            src="./../../pexels-zen-chung-5537998.jpg"
            cover
          ></v-carousel-item>
        </v-carousel>
      </v-layout>
      <v-layout>
        <v-container>
          <v-row align="center" justify="center">
            <div class="d-flex align-center flex-column">
              <div class="text-subtitle-2">Student Life</div>

              <v-card
                width="400"
                title="Student Life"
                subtitle="Get the Most of Your Strathmore Experience "
                text="
                              At Strathmore, we believe that student life is an essential component of the college experience. We strive to create a vibrant and inclusive community where students can learn, grow, and thrive both inside and outside the classroom. Our diverse range of extracurricular activities, support services, and campus amenities are designed to enhance your university journey and help you make the most of your time here.
                              
                              Student Life at Stratmore is as rich as the as the student community is diverse. From sports and the arts to clubs and societies, every student can find a place to connect."
              ></v-card>

              <div class="mt-4 text-subtitle-2">Student Life</div>

              <v-card width="400">
                <template v-slot:title> Co-curricular Acvtivites </template>

                <template v-slot:subtitle>
                  Student Activities to Activate Your Campus Life
                </template>

                <template v-slot:text>
                  Get involved and make lasting connections through our diverse
                  array of student organizations, clubs, and societies. Whether
                  you're passionate about arts and culture, sports and
                  recreation, social justice and activism, or professional
                  development, there's a group for you. Participate in campus
                  events, volunteer opportunities, and leadership programs to
                  expand your horizons, develop new skills, and create memories
                  that will last a lifetime.
                </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">Student Life</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Accomodation </v-card-title>

                  <v-card-subtitle
                    >Community & Residential Spaces</v-card-subtitle
                  >
                </v-card-item>

                <v-card-text>
                  Housing and Residence Life Experience the convenience and
                  camaraderie of our recommended residential options. Whether
                  you prefer traditional dormitories, apartment-style living, or
                  themed communities, you'll find a comfortable and supportive
                  environment where you can live, learn, and grow alongside your
                  peers. Our residence life staff are dedicated to creating
                  inclusive communities that foster personal growth, academic
                  success, and a sense of belonging.
                </v-card-text>
              </v-card>
            </div>
          </v-row>
        </v-container>
      </v-layout>
    </v-container>
  </div>
</template>
<script setup>
const variants = ["elevated", "flat", "tonal", "outlined"];
</script>
