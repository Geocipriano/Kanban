<template>
<v-navigation-drawer permanent color="#FB8B24">
    <v-toolbar flat>
        <v-list>
            <v-list-tile>
                <v-list-tile-title class="title">
                    Application
                </v-list-tile-title>
            </v-list-tile>
        </v-list>
    </v-toolbar>
    <v-divider></v-divider>
    <v-list dense class="pt-0">
        <v-list-tile >
            <v-list-tile-action>
                <v-icon></v-icon>
            </v-list-tile-action>
            <v-list-tile-content>
                <v-list-tile-title>Teste</v-list-tile-title>
            </v-list-tile-content>
        </v-list-tile>
    </v-list>
</v-navigation-drawer>
</template>


<script>
export default {
    name : 'sidebar',
}
</script>