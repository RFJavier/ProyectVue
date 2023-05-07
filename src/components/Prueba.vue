<script setup lang="ts">
import { ref } from 'vue';


let valor = ref<number>(0);

let arreglo =ref<number[]>([1,2,3,4,5,6]) ;

function AgregarNumero() {

    arreglo.value.push(arreglo.value.length + 1)
}

function Nuevo(){
arreglo.value.map((numero)=>{console.log(`${numero} * ${valor.value} =  ${numero*valor.value}` )})

}

function filtro(){
   const par = arreglo.value.filter((numero)=>numero%2 === 0 )
   return par
}


function multimpares(){
    arreglo.value.filter((numero)=>numero%2 !== 0).map((numero)=>{console.log(`${numero} * ${valor.value} =  ${numero*valor.value}` )})

}

function multpares(){
    filtro().map((numero)=>{console.log(`${numero} * ${valor.value} =  ${numero*valor.value}` )})
}
</script>
<template>
    <input type="text" v-model="valor"/>
    <button @click="AgregarNumero">change</button>
    
<ul>
    <li v-for="numero in arreglo" >

        {{ numero }}
    
    </li>
</ul>

<button @click="Nuevo">nuevo</button>

<button @click="filtro">Numero Par</button>

<button @click="multimpares">multiplcar pares</button>

</template>
