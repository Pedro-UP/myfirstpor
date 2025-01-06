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
              <h1 class="text-5xl font-bold text-white text-shadow-xl">Hola, soy Pedro Luis</h1>
              <h1 class="text-5xl font-bold text-white text-shadow-xl">Desarollador Full-Stack</h1>
              <p class="text-lg mt-4 text-white text-shadow-md">Soy un ingeniero en informática con una
                pasión innata por la tecnología. Me encanta resolver problemas complejos y crear soluciones innovadoras.
                Mi experiencia en desarrollo web me permite dar vida a ideas creativas y construir productos digitales
                que impactan a los usuarios.</p>
            </div>
          </div>
        </section>
      </div>
      <div class="mt-16">
        <section id="about" class="py-16 px-8">
          <h2 class="text-3xl font-bold mb-8 text-center">Sobre Mí</h2>
          <div class="flex flex-col md:flex-row items-center md:space-x-8">
            <!-- Contenedor de texto -->
            <div class="md:w-2/2">
              <h1 class="text-2xl font-bold mb-8">
                Soy un apasionado desarrollador full-stack con una sólida experiencia en
                la creación de aplicaciones web dinámicas e interactivas.
              </h1>
              <p>
                Me encanta transformar ideas en soluciones digitales que deleitan a los usuarios. Mis habilidades
                abarcan desde el desarrollo frontend usando React o Vue hasta el backend con Laravel. He trabajado en
                diversos
                proyectos,
                desde la construcción de sitios web corporativos hasta el desarrollo de aplicaciones móviles híbridas.
                Mi enfoque se centra en crear experiencias de usuario intuitivas y optimizar el rendimiento de las
                aplicaciones.
                Estoy constantemente aprendiendo nuevas tecnologías y buscando oportunidades para mejorar mis
                habilidades.
              </p>
            </div>
            <img class="rounded-full border-2 border-gray-300 shadow-md w-40 md:w-56"
              :src="require('@/assets/IMG20231231233658.jpg')" alt="Pedro C" />
          </div>
          <!-- Cuadrícula de iconos -->
          <div class="grid grid-cols-2 sm:grid-cols-4 gap-6 mt-8 text-center">
            <div class="flex flex-col items-center">
              <img src="https://cdn-icons-png.flaticon.com/128/732/732212.png" alt="HTML Icon" class="w-12 h-12">
              <p class="mt-2 text-sm">HTML</p>
            </div>
            <div class="flex flex-col items-center">
              <img src="https://cdn-icons-png.flaticon.com/512/7939/7939651.png" alt="CLI Icon" class="w-12 h-12">
              <p class="mt-2 text-sm">CLI</p>
            </div>
            <div class="flex flex-col items-center">
              <img src="https://cdn-icons-png.flaticon.com/128/5968/5968292.png" alt="JavaScript Icon"
                class="w-12 h-12">
              <p class="mt-2 text-sm">JavaScript</p>
            </div>
            <div class="flex flex-col items-center">
              <img src="https://vuejs.org/images/logo.png" alt="Vue.js Icon" class="w-12 h-12">
              <p class="mt-2 text-sm">Vue.js</p>
            </div>
            <div class="flex flex-col items-center">
              <img src="https://cdn-icons-png.flaticon.com/512/919/919851.png" alt="React Icon" class="w-12 h-12">
              <p class="mt-2 text-sm">React</p>
            </div>
            <div class="flex flex-col items-center">
              <img
                src="https://static.vecteezy.com/system/resources/previews/012/697/294/original/3d-laravel-programming-framework-logo-free-png.png"
                alt="Laravel Icon" class="w-12 h-12">
              <p class="mt-2 text-sm">Laravel</p>
            </div>
            <div class="flex flex-col items-center">
              <img src="https://cdn-icons-png.flaticon.com/128/5968/5968350.png" alt="Python Icon" class="w-12 h-12">
              <p class="mt-2 text-sm">Python</p>
            </div>
            <div class="flex flex-col items-center">
              <img src="https://logoeps.com/wp-content/uploads/2012/03/mysql-vector1.jpg" alt="MySQL Icon"
                class="w-12 h-12">
              <p class="mt-2 text-sm">MySQL</p>
            </div>
          </div>
        </section>
      </div>
      <div class="mt-16">
        <section id="experiencia" class="py-20">
          <div class="container mx-auto px-4">
            <h2 class="text-center text-3xl font-bold mb-12 text-gray-800">Experiencia Laboral</h2>
            <div class="flex justify-center">
              <div class="max-w-md bg-white rounded-lg shadow-xl overflow-hidden md:max-w-2xl">
                <div class="md:flex">
                  <div class="md:shrink-0">
                    <img class="h-48 w-full md:h-full md:w-48 object-cover rounded-l-lg"
                      src="https://media.glassdoor.com/sqll/7350306/golsystems-squarelogo-1657012187062.png"
                      alt="GOLSYSTEMS">
                  </div>
                  <div class="p-8">
                    <div class="uppercase tracking-wide text-sm text-indigo-700 font-semibold">Golsystems de
                      México</div>
                    <p class="mt-2">
                      Desarrollé un sistema web de gestión de valoración de habilidades durante una residencia de 6
                      meses.
                    </p>
                    <p class="mt-2">
                      Este proyecto me permitió adquirir experiencia práctica en el uso de librerías, componentes y
                      bases de datos relacionales, así como en la gestión de bases de datos, control de versiones
                      (Git) y planificación de diseño.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
      <div class="mt-16">
        <section id="proyectos" class="py-16">
          <h2 class="text-3xl font-bold mb-8 text-center">Proyectos</h2>
          <div class="container mx-auto px-40">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-8">
              <div class="bg-white rounded-lg shadow-md p-4">
                <h5 class="font-medium">Laravel Lista de Compras</h5>
                <div class="flex space-x-2 mt-2"> <span
                    class="inline-flex items-center rounded-md bg-gray-200 px-2 py-1 text-xs font-medium text-gray-700">Laravel</span>
                  <span
                    class="inline-flex items-center rounded-md bg-blue-100 px-2 py-1 text-xs font-medium text-blue-700">Tailwind
                    CSS</span>
                  <span
                    class="inline-flex items-center rounded-md bg-green-100 px-2 py-1 text-xs font-medium text-green-700">MySQL</span>
                </div>
                <ul>
                  Desarrollé una intuitiva lista de compras digital con Laravel y Livewire, potenciada por el diseño
                  ágil de Tailwind CSS y la robustez de MySQL.
                </ul>
                <a href="https://github.com/Pedro-UP/LarevlApi.git" class="text-blue-500">Ver Mas</a>
              </div>
              <div class="bg-white rounded-lg shadow-md p-4">
                <h5 class="font-medium">Recetas de Cocina Web</h5>
                <div class="flex space-x-2 mt-2"> <span
                    class="inline-flex items-center rounded-md bg-gray-200 px-2 py-1 text-xs font-medium text-gray-700">Vue</span>
                  <span
                    class="inline-flex items-center rounded-md bg-blue-100 px-2 py-1 text-xs font-medium text-blue-700">JavaScript</span>
                  <span
                    class="inline-flex items-center rounded-md bg-green-100 px-2 py-1 text-xs font-medium text-green-700">API</span>
                </div>
                <ul>
                  Este sitio web, creado con Vue, ofrece una interfaz para visualizar diferentes platillos, con
                  opciones de búsqueda por categoría o nombre. Utiliza peticiones GET a una API para recuperar los
                  datos.
                </ul>
                <a href="https://recetas-comida-api-453ca2.netlify.app/" class="text-blue-500">Ver Mas</a>
              </div>
              <div class="bg-white rounded-lg shadow-md p-4">
                <h5 class="font-medium">Primera Pagina Web</h5>
                <div class="flex space-x-2 mt-2"> <span
                    class="inline-flex items-center rounded-md bg-gray-200 px-2 py-1 text-xs font-medium text-gray-700">HTML</span>
                  <span
                    class="inline-flex items-center rounded-md bg-blue-100 px-2 py-1 text-xs font-medium text-blue-700">CSS</span>
                </div>
                <ul>
                  Mi primera experiencia en desarrollo web: un sitio publicado en internet donde puse en práctica mis
                  conocimientos de HTML y CSS.
                </ul>
                <a href="https://pedro-up.github.io/PrimerPW/" class="text-blue-500">Ver Mas</a>
              </div>
              <div class="bg-white rounded-lg shadow-md p-4">
                <h5 class="font-medium">Juego del Gato</h5>
                <div class="flex space-x-2 mt-2"> <span
                    class="inline-flex items-center rounded-md bg-gray-200 px-2 py-1 text-xs font-medium text-gray-700">C#</span>
                  <span
                    class="inline-flex items-center rounded-md bg-blue-100 px-2 py-1 text-xs font-medium text-blue-700">Visual
                    Studio</span>
                  <span
                    class="inline-flex items-center rounded-md bg-green-100 px-2 py-1 text-xs font-medium text-green-700">Arrays</span>
                </div>
                <ul>
                  Este juego del gato (tres en raya) se enfoca en la práctica con arreglos en código. Permite partidas
                  locales entre dos jugadores, sin funcionalidad de IA.
                </ul>
                <a href="https://github.com/Pedro-UP/Gato.git" class="text-blue-500">Ver Mas</a>
              </div>
            </div>
          </div>
        </section>
      </div>
      <div class="mt-16">
        <section id="contacto">
          <div class="text-center">
            <h2 class="text-3xl font-bold mb-4">Contacto</h2>
            <p class="mb-8 px-32">
              Actualmente me encuentro enfocado en mi desarrollo profesional dentro del área de Desarrollo Web.
              Si le interesa conectar o explorar posibles colaboraciones en proyectos futuros, no dude en contactarme.
            </p>
          </div>
          <div class="mt-8 flex justify-center">
            <a href="mailto:pedrocazorla03@gmail.com"
              class="bg-blue-500 text-white font-bold py-3 px-6 rounded-full hover:bg-blue-600 transition">
              CONTÁCTAME
            </a>
          </div>
          <div class="flex justify-center space-x-8 pt-8">
            <a href="https://github.com/Pedro-UP" target="_blank" rel="noopener noreferrer">
              <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub"
                class="w-16 h-16 rounded-full">
            </a>
            <a href="https://www.linkedin.com/in/pedro-luis-isidro-cazorla-302911257/" target="_blank"
              rel="noopener noreferrer">
              <img
                src="https://static.vecteezy.com/system/resources/previews/023/986/970/non_2x/linkedin-logo-linkedin-logo-transparent-linkedin-icon-transparent-free-free-png.png"
                alt="LinkedIn" class="w-16 h-16 rounded-full">
            </a>
            <a href="/cv/CVPedro2024.pdf" download>
              <img src="https://cdn-icons-png.flaticon.com/512/345/345609.png" alt="Descargar CV"
                class="w-16 h-16 rounded-full">
            </a>
          </div>
        </section>
      </div>
    </main>
    <footer class="bg-gray-800 text-white">
      <div class="container mx-auto text-center">
        <p>Copyright © 2025 | Developed by Pedro Luis Isidro Cazorla
        </p>
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