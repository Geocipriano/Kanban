<template>
    <nav>
        <v-toolbar dark app>
            <v-btn round  dark @click="draw = 'true'">Tarefas</v-btn>
            <v-spacer></v-spacer>
            <v-toolbar-title>
                <span class="font-italic success--text">Atual</span>
                <span> Kanban</span>
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn color="success">Sair</v-btn>
        </v-toolbar>
        <v-navigation-drawer v-model="draw" app color="success">
            <v-btn flat block @click="drawer = false">Retornar</v-btn>
        </v-navigation-drawer>
    </nav>
</template>

<script>
export default {
    data() {
        return {
            draw : false
        }
    }
}
</script>