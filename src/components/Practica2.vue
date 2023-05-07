<script setup lang="ts">

    // condiciones en js o ts
    let numero = 1;
    if(numero === 2 || numero >=2 || numero <= 15){
        console.log(`La condicion de ${numero} es verdadera`)
    }
    else{
        console.log('la condicion es falsa')
    }

    numero >=2  ? console.log('la condicion es verdadera')  : numero <=15 && console.log('la condicion es falsa')

    // condiciones en vue


</script>
<!-- <template>
    <h1 v-if="numero >=2 || numero <=25">
        Verdadero
    </h1>
    <h1 v-else>
        Falso
    </h1>

    <h1 >
        hola
    </h1>
</template> -->