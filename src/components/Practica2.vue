<script setup lang="ts">
let num:number = 16;

//if and else corriente
if (num >= 7 && num <=10  ) {
    console.log("El numero no es igual")
}
else{ 
    console.log("El numero no es igual")
}

// and &&
// or ||
// condicion ternaria
num >= 10 && num <=19 ? console.log("condicion corecta") : console.log("condicion incorrecta")

// ternaria con and integrado

num >=10 && num <19 && console.log("condicion 1")


</script>

<template>
<h1 v-if="num==10">Practica 2</h1>
<h1 v-else>Practica 2</h1>
<h1 v-show="num == 16">Ah facilito donde le subo la dificultad a estos bots</h1>

</template>

<style>
</style>