<script>
import Homepage from "./../components/Homepage.vue";
import Events from "./../components/Events.vue";
import Courses from "./../components/Courses.vue";
import AboutUs from "./../components/AboutUs.vue";
import Alumni from "./../components/Alumni.vue";
import ContactUs from "./../components/ContactUs.vue";
import Partnerships from "./../components/Partnerships.vue";
</script>

<template>
    <v-app-bar color="teal">
        <div>
            <v-btn to="/" colour="white" dark>Home</v-btn>
        </div>
        <div>
            <v-btn to="/events" colour="white" dark>Events</v-btn>
        </div>
        <div>
            <v-btn to="/courses" colour="white" dark>Courses</v-btn>
        </div>
        <div>
            <v-btn to="/contacts" colour="white" dark>ContactUs</v-btn>
        </div>
        <div>
            <v-btn to="/about" colour="white" dark>AboutUs</v-btn>
        </div>
        <div>
            <v-btn to="/partnerships" colour="white" dark>Partnerships</v-btn>
        </div>
        <div>
            <v-btn to="/alumni" colour="white" dark>Alumni</v-btn>
        </div>
    </v-app-bar>
</template>