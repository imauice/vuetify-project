<template>
  <v-container>
    <div class="space-between">
      <v-breadcrumbs :items="['Foo', 'Bar', 'Fizz']"></v-breadcrumbs>
      <v-btn>
        Insert
      </v-btn>
    </div>
    <DataTable />
  </v-container>
</template>

<script setup>
//
</script>
<style>
.space-between {
  display: flex;
  justify-content: space-between;
}
</style>
