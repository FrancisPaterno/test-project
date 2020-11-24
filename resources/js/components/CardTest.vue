<template>
<v-container class="mx-auto" dark>
<v-card flat max-width="500">
        <v-card-title flat >
            <v-row class="content-center">
                <v-col cols="7" class="d flex flex-col">
                        <h4><strong>Overall rating</strong></h4> 
                        <div class="d flex flex-row text-center">
                        <p class="text-2xl cyan--text darken-1">4.2</p> 
                        <div class="content-center mx-3">
                            <v-icon small color="cyan darken-2">star_rate</v-icon>
                            <v-icon small color="cyan darken-2">star_rate</v-icon>
                            <v-icon small color="cyan darken-2">star_rate</v-icon>
                            <v-icon small color="cyan darken-2">star_rate</v-icon>
                            <v-icon small color="cyan darken-2">star_rate</v-icon>
                        </div>
                        
                        <p class="grey--text"> 65 Votes</p> 
                        </div>
                </v-col>
                <v-col cols="2">
                    <v-btn text >
                        <v-icon>
                            add
                        </v-icon>
                    </v-btn>
                </v-col>
            </v-row>
           
        </v-card-title>
        <v-divider></v-divider>
        <v-card-text class="mx-2">
            <v-row>
                <v-col cols="2" >
                     <v-img src="https://cdn.vuetifyjs.com/images/profiles/marcus.jpg" max-height="50px" max-width="50px" ></v-img>
                </v-col>
                <v-col>
                    <h3>Philip Martin</h3>
                    <v-icon small color="cyan darken-2">star_rate</v-icon>
                    <v-icon small color="cyan darken-2">star_rate</v-icon>
                    <v-icon small color="cyan darken-2">star_rate</v-icon>
                    <v-icon small>star_rate</v-icon>
                    <v-icon small>star_rate</v-icon>
                    6 days ago
                </v-col>
            </v-row>
            <v-row>
                <v-col>
                    <p style="text-align:justify">
                        This place is all you need for tha short <br> or long trip to Tbilisi. Perfect <br> location! Sparkling clean and modern.
                    </p>
                </v-col>
            </v-row>
        </v-card-text>
        <v-card-actions class="grey--text mx-4"> 
            from Facebook
        </v-card-actions>
    </v-card>
</v-container>
    
</template>
<script>
export default {
    
}
</script>