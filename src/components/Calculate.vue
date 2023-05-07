<script setup lang="ts" >

</script>
<template>
    <div class="w-screen h-screen flex justify-center items-center bg-[#00a8b5]">

        <div class=" w-96 h-100  p-4  bg-[#176886] flex flex-col rounded-lg shadow-2xl">
            <h1 class="w-80 h-20 mx-4 p-4 text-xl text-white text-center">
                Calculadora
            </h1>
            <input placeholder="0" class=" w-80 h-12 mx-4 p-4 text-lg text-white text-end bg-[#1d3d66] border-4 border-gray-400 rounded-full">
            <div class="w-full grid grid-cols-4 p-1">
                <button class="bg-[#886c94] border-4 border-gray-400 p-2 rounded-full text-white w-18 m-2 ">C</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">*</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2 ">/</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2 ">+</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">7</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2 ">8</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2 ">9</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18  m-2">-</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg  p-2 rounded-full text-white w-18 m-2">5</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">6</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">7</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">%</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">1</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">2</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">3</button>
                <button class="bg-[#886c94] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-18 m-2">0</button>
            </div>
            <div class="w-full grid grid-cols-4 p-1">
                <button class="bg-[#dd6c98] border-4 border-gray-400 text-lg p-2 rounded-full text-white w-80 m-2">=</button>
            </div>
        </div>
    </div>
</template>