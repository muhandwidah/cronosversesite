<template>
 <v-app>
   <div id="navcontainer">
      <navbar id="navbar" />
    </div>
    <div id="bodycontainer">
      <v-row justify="center">
    <h1 id="projecth1">Our Team</h1>
    </v-row>
    <v-divider id="divider"></v-divider>
      <div id="teamcontainer">
        <v-row justify="center">
        <v-card class="mx-auto" max-width="330">
          <v-img src="https://i.ibb.co/BsdNbv0/Tommy.png" height="400px"></v-img>
      </v-card>
      <v-card class="mx-auto" max-width="330">
          <v-img src="https://i.ibb.co/gT2DmFq/Steve.png" height="400px"></v-img>
      </v-card>  
      <v-card class="mx-auto" max-width="330">
          <v-img src="https://i.ibb.co/9WT2QsC/Ryan.png" height="400px"></v-img>
      </v-card>  
      <v-card class="mx-auto" max-width="330">
          <v-img src="https://i.ibb.co/qjQMjnd/Manny.png" height="400px"></v-img>
      </v-card>  
      <v-card class="mx-auto" max-width="330">
          <v-img src="https://i.ibb.co/sRXvjmg/Muhand.png" height="400px"></v-img>
      </v-card>  
      </v-row>
    </div>
    </div>
    </v-app>
</template>

<script>
import navbar from "@/components/navbar.vue";
export default {
    name: 'Token',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {},
    components: {
    navbar,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Russo+One&display=swap");
#projecth1 {
  margin-top: 50px;
  margin-bottom: 50px;
}
#divider {
  margin-top: 30px;
  margin-bottom: 30px;
}
h1 {
  color: black;
  font-family: "Russo One", sans-serif;
  font-size: 50px;
}
#navbar {
  background-color: black;
}
</style>