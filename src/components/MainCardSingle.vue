<script setup>
import { faker } from '@faker-js/faker';
    const firstname = faker.person.firstname()
    const lastname = faker.person.lastname()
     

</script>

<template>
    {{ firstname }}  {{ lastname }} <br/>
</template>