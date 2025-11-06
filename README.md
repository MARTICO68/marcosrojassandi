<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Germán Adrián Vargas Álvarez — Portafolio</title>
  <meta name="description" content="Portafolio profesional — Germán Adrián Vargas Álvarez (Ingeniero en Sistemas)">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .skill-bar { background: #e6e6e6; height: 8px; border-radius: 999px; }
    .skill-fill { height: 8px; border-radius: 999px; }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased">

  <!-- NAV -->
  <header class="bg-white shadow-sm sticky top-0 z-40">
    <div class="max-w-5xl mx-auto px-4 py-4 flex items-center justify-between">
      <a href="#" class="font-bold text-lg">Germán A. Vargas</a>
      <nav class="hidden md:flex gap-6 text-sm">
        <a href="#sobre" class="hover:text-indigo-600">Sobre mí</a>
        <a href="#skills" class="hover:text-indigo-600">Skills</a>
        <a href="#experiencia" class="hover:text-indigo-600">Experiencia</a>
        <a href="#portfolio" class="hover:text-indigo-600">Portafolio</a>
        <a href="#contacto" class="hover:text-indigo-600">Contacto</a>
      </nav>

      <button id="btn-menu" class="md:hidden p-2 rounded hover:bg-gray-100">
        <svg id="icon-menu" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none"
             viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round"
             stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
      </button>
    </div>

    <div id="mobile-menu" class="md:hidden hidden border-t">
      <div class="px-4 py-3 space-y-2">
        <a href="#sobre" class="block">Sobre mí</a>
        <a href="#skills" class="block">Skills</a>
        <a href="#experiencia" class="block">Experiencia</a>
        <a href="#portfolio" class="block">Portafolio</a>
        <a href="#contacto" class="block">Contacto</a>
      </div>
    </div>
  </header>

  <!-- MAIN -->
  <main class="max-w-5xl mx-auto px-4 py-10">
    <!-- HERO -->
    <section class="grid md:grid-cols-3 gap-6 items-center">
      <div class="md:col-span-2">
        <h1 class="text-4xl font-extrabold mb-2">Germán Adrián Vargas Álvarez</h1>
        <p class="text-indigo-600 font-semibold mb-4">Ingeniero en Sistemas — Desarrollo web & Automatización</p>
        <p class="text-gray-600">Soy ingeniero en sistemas con experiencia en desarrollo de aplicaciones web, bases de datos y automatización de procesos. Me enfoco en entregar soluciones sólidas, optimizadas y fáciles de mantener.</p>

        <div class="mt-6 flex gap-3">
          <a href="#contacto" class="px-4 py-2 bg-indigo-600 text-white rounded shadow-sm">Contactar</a>
          <a href="CV.pdf" target="_blank" class="px-4 py-2 border rounded">Descargar CV (PDF)</a>
        </div>
      </div>

      <div class="flex justify-center md:justify-end">
        <!-- REEMPLAZAR: coloca aquí tu foto como 'foto.jpg' en el repo -->
        <img src="foto.jpg" alt="Foto Germán" class="w-44 h-44 rounded-full object-cover shadow-md">
      </div>
    </section>

    <!-- SOBRE -->
    <section id="sobre" class="mt-12 bg-white rounded-lg p-6 shadow-sm">
      <h2 class="text-2xl font-bold mb-3">Sobre mí</h2>
      <p class="text-gray-700">Ingeniero en Sistemas con interés en desarrollo full-stack, bases de datos y soluciones para redes y servicios. Me caracterizo por la atención al detalle, capacidad de aprendizaje rápido y trabajo en equipo.</p>

      <div class="mt-4 grid md:grid-cols-3 gap-3 text-sm text-gray-700">
        <div><strong>Fecha de nacimiento:</strong> 17/01/2001</div>
        <div><strong>Teléfono:</strong> ‪(+506) 8604-2552‬</div>
        <div><strong>Ubicación:</strong> Pérez Zeledón, Costa Rica</div>
      </div>
    </section>

    <!-- SKILLS -->
    <section id="skills" class="mt-8">
      <h2 class="text-2xl font-bold mb-4">Skills</h2>

      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-white p-4 rounded shadow-sm">
          <h3 class="font-semibold mb-3">Técnicas</h3>

          <div class="mb-3">
            <div class="flex justify-between text-sm mb-1"><span>HTML & CSS</span><span>85%</span></div>
            <div class="skill-bar"><div class="skill-fill bg-indigo-600" style="width:85%"></div></div>
          </div>

          <div class="mb-3">
            <div class="flex justify-between text-sm mb-1"><span>JavaScript</span><span>60%</span></div>
            <div class="skill-bar"><div class="skill-fill bg-indigo-600" style="width:60%"></div></div>
          </div>

          <div class="mb-3">
            <div class="flex justify-between text-sm mb-1"><span>SQL</span><span>75%</span></div>
            <div class="skill-bar"><div class="skill-fill bg-indigo-600" style="width:75%"></div></div>
          </div>
        </div>

        <div class="bg-white p-4 rounded shadow-sm">
          <h3 class="font-semibold mb-3">Profesionales</h3>
          <div class="mb-3">
            <div class="flex justify-between text-sm mb-1"><span>Comunicación</span><span>90%</span></div>
            <div class="skill-bar"><div class="skill-fill bg-green-500" style="width:90%"></div></div>
          </div>
          <div class="mb-3">
            <div class="flex justify-between text-sm mb-1"><span>Trabajo en equipo</span><span>85%</span></div>
            <div class="skill-bar"><div class="skill-fill bg-green-500" style="width:85%"></div></div>
          </div>
          <div class="mt-4 text-sm text-gray-600">
            <strong>Herramientas:</strong> Git, VS Code, MySQL, Postgres, Tailwind CSS
          </div>
        </div>
      </div>
    </section>

    <!-- EXPERIENCIA -->
    <section id="experiencia" class="mt-8 bg-white p-6 rounded shadow-sm">
      <h2 class="text-2xl font-bold mb-3">Experiencia</h2>

      <div class="space-y-4">
        <div>
          <div class="flex justify-between items-start">
            <div>
              <h3 class="font-semibold">Ingeniero en Sistemas — Proyectos freelance</h3>
              <div class="text-sm text-gray-600">Desarrollo web, bases de datos y automatización</div>
            </div>
            <div class="text-sm text-gray-500">2022 — Presente</div>
          </div>
          <p class="mt-2 text-gray-700 text-sm">Desarrollo de sitios web, integración de API, optimización de bases de datos y soluciones a medida para clientes pequeños y medianos.</p>
        </div>

        <div>
          <div class="flex justify-between items-start">
            <div>
              <h3 class="font-semibold">Asistente Técnico / Soporte (proyectos académicos)</h3>
              <div class="text-sm text-gray-600">Implementación de redes y mantenimiento</div>
            </div>
            <div class="text-sm text-gray-500">2020 — 2022</div>
          </div>
          <p class="mt-2 text-gray-700 text-sm">Instalación y configuración de equipos de red, resolución de incidencias y soporte al usuario final.</p>
        </div>
      </div>
    </section>

    <!-- PORTFOLIO -->
    <section id="portfolio" class="mt-8">
      <h2 class="text-2xl font-bold mb-4">Portafolio</h2>
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
        <a class="block bg-white rounded shadow-sm overflow-hidden" href="#" target="_blank">
          <img src="https://via.placeholder.com/600x300" class="w-full h-40 object-cover" alt="">
          <div class="p-3">
            <h4 class="font-semibold">Sitio Web — Librería</h4>
            <p class="text-sm text-gray-600">HTML/CSS/PHP — E-commerce básico</p>
          </div>
        </a>

        <a class="block bg-white rounded shadow-sm overflow-hidden" href="#">
          <img src="https://via.placeholder.com/600x300" class="w-full h-40 object-cover" alt="">
          <div class="p-3">
            <h4 class="font-semibold">Sistema de Ventas</h4>
            <p class="text-sm text-gray-600">C# / MySQL — Punto de venta</p>
          </div>
        </a>

        <a class="block bg-white rounded shadow-sm overflow-hidden" href="#">
          <img src="https://via.placeholder.com/600x300" class="w-full h-40 object-cover" alt="">
          <div class="p-3">
            <h4 class="font-semibold">Automatización</h4>
            <p class="text-sm text-gray-600">Scripts de automatización y tareas programadas</p>
          </div>
        </a>
      </div>
    </section>

    <!-- CONTACTO -->
    <section id="contacto" class="mt-8 bg-white p-6 rounded shadow-sm">
      <h2 class="text-2xl font-bold mb-3">Contacto</h2>
      <p class="text-gray-700 mb-4">Si querés contactarme para proyectos o consultas, escribime por correo o por teléfono.</p>

      <div class="grid md:grid-cols-2 gap-4">
        <form action="mailto:germanvar12@gmail.com" method="post" enctype="text/plain" class="space-y-3">
          <input name="Nombre" required class="w-full p-3 border rounded" placeholder="Tu nombre">
          <input name="Correo" required class="w-full p-3 border rounded" placeholder="Tu correo">
          <textarea name="Mensaje" required class="w-full p-3 border rounded" rows="4" placeholder="Mensaje"></textarea>
          <button type="submit" class="px-4 py-2 bg-indigo-600 text-white rounded">Enviar mensaje</button>
        </form>

        <div class="text-sm text-gray-700 space-y-2">
          <div><strong>Teléfono:</strong> (+506) 8604-2552</div>
          <div><strong>Email:</strong> <a href="mailto:germanvar12@gmail.com" class="text-indigo-600">germanvar12@gmail.com</a></div>
          <div><strong>Ubicación:</strong> Pérez Zeledón, Costa Rica</div>
          <div class="pt-3"><a href="CV.pdf" target="_blank" class="px-4 py-2 border rounded inline-block">Descargar CV (PDF)</a></div>
        </div>
      </div>
    </section>

    <footer class="mt-10 text-center text-sm text-gray-500 pb-8">
      © 2025 Germán A. Vargas — Todos los derechos reservados
    </footer>
  </main>

  <script>
    // Toggle menu
    const btn = document.getElementById('btn-menu');
    const menu = document.getElementById('mobile-menu');
    btn.addEventListener('click', () => menu.classList.toggle('hidden'));
    // Smooth anchors
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        e.preventDefault();
        const id = a.getAttribute('href');
        if(id.length>1) document.querySelector(id).scrollIntoView({behavior:'smooth'});
        menu.classList.add('hidden');
      })
    });
  </script>

</body>
</html>
