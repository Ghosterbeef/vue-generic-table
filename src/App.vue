<template>
    <VTable :items="tableItems"></VTable>
</template>

<script setup lang="ts">
import VTable from "@/components/VTable.vue";
import {ref} from "vue";

const tableItems = ref([
    {id: '124', name: 'Johnson', age: 22},
    {id: '125', name: 'Brown', age: 19},
    {id: '126', name: 'Williams', age: 21},
    {id: '127', name: 'Jones', age: 23},
    {id: '128', name: 'Davis', age: 18},
    {id: '129', name: 'Miller', age: 20},
    {id: '130', name: 'Wilson', age: 24},
    {id: '131', name: 'Moore', age: 19},
    {id: '132', name: 'Taylor', age: 22},
    {id: '133', name: 'Anderson', age: 20},
    {id: '134', name: 'Thomas', age: 21},
    {id: '135', name: 'Jackson', age: 23},
    {id: '136', name: 'White', age: 18},
    {id: '137', name: 'Harris', age: 19},
    {id: '138', name: 'Martin', age: 22},
    {id: '139', name: 'Thompson', age: 20},
    {id: '140', name: 'Garcia', age: 24},
    {id: '141', name: 'Martinez', age: 19},
    {id: '142', name: 'Robinson', age: 21},
    {id: '143', name: 'Clark', age: 23}
]);
</script>

<style scoped>
</style>
