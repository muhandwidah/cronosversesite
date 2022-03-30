<template>
  <v-app>
    <div>
      <navbar id="navbar" />
    </div>
    <h1 id="projecth1">CRONOSVERSE FAQ</h1>
    <div id="expansioncontainer">
      <v-row justify="center">
        <v-expansion-panels dark inset>
          <v-expansion-panel>
            <v-expansion-panel-header
              >How Many Land Tiles Will Be Available?</v-expansion-panel-header
            >
            <v-expansion-panel-content>
              <p>
                There are a total of 1208 Land Tiles for Sale in the following
                quantities:
              </p>
              <ul>
                <li>782 Plains Tiles</li>
                <li>310 Suburban Tiles</li>
                <li>116 Commercial Tiles</li>
              </ul>
              <p>
                The City Center of Crotopolis is constructed of the equivalent
                size of 144 Tiles; however, lands within the City Center will
                not be available for sale. Instead, lands in the City Center are
                reserved for social gatherings, project partners and promotional
                content.
              </p>
            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header
              >How Much Will A Land Tile Cost?</v-expansion-panel-header
            >
            <v-expansion-panel-content>
              <p>
                Land Tiles vary in price based on their usage type and proximity
                to the Crotopolis City Centre. Land prices will be available in
                the very near future. Please stay tuned. The types of tiles
                available are as follows:
              </p>
              <ul>
                <li>Plains Tiles</li>
                <li>Suburban Tiles</li>
                <li>Commerical District Tiles</li>
              </ul>
            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header
              >What Can I Do With My Land?</v-expansion-panel-header
            >
            <v-expansion-panel-content>
              <p>
                Land owners will be able to build structures on their land for
                their NFT characters, friends, and community members to enjoy.
              </p>
              <p>
                Each Land Tile will come preloaded with the appropriate building
                materials for the designated land use of the tile. Land owners
                will be able to build out their lands as they see fit using the
                building kits from their preloaded inventory; absolutely no
                coding required.
              </p>
              <p>
                Alternatively, Land Owners can import their own 3D digital
                assets created on Blender, Maya, 3DSM our other compatable 3D
                animation software.
              </p>
              <p>
                Prior to launch of our social MMO, Land owners will be given
                time to develop their land tiles in Phase 4. Upon launch of our
                social MMO, changes to land can only be done so periodically,
                and will be imported by our team to launch on the next scheduled
                MMO map update.
              </p>
            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header
              >What Is Land Amalgamation & How Does It
              Work?</v-expansion-panel-header
            >
            <v-expansion-panel-content>
              <p>
                Land Amalgamation is the joining of two or more advancement land
                tiles. This process allows land owners who have adjacent land
                tiles in the same wallet to permanently join those lands. By
                doing so, users can pool all of the resources in each tile to
                construct larger buildings.
              </p>
              <p>
                **Land Amalgamation can only be done once and will not be
                reversible.***
              </p>
              <p>
                Requests for Land Amalgamations will be made available to land
                owners at the completion of Phase 3. Land owners will then
                exchange their adjacent land tiles tokens for a newly formed
                token and the previously issued tokens will be burned.
              </p>
              <p>Amalgamation is only available for Plains and Suburban Lots</p>
              <li>
                Allowed Formats for Plains (up to 16 adjacent tiles): 1x2, 1x3,
                1x4, 2x2, 2x3, 2x4,3x3, 3x4, or 4x4 configurations
              </li>
              <li>
                Allowed Formats for Suburban Tiles (up to 4 adjacent tiles):
                1x2, 1x3, 1x4, or 2x2
              </li>
              <li>
                Allowed Formats for Commercial Tiles (up to 4 adjacent tiles):
                1x2, 1x3, 1x4, or 2x2
              </li>
            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header
              >Who are the CroVilians?</v-expansion-panel-header
            >
            <v-expansion-panel-content>
              <p>
                Crovilians are the future citizens of The CronosVerse. They will
                be available in Phase 3 of our road map. Crovilans will come in
                generative collections and have various traits representing the
                many societal roles needed in the metaverse, such as
                construction workers, tradespeople, teachers, doctors, police
                officers, bankers, professionals, restuarant workers, etc. Each
                Crovilian will serve a different purpose in our metaverse
                society. Holding a Crovilian NFT will grant you access to The
                CronosVerse. Crovilans will need places to live, so they will
                rent lands from land owners, apartments in Crotopolis, and work
                in the various businesses in the City Centre and Commerical
                Districts. Most importanty, Crovilians will build relationships
                with their fellow citizens and become an integrated part of The
                CronosVerse Society.
              </p>
            </v-expansion-panel-content>
          </v-expansion-panel>
        </v-expansion-panels>
      </v-row>
    </div>
    <v-divider id="divider" ></v-divider>
    <h1 id="projecth1">Our Project Road Map</h1>
    <v-divider id="divider"></v-divider>
    <div>
    <v-row justify="center">
      <v-timeline :dense="$vuetify.breakpoint.smAndDown">
      <v-timeline-item>
        <span slot="opposite">Phase 1</span>
        <v-card width="450px" class="elevation-2">
          <v-card-title class="text-h5">
            Project Launch
          </v-card-title>
          <v-card-text>
            <ul>
              <li>The CronosVerse Project Announcement</li>
              <li>Twitter, Webpage & AMAs</li>
              <li>Game Concept Release</li>
              <li>Initial Project Partner Announcements</li>
            </ul>
          </v-card-text>
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
        <span slot="opposite">Phase 2</span>
        <v-card width="450px" class="elevation-2">
          <v-card-title class="text-h5">
            Initial Land Offering
          </v-card-title>
          <v-card-text>
            <ul>
              <li>Land Map Release</li>
              <li>Initial Land Offering/Land Sales Go Live</li>
              <li>Discord Server</li>
              <li>Community Engagement (Giveaways, Prizes, Contests)</li>
            </ul>
          </v-card-text>
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
        <span slot="opposite">Phase 3</span>
        <v-card width="450px" class="elevation-2">
          <v-card-title class="text-h5">
            The CroVilians
          </v-card-title>
          <v-card-text>
            <ul>
              <li>Secondary Market Land Sales Go Live</li>
              <li>Crovilians NFT (Citizens of The CronosVerse)</li>
              <li>Partner Metaverse Teasers</li>
              <li>Charity Announcements to Fight Homelessness</li>
            </ul>
          </v-card-text>
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
        <span slot="opposite">Phase 4</span>
        <v-card width="450px" class="elevation-2">
          <v-card-title class="text-h5">
            Alpha Gameplay
          </v-card-title>
          <v-card-text>
            <ul>
              <li>Land Amalgamations (see FAQ)</li>
              <li>Web3 Connectivity to Unreal Engine Gameplay</li>
              <li>Alpha Game Play for Land Owners</li>
              <li>Road Map 2.0</li>
            </ul>
          </v-card-text>
        </v-card>
      </v-timeline-item>
    </v-timeline>
    </v-row>
    </div>
    <v-divider id="divider"></v-divider>
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
    <v-divider id="divider"></v-divider>
    <h1 id="projecth1">Our Project Partners</h1>
    <v-row justify="center">
    <div id="supportcontainer">
      <div id="support">
      <img src="https://i.ibb.co/yXfL5xF/TopBlok.png" onlick="topblok()" class="partnersimg">
      <img src="https://i.ibb.co/LCXNn68/crodex.png" class="partnersimg">
      <img src="https://i.ibb.co/ZH5dLkp/The-Cronicle.png" class="partnersimg">
      <img src="https://i.ibb.co/jysV8jC/Primate-Cronos.png" class="partnersimg">
      <img src="https://i.ibb.co/PmKx9y5/Cro-Skulls.jpg" class="partnersimg">
      <img src="https://i.ibb.co/6Xtjkqc/cronos-nana.png" class="partnersimg">
      <img src="https://i.ibb.co/r35Q4Vr/Cronos-Chimp-Club.jpg" class="partnersimg">
      <img src="https://i.ibb.co/dGnnGmX/CroMoon.png" class="partnersimg">
      <img src="https://i.ibb.co/ncZJt4Z/Crobots-Logo.png" class="partnersimg">
      </div>
    </div>
    </v-row>
  </v-app>
</template>

<script>
import navbar from "@/components/navbar.vue";
export default {
  name: "team",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
  components: {
    navbar,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Russo+One&display=swap");

v-card-title {
  font-family: "Russo One", sans-serif;
}

span {
  font-family: "Russo One", sans-serif;
  font-size: 32px;
}

li {
  font-family: "Russo One", sans-serif;
  font-size: 15px;
}

#support {
  width: 80%;
  margin: auto;
  margin-top: 30px;
}

#projecth1 {
  margin-top: 50px;
  margin-bottom: 50px;
}

#supportcontainer{
  background-color: black;
}

.partnersimg {
  height: 250px;
  width: 300px;
  align-items: center;
}

#navbar {
  background-color: black;
}
#expansioncontainer {
  width: 80%;
  margin: auto;
  margin-top: 20px;
}
h1 {
  margin: auto;
  color: black;
  font-family: "Russo One", sans-serif;
  font-size: 50px;
}

#divider {
  margin-top: 30px;
  margin-bottom: 30px;
}
</style>
