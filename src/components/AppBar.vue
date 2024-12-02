<template>

    <v-app-bar :elevation="2">
        <template v-slot:prepend>
                <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>
        <div class="menubar">

            <v-app-bar-title>Application Bar</v-app-bar-title>
            <TopMenu/>
        </div>
    </v-app-bar>
</template>

<script setup>
//
</script>
<style>
.menubar{
    display: flex;
    justify-content: space-between;
    width: 100%;
}
</style>