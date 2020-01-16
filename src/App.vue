<template>
    <v-app>
        <app-navigation></app-navigation>
        <v-app-bar app>{{appTitle}}</v-app-bar>
        <v-content>
            <!-- If using vue-router -->
            <router-view></router-view>
        </v-content>
        <v-footer app>
            <!-- -->
        </v-footer>
    </v-app>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';

export default {
    name: 'App',
    components: {
        AppNavigation
    },
    data() {
        return {
            appTitle: 'ABC WebApplication'
        };
    }
};
</script>

<style>
</style>