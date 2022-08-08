<template>
    <div class="d-flex flex-column ">
        <div class="d-flex justify-center">

            <a href="https://vuetifyjs.com/en/" target="_blank">
                <v-tooltip left>
                    <template v-slot:activator="{ on, attrs }">
                        <v-img src="../assets/logo.svg" width="100px" v-bind="attrs" v-on="on"> </v-img>
                    </template>
                    <span>Vuetifyjs</span>
                </v-tooltip>
            </a>
        </div>

        <div class="d-flex justify-center mt-5">
            <v-card width="60%">

                <v-card-title primary-title class="d-flex justify-center">
                    Consigne
                </v-card-title>

                <v-card-text>


                    <p>
                        Nous utilisons Vuejs 2.6 comme frameWork Js et Vuetify comme framwork Css.<br />
                        VueJs et Vuetify sont déja installer.<br />
                        Tu peut utiliser vuex, vueRouteur, axios...
                    </p>

                    <p>
                        Tu va utiliser l'api de <a href="https://pokeapi.co/" target="_blank"> Pokemon</a>
                    </p>

                    <v-list-item>
                        <v-list-item-content>
                            <v-list-item-title>
                                <v-icon small color="black" class="mr-2">mdi-circle</v-icon>Afficher la liste des
                                pokemons
                            </v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>

                    <v-list-item>
                        <v-list-item-content>
                            <v-list-item-title>
                                <v-icon small color="black" class="mr-2">mdi-circle</v-icon>Pouvoir en afficher 5 - 10 -
                                15
                                -20 par page
                            </v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>

                    <v-list-item>
                        <v-list-item-content>
                            <v-list-item-title>
                                <v-icon small color="black" class="mr-2">mdi-circle</v-icon>Voir la description du
                                pokemon
                                dans une nouvelle page
                            </v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>

                    <v-list-item>
                        <v-list-item-content>
                            <v-list-item-title>
                                <v-icon small color="black" class="mr-2">mdi-circle</v-icon>Mettre en favorie ces
                                Pokemon
                                préférer
                            </v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>

                    <v-list-item>
                        <v-list-item-content>
                            <v-list-item-title>
                                <v-icon small color="black" class="mr-2">mdi-circle</v-icon>Page de ces Pokemon favorie
                            </v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>


                </v-card-text>
            </v-card>
        </div>








    </div>
</template>

<script>
export default {
    name: "InstructionsTest"
}
</script>

<style scoped>
</style>