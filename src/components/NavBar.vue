<template>
  <v-app-bar height="80" color="#fef5f8" id="inspire" scroll-behavior="elevate">
    <v-img src="/src/img/1.png"></v-img>
    <v-app-bar-title class="text-h4">Explore</v-app-bar-title>
    <v-spacer></v-spacer>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#634709" v-bind="props">HOME +</v-btn>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>Home page one</v-list-item-title>
                <v-list-item-title>Home page two</v-list-item-title>
            </v-list-item>
        </v-list>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#634709" v-bind="props">Tours +</v-btn>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>Tour grid</v-list-item-title>
                <v-list-item-title>Tour list</v-list-item-title>
                <v-list-item-title>Tour single</v-list-item-title>
            </v-list-item>
        </v-list>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#634709" v-bind="props">Hotel</v-btn>
        </template>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#634709" v-bind="props">pages +</v-btn>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>About</v-list-item-title>
                <v-list-item-title>Team</v-list-item-title>
                <v-list-item-title>Faq</v-list-item-title>
                <v-list-item-title>404</v-list-item-title>
            </v-list-item>
        </v-list>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#634709" v-bind="props">Blog</v-btn>
        </template>
    </v-menu>
    <v-menu transition="slide-x-transition">
        <template v-slot:activator="{props}">
            <v-btn color="#634709" v-bind="props">Contact</v-btn>
        </template>
    </v-menu>
    <v-btn class="text-none mr-8 expl" color="indigo-lighten-1" size="x-large" variant="flat" rounded="0">
        Get Exploration
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {

}
</script>

<style>
.expl {
    background-color: white;
    color: #6347f9;
}
</style>