<template>
    <v-app id="selfmade" dark>
        <v-content>
            <v-container fluid fill-height>
                <v-layout align-center justify-center row fill-height>
                    <v-flex xs12 sm10 md8 class="text-xs-center">
                        <v-flex class="anpassung"  xs6 align-content-center justify-center>
                            <v-img class="anpassung groeße" justify-center align-center style="width: 200px" :src="$withBase('/SME_schw_hg.svg')" alt="logo"></v-img>
                        </v-flex>
                        <div class="white--text display-3 font-weight-medium text-uppercase">
                            Coming soon
                        </div>
                        <div class="display-2 font-weight-black gold">2019</div>
                    </v-flex>
                </v-layout>
            </v-container>
        </v-content>
        <v-footer color="#000">
            <v-layout align-center justify-center>
                <div class="justify-center">&copy;2019 - SELF.MADE. Enterprises</div>
            </v-layout>
        </v-footer>
    </v-app>
</template>

<style lang="stylus">
    @import '~vuetify/src/stylus/theme.styl'

    $material-dark.background = #000

    @import '~vuetify/src/stylus/main'

    .gold {
        color: #AE9A64;
    }
    .anpassung
    {
        margin: auto;
    }

    @media only screen and (min-width: 900px) {

        .groeße
        {
            width: 300px !important;
        }
    }

</style>