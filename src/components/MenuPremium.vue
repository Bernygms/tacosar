<template>
  <section id="menu" class="py-16 px-6">
    <h2 class="text-3xl font-bold text-center mb-10">
      Menú
    </h2>

    <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      
      <div v-for="item in menu" :key="item.nombre"
        class="bg-white/80 backdrop-blur p-6 rounded-2xl border border-orange-100 shadow-lg hover:shadow-xl hover:-translate-y-1 transition">

        <h3 class="text-lg font-semibold mb-1">{{ item.nombre }}</h3>
        <p class="text-gray-500 text-sm mb-3">{{ item.desc }}</p>

        <span class="text-orange-600 text-lg font-bold">
          ${{ item.precio }}
        </span>

      </div>

    </div>
  </section>
</template>

<script setup>
const menu = [
  { nombre: "Tacos al pastor", desc: "Con piña", precio: 15 },
  { nombre: "Tacos de asada", desc: "A la parrilla", precio: 18 },
  { nombre: "Cemita de milanesa", desc: "Con quesillo", precio: 45 }
]
</script>