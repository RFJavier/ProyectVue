<script setup lang="ts"></script>
<template>
    <div class="w-screen h-screen bg-gradient-to-r from-amber-200 to-sky-300 flex justify-center items-center" >
        
        <div class="bg-[url('./assets/img/OIP.jpg')] rounded-3xl bg-auto border-x-8 border-t-sky-300/100 border-l-sky-300/100 border-b-amber-200/100 border-r-amber-200/100 shadow-xl w-96 p-5" >
            <!-- <div class="border-2 border-t-sky-300/100 border-l-sky-300/100 border-b-amber-200/100 border-r-amber-200/100 backdrop-blur-sm rounded-xl text-right text-4xl font-bold p-2 w-full h-16 ">0</div> -->
            <input placeholder="0" class="border-4 border-t-sky-300/100 border-l-sky-300/100 border-b-amber-200/100 border-r-amber-200/100 bg-gradient-to-r from-amber-200 to-sky-300 rounded-xl text-right text-4xl font-bold text-black w-full h-16 p-2">
            <div class="justify-items-center grid grid-cols-2 w-full h-1/4  p-1 mt-4">
                <div class="grid grid-cols-2 w-full h-full" >
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">1</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">2</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">4</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">5</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">7</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">8</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">.</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">0</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">(</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">)</button>
                </div>
                <div class="grid grid-cols-2 w-full h-full" >
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">3</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">+</button>
                    <button class="border-2 border-sky-300 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">6</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">-</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">9</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">x</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">%</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-16 m-3 pb-1 mb-1">/</button>
                    <button class="border-2 border-amber-200 backdrop-blur-sm rounded-full shadow-blue-700 hover:shadow-xl text-xl font-semibold w-36  m-3 pb-1 mb-1">=</button>
                </div>
            </div>  
        </div>
        </div>
</template>