<template>
  <div id="Alumni">
    <v-container>
      <v-layout column>
        <h1>Strthmore Alumni</h1>
      </v-layout>
    </v-container>
  </div>


Alumni Spotlight

  <div id="Alumni">
    <v-container>
      <v-layout column>
        <v-carousel>
          <v-carousel-item src="./../../public/graduates pexels-emily-ranquist-1205651.jpg" cover></v-carousel-item>

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
                title="Alumni"
                subtitle="Agents of Transformation "
                text=
                "Welcome to the Alumni Spotlight section, where we celebrate the achievements and successes of our esteemed graduates from around the globe. Our alumni community is a testament to the transformative power of education and the enduring impact of our university."

                              
              ></v-card>

              <div class="mt-4 text-subtitle-2">Alumni</div>

              <v-card width="400">
                <template v-slot:title> Strathmore Alumni </template>

                <template v-slot:subtitle>
                  Featured Alumni:
                </template>

                <template v-slot:text>
                  Alumni Spotlight

Welcome to the Alumni Spotlight section, where we celebrate the achievements and successes of our esteemed graduates from around the globe. Our alumni community is a testament to the transformative power of education and the enduring impact of our university.

Dr. Sophia Rodriguez

Degree: Ph.D. in Biomedical Engineering, Class of 2010
Current Position: Chief Scientific Officer at a leading biotech firm
Achievements: Dr. Rodriguez has pioneered groundbreaking research in regenerative medicine, leading to the development of innovative therapies for chronic diseases. Her work has earned her numerous accolades and recognition in the scientific community.
Johnathan Chen

Degree: Bachelor of Business Administration, Class of 2005
Current Position: CEO of a successful tech startup
Achievements: Mr. Chen's entrepreneurial spirit and strategic vision have propelled his company to the forefront of the industry. Under his leadership, the company has experienced exponential growth and garnered attention for its innovative products and services.
Alumni Success Stories:

Sarah Nguyen

Degree: Master of Fine Arts in Creative Writing, Class of 2017
Current Endeavors: Published author and advocate for underrepresented voices in literature
Impact: Through her poignant storytelling, Sarah has shed light on important social issues and inspired readers worldwide. She is a vocal advocate for diversity and inclusion in the literary world, using her platform to amplify marginalized voices.
David Patel

Degree: Bachelor of Science in Computer Science, Class of 2012
Current Endeavors: Co-founder of a tech nonprofit dedicated to providing access to coding education for underserved communities
Impact: David's commitment to bridging the digital divide has empowered countless individuals to pursue careers in technology. His nonprofit has provided essential resources and mentorship to aspiring programmers, fostering a more equitable and inclusive tech industry.
                 </template>
               </v-card>

              <div class="mt-4 text-subtitle-2">Alumni</div>

              <v-card width="400">
                <v-card-item>
                  <v-card-title>Alumni </v-card-title>

                  <v-card-subtitle> Alumni Networks </v-card-subtitle
                  >
                </v-card-item>

                <v-card-text>
                
Our alumni are integral partners in advancing the mission of Strathmore. Through their expertise, networks, and philanthropic support, alumni contribute to the success of current students, foster mentorship opportunities, and strengthen the reputation and impact of our university worldwide.

At Strathmore, we are committed to cultivating and nurturing meaningful partnerships that drive positive change and create enduring value for our students, faculty, and communities. Together, we are shaping the future of education, research, and innovation.
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

