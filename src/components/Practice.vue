<script setup lang="ts">
    import { ref } from 'vue';
    //Variable reactiva//
    const Name =ref<number>(0);
    let Numeros = ref<number[]>([1,2,3,4,5,6,7,8,9,10]); 

    let numeroIngresado = ref<number>(0);

    function AgregarNumeros(){
        Numeros.value.push(Numeros.value.length +1)
    }

    function cambiarNumero(){
        Numeros.value.push(Name.value)
    }
    function NuevoNumero(){
        Numeros.value.map((numero )=>{ 
            console.log(`${numero} * ${numeroIngresado.value} El resultado es:  ${numero*numeroIngresado.value}`)
         })
    }

    function filtrarNumero(){
        
        let numeroPar = Numeros.value.filter((numero)=> numero % 2 !== 0 )

        // console.log(numeroPar)
        return numeroPar;
    }

    function multiplicar(){
        filtrarNumero().map((numero )=>{ 
            console.log(`${numero} * ${numeroIngresado.value} El resultado es:  ${numero*numeroIngresado.value}`)
         })
    }
    
</script>

<template>

    <button id="Nuevo" @click="multiplicar">
        multiplicar
    </button>

    <button id="Nuevo" @click="filtrarNumero">
        Filtrar
    </button>

    <button id="Nuevo" @click="NuevoNumero">
        Nuevo
    </button>

    <p>
        {{ Name }}
    </p>
    <input type="text" v-model="numeroIngresado">
    <button @click="AgregarNumeros">Change</button>
    <button @click="cambiarNumero">Change</button>
    <ul>
        <li v-for="numero in Numeros">
            {{ numero }}
        </li>
    </ul>
</template>

<style>
</style>