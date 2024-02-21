<template>
  <div id="events">
    <v-container>
      <v-layout column>
        <h1>Strathmore University Events</h1>
      </v-layout>
    </v-container>
  </div>




  <div id="events">
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
              <div class="text-subtitle-2">Events at Strathmore</div>

              <v-card
                width="400"
                title="Campus Culture and Events"
                subtitle="Rich Campus Culture "
                text=
                "Immerse yourself in our rich campus culture, where diversity, creativity, and innovation thrive. From cultural celebrations and guest lectures to concerts and theatrical performances, there's always something exciting happening at [University Name]. Our dedicated student organizations and clubs cater to a wide range of interests, providing countless opportunities to connect with like-minded peers and make lasting memories."

                              
              ></v-card>

              <div class="mt-4 text-subtitle-2">Events</div>

              <v-card width="400">
                <template v-slot:title> Events at Strathmore </template>

                <template v-slot:subtitle>
                  Exciting Events All Through the 
                  Year
                </template>

                <template v-slot:text>
                  Stay tuned for exciting events happening at our university! We offer a vibrant calendar filled with diverse activities, seminars, workshops, and cultural events designed to enrich your university experience. Whether you're interested in academic lectures, student-led initiatives, career fairs, artistic performances, or community outreach programs, there's something for everyone to engage in and enjoy.
                </template>
              </v-card>

              <div class="mt-4 text-subtitle-2">Events</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Events and Culture </v-card-title>

                  <v-card-subtitle
                    >Events and Culture</v-card-subtitle
                  >
                </v-card-item>

                <v-card-text>
                  Be sure to check back regularly for updates and announcements about upcoming events. We encourage you to get involved, connect with peers, and make the most of your time at our university by participating in the diverse array of activities we have to offer. Join us as we create memorable experiences and foster a sense of belonging and growth for all members of our community.
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

