<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículum de Luciano Budman</title>
    <!-- Incluye Tailwind CSS para un diseño moderno y responsivo -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Incluye Font Awesome para iconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- Incluye Google Fonts para la tipografía Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #374151;
        }
    </style>
</head>
<body class="bg-gray-100 p-4 sm:p-8 md:p-12 lg:p-16">

    <!-- Contenedor Principal con Sombra y Esquinas Redondeadas -->
    <div class="max-w-4xl mx-auto bg-white shadow-2xl rounded-3xl overflow-hidden transform transition-all duration-500">
        <!-- Encabezado con Nombre, Título y un Degradado Vistoso -->
        <header class="relative bg-gray-900 text-white p-8 md:p-12 lg:p-16 text-center rounded-t-3xl">
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold tracking-tight mb-2">
                Luciano Budman
            </h1>
            <h2 class="text-lg sm:text-xl lg:text-2xl font-light text-gray-300">
                Profesional en Tecnología y Desarrollo
            </h2>
            <div class="absolute bottom-0 left-0 right-0 h-4 bg-gradient-to-r from-teal-500 via-sky-500 to-indigo-500"></div>
        </header>

        <!-- Sección de Perfil y Contacto -->
        <section class="p-6 md:p-8 lg:p-10 flex flex-col md:flex-row items-center md:items-start gap-8">
            <!-- Espacio para la foto de perfil -->
            <div class="flex-shrink-0 w-32 h-32 md:w-40 md:h-40 bg-gray-200 rounded-full overflow-hidden shadow-lg">
                <!-- Imagen de perfil (placeholder) -->
                <img src="https://placehold.co/160x160/9ca3af/ffffff?text=Tu+Foto" alt="Foto de perfil" class="w-full h-full object-cover">
            </div>
            <!-- Resumen Profesional y Datos de Contacto -->
            <div class="flex-grow text-center md:text-left">
                <p class="text-gray-600 mb-4 text-sm sm:text-base leading-relaxed">
                    Estudiante técnico proactivo y orientado a la resolución de problemas, con una sólida base en el área de la computación. Apasionado por la tecnología y el aprendizaje continuo, he desarrollado habilidades en diversas áreas, incluyendo el manejo de software, programación y la gestión de proyectos. Mi capacidad para adaptarme rápidamente a nuevos entornos y mi gran iniciativa me permiten enfrentar desafíos con confianza, buscando contribuir de manera efectiva en cualquier equipo de trabajo.
                </p>
                <!-- Iconos de Contacto con Enlaces -->
                <div class="flex flex-col sm:flex-row items-center justify-center md:justify-start gap-4 text-gray-500 mt-4">
                    <div class="flex items-center gap-2">
                        <i class="fas fa-map-marker-alt text-teal-500"></i>
                        <span class="text-sm">Villa Urquiza, CABA</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fas fa-envelope text-sky-500"></i>
                        <span class="text-sm">lucianobudman2005@gmail.com</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fas fa-phone-alt text-indigo-500"></i>
                        <span class="text-sm">+54 9 11 6954 0365</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contenedor para las Secciones de Contenido (Educación, Habilidades, Cursos) -->
        <div class="p-6 md:p-8 lg:p-10 grid grid-cols-1 md:grid-cols-2 gap-8">

            <!-- Sección de Educación -->
            <div class="bg-gray-50 p-6 rounded-2xl shadow-md border border-gray-200 hover:shadow-lg transition-shadow duration-300">
                <h3 class="text-2xl font-semibold mb-4 border-b-2 border-teal-500 pb-2 text-gray-800">Educación</h3>
                <div class="mb-4">
                    <h4 class="font-bold text-gray-700">Bachillerato Técnico en Computación</h4>
                    <p class="text-sm text-gray-500">Escuela Técnica 32 Gral. José de San Martín</p>
                    <p class="text-xs text-gray-400 mt-1">Marzo 2017 - Diciembre 2023</p>
                    <ul class="list-disc list-inside mt-2 text-sm text-gray-600">
                        <li>Enfoque en la resolución de problemas y el pensamiento lógico.</li>
                        <li>Adquirí una base sólida en conceptos de programación y sistemas informáticos.</li>
                    </ul>
                </div>
            </div>

            <!-- Sección de Habilidades -->
            <div class="bg-gray-50 p-6 rounded-2xl shadow-md border border-gray-200 hover:shadow-lg transition-shadow duration-300">
                <h3 class="text-2xl font-semibold mb-4 border-b-2 border-sky-500 pb-2 text-gray-800">Habilidades Clave</h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm text-gray-600">
                    <div>
                        <h4 class="font-medium text-gray-700 mb-1">Software y Herramientas</h4>
                        <ul class="list-disc list-inside ml-2">
                            <li>Microsoft Office</li>
                            <li>Google Sheets</li>
                            <li>Visual Studio</li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="font-medium text-gray-700 mb-1">Habilidades Técnicas</h4>
                        <ul class="list-disc list-inside ml-2">
                            <li>Java, Python, C++</li>
                            <li>HTML, JavaScript</li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="font-medium text-gray-700 mb-1">Habilidades Interpersonales</h4>
                        <ul class="list-disc list-inside ml-2">
                            <li>Trabajo en equipo</li>
                            <li>Resolución de Problemas</li>
                            <li>Iniciativa</li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="font-medium text-gray-700 mb-1">Idiomas</h4>
                        <ul class="list-disc list-inside ml-2">
                            <li>Español (Nativo)</li>
                            <li>Inglés (Básico)</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Sección de Cursos -->
            <div class="col-span-1 md:col-span-2 bg-gray-50 p-6 rounded-2xl shadow-md border border-gray-200 hover:shadow-lg transition-shadow duration-300">
                <h3 class="text-2xl font-semibold mb-4 border-b-2 border-indigo-500 pb-2 text-gray-800">Cursos y Certificaciones</h3>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-x-8 gap-y-4">
                    <div>
                        <h4 class="font-bold text-gray-700">Desarrollo de Videojuegos con Unity</h4>
                        <p class="text-sm text-gray-500">Gobierno de la Ciudad de Bs. As.</p>
                        <p class="text-xs text-gray-400 mt-1">Enero 2023</p>
                    </div>
                    <div>
                        <h4 class="font-bold text-gray-700">Robótica</h4>
                        <p class="text-sm text-gray-500">Universidad Tecnológica Nacional (UTN)</p>
                        <p class="text-xs text-gray-400 mt-1">Diciembre 2022</p>
                    </div>
                </div>
            </div>

        </div>

        <!-- Pie de Página -->
        <footer class="p-6 text-center text-xs text-gray-500 bg-gray-200 rounded-b-3xl">
            Creado con ❤️ y Tailwind CSS
        </footer>

    </div>

</body>
</html>
