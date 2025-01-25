<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Landing page para una cámara de seguridad con panel solar: protección, ahorro energético y control inteligente">
    <title>Cámara Solar | Protección Inteligente</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        /* Personalización adicional */
        body {
            font-family: 'Arial', sans-serif;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x800') center/cover no-repeat;
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header / Hero Section -->
    <header class="hero text-white h-screen flex flex-col justify-center items-center text-center px-4">
        <h1 class="text-4xl font-bold md:text-6xl">Seguridad 24/7 con Energía Solar</h1>
        <p class="mt-4 text-lg md:text-xl">Ahorra energía, cuida el medio ambiente y protege tu hogar o negocio desde cualquier lugar.</p>
        <a href="#comprar" class="mt-6 bg-yellow-500 text-black px-6 py-3 rounded-lg text-lg font-semibold shadow hover:bg-yellow-400">Comprar Ahora por S/300</a>
    </header>

    <!-- Beneficios Principales -->
    <section class="py-16 px-6 bg-white text-center">
        <h2 class="text-3xl font-bold">Beneficios Principales</h2>
        <div class="mt-10 grid md:grid-cols-4 gap-8">
            <div class="bg-gray-100 p-6 rounded-lg shadow">
                <img src="https://via.placeholder.com/80" alt="Energía Solar" class="mx-auto">
                <h3 class="mt-4 font-semibold text-lg">Energía Solar</h3>
                <p>Ahorro garantizado, sin necesidad de electricidad.</p>
            </div>
            <div class="bg-gray-100 p-6 rounded-lg shadow">
                <img src="https://via.placeholder.com/80" alt="Visión Nocturna" class="mx-auto">
                <h3 class="mt-4 font-semibold text-lg">Visión Nocturna</h3>
                <p>Protección incluso en la oscuridad más total.</p>
            </div>
            <div class="bg-gray-100 p-6 rounded-lg shadow">
                <img src="https://via.placeholder.com/80" alt="Control Remoto" class="mx-auto">
                <h3 class="mt-4 font-semibold text-lg">Control Remoto</h3>
                <p>Accede a la cámara desde tu celular en cualquier momento.</p>
            </div>
            <div class="bg-gray-100 p-6 rounded-lg shadow">
                <img src="https://via.placeholder.com/80" alt="Fácil Instalación" class="mx-auto">
                <h3 class="mt-4 font-semibold text-lg">Fácil Instalación</h3>
                <p>Sin cables ni complicaciones técnicas.</p>
            </div>
        </div>
    </section>

    <!-- Características Técnicas -->
    <section class="py-16 px-6 bg-gray-50">
        <h2 class="text-3xl font-bold text-center">Características Técnicas</h2>
        <ul class="mt-10 max-w-4xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-4">
            <li class="bg-white p-4 rounded-lg shadow">📹 <strong>Resolución:</strong> 1080p Full HD</li>
            <li class="bg-white p-4 rounded-lg shadow">🔋 <strong>Autonomía:</strong> Hasta 48 horas con batería cargada</li>
            <li class="bg-white p-4 rounded-lg shadow">🌦️ <strong>Resistencia:</strong> Soporta lluvia, polvo y calor extremo</li>
            <li class="bg-white p-4 rounded-lg shadow">📡 <strong>Conectividad:</strong> Wi-Fi y app móvil (Android/iOS)</li>
        </ul>
    </section>

    <!-- Testimonios -->
    <section class="py-16 px-6 bg-white text-center">
        <h2 class="text-3xl font-bold">Lo Que Dicen Nuestros Clientes</h2>
        <div class="mt-10 grid md:grid-cols-2 gap-8">
            <div class="bg-gray-100 p-6 rounded-lg shadow">
                <p class="italic">"Compré esta cámara para mi tienda, y desde entonces puedo ver todo desde mi celular. Ahorro en luz y la instalación fue rapidísima."</p>
                <p class="mt-4 font-semibold">— Juan Carlos, Lima</p>
            </div>
            <div class="bg-gray-100 p-6 rounded-lg shadow">
                <p class="italic">"La cámara es perfecta para mi casa de campo. No necesito cables y puedo vigilar a distancia en cualquier momento."</p>
                <p class="mt-4 font-semibold">— Rosa María, Arequipa</p>
            </div>
        </div>
    </section>

    <!-- CTA Final -->
    <section id="comprar" class="py-16 px-6 bg-yellow-100 text-center">
        <h2 class="text-3xl font-bold">Empieza a Proteger tu Hogar Hoy</h2>
        <p class="mt-4 text-lg">Compra ahora por S/300 y obtén envío GRATIS a todo el Perú.</p>
        <a href="#" class="mt-6 inline-block bg-yellow-500 text-black px-6 py-3 rounded-lg text-lg font-semibold shadow hover:bg-yellow-400">Comprar Ahora</a>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-gray-800 text-white text-center">
        <p>&copy; 2025 Cámara Solar | Todos los derechos reservados</p>
        <nav class="mt-4">
            <a href="#" class="text-gray-400 hover:text-white mx-2">Términos y Condiciones</a>
            <a href="#" class="text-gray-400 hover:text-white mx-2">Política de Privacidad</a>
        </nav>
    </footer>

</body>
</html>
