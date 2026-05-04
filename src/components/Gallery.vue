<template>
  <section class="py-16 px-6">
    <h2 class="text-3xl font-bold text-center mb-10">
      Nuestros platillos
    </h2>

    <div class="grid grid-cols-2 md:grid-cols-4 gap-4 max-w-6xl mx-auto">
      <img 
        v-for="i in 8" 
        :key="i"
        class="rounded-xl shadow-md hover:scale-105 transition duration-300"
      />
    </div>
  </section>
</template>