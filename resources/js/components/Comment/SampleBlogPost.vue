<template>
    <v-card class="mx-auto" color="#26c6da" dark>
        <v-card-title>
            <v-icon large left>mdi-twitter</v-icon>
            <span class="text-h6 font-weight-light">Sample Tweet</span>
        </v-card-title>

        <v-card-text class="text-h5 font-weight-bold">
            "Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as
            well."
        </v-card-text>

        <v-card-actions>
            <div class="grow">
                <v-list-item>
                    <v-list-item-avatar color="grey darken-3">
                        <v-img class="elevation-6" alt=""
                               src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"/>
                    </v-list-item-avatar>

                    <v-list-item-content>
                        <v-list-item-title>Evan You</v-list-item-title>
                    </v-list-item-content>

                    <v-row align="center" justify="end">
                        <v-icon class="mr-1">mdi-heart</v-icon>
                        <span class="subheading mr-2">256</span>
                        <span class="mr-1">·</span>
                        <v-icon class="mr-1">mdi-share-variant</v-icon>
                        <span class="subheading">45</span>
                    </v-row>
                </v-list-item>

                <AddComment/>
            </div>
        </v-card-actions>
    </v-card>
</template>
<script>
import AddComment from "./AddComment";

export default {
    components: {AddComment}
}
</script>
