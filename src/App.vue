<template>
  <div class="bg-no-repeat bg-cover bg-fixed min-h-screen"
    style="background-image: url('https://gradient.page/_next/image?url=%2Fcdn%2Fvibrant-vista%2Fvibrant-vista-004.jpg&w=1920&q=75')">
    <nav class="bg-white shadow fixed top-0 left-0 w-full z-50">
      <div class="container mx-auto px-4 py-2 flex justify-between items-center">
        <a href="#" class="font-bold text-xl">Mi Portafolio</a>
        <ul class="hidden md:flex space-x-4">
          <li><a href="#home" class="hover:text-gray-700">Home</a></li>
          <li><a href="#about" class="hover:text-gray-700">About</a></li>
          <li><a href="#experiencia" class="hover:text-gray-700">Experiencia</a></li>
          <li><a href="#proyectos" class="hover:text-gray-700">Proyectos</a></li>
          <li><a href="#contacto" class="hover:text-gray-700">Contacto</a></li>
        </ul>
      </div>
    </nav>

    <main class="container mx-auto py-16">
      <div class="mt-16">
        <section id="home" class="bg-cover bg-center text-white"
          style="background-image: url('https://media.licdn.com/dms/image/v2/C4E1BAQFg1NOq1-rafg/company-background_10000/company-background_10000/0/1584603073015/colegio_de_profesionales_en_tecnologas_de_la_informacin_e_informtica_de_mxico_a_c_cover?e=2147483647&v=beta&t=83B843T-4wCvzwImcHo-ITDcP43_NZzGRyNAC7vNkss')">
          <div class="container mx-auto py-32">
            <div class="bg-gray-900 text-center">
              <h1 class="text-5xl font-bold text-white text-shadow-xl">Hola, soy [Tu Nombre]</h1>
              <p class="text-lg mt-4 text-white text-shadow-md">[Breve descripción sobre ti]</p>
            </div>
          </div>
        </section>
      </div>
      <div class="mt-16">
        <section id="about" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Sobre Mí</h2>
          <p>[Escribe aquí una descripción más detallada sobre ti, tus habilidades y experiencia]</p>
          <img class="rounded-full mx-auto" src="[Tu imagen]" alt="Tu foto" width="200">
        </section>
      </div>
      <div class="mt-16">
        <section id="experiencia" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Experiencia Laboral</h2>
        </section>
      </div>
      <div class="mt-16">
        <section id="proyectos" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Proyectos</h2>
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <div v-for="project in projects" :key="project.id" class="bg-white shadow-md rounded-lg overflow-hidden">
              <img class="w-full" :src="project.image" alt="Imagen del proyecto">
              <div class="p-4">
                <h3 class="text-xl font-bold">{{ project.title }}</h3>
                <p>{{ project.description }}</p>
              </div>
            </div>
          </div>
        </section>
      </div>
      <div class="mt-16">
        <section id="contacto" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Contacto</h2>
          <p>Encuéntrame en:</p>
        </section>
      </div>
    </main>

    <footer class="bg-gray-800 text-white py-4">
      <div class="container mx-auto text-center">
        <p>© 2023 [Tu Nombre]. Todos los derechos reservados.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        // ... tus proyectos aquí
      ]
    }
  }
}
</script>