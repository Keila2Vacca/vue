<script setup>
let count = 0;
function addvalue() {
    count++;
    console.log(count);
}
</script>

<template>
<div @click="addvalue()" class="bg-blue-500 text-white py-2 px-4 rounded inline-block hover:cursor-pointer hover:bg-blue-700 transition-colors">
    ¡presioname! {{ count }}
</div>
</template>