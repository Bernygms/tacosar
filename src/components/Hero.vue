<template>
  <section class="relative pt-28 pb-16 px-6 text-center overflow-hidden">

    <!-- Fondo blur decorativo -->
    <div class="absolute -top-20 -left-20 w-72 h-72 bg-orange-300 rounded-full blur-3xl opacity-30"></div>
    <div class="absolute -bottom-20 -right-20 w-72 h-72 bg-red-300 rounded-full blur-3xl opacity-30"></div>

    <img 
      class="relative z-10 rounded-2xl shadow-xl mx-auto mb-6 max-w-md hover:scale-105 transition duration-500"
    />

    <h1 class="text-4xl md:text-5xl font-extrabold mb-3 leading-tight">
      Tacos & Cemitas
      <span class="text-orange-600">con sabor real</span>
    </h1>

    <p class="text-gray-500 mb-6 max-w-md mx-auto">
      Preparados al momento en Tehuacán. Rápidos, ricos y bien servidos.
    </p>

    <div class="flex justify-center gap-4 flex-wrap">
      <a 
        href="#menu"
        class="bg-orange-500 text-white px-6 py-3 rounded-full font-semibold shadow-md hover:scale-105 transition"
      >
        Ver menú
      </a>

      <a 
        href="https://wa.me/521XXXXXXXXXX"
        class="bg-green-500 text-white px-6 py-3 rounded-full font-semibold shadow-md hover:scale-105 transition"
      >
        Pedir ahora
      </a>
    </div>

  </section>
</template>