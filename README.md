<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marvin Academy - Home</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/tsparticles@3.5.0/tsparticles.bundle.min.js"></script>
</head>
<body class="font-sans text-gray-800 bg-gray-100">
    <!-- Navigation Bar -->
    <nav class="bg-blue-600 text-white fixed w-full z-50 shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <a href="index.html" class="text-2xl font-bold">Marvin Academy</a>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="index.html" class="hover:bg-blue-700 px-3 py-2 rounded-md">Home</a>
                    <a href="about.html" class="hover:bg-blue-700 px-3 py-2 rounded-md">About Us</a>
                    <a href="services.html" class="hover:bg-blue-700 px-3 py-2 rounded-md">Services</a>
                    <a href="gallery.html" class="hover:bg-blue-700 px-3 py-2 rounded-md">Gallery</a>
                    <a href="contact.html" class="hover:bg-blue-700 px-3 py-2 rounded-md">Contact Us</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section with Particle Background -->
    <section class="pt-16 bg-blue-600 text-white relative overflow-hidden">
        <div id="tsparticles" class="absolute inset-0 z-0"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 text-center relative z-10">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Welcome to Marvin Academy</h1>
            <p class="text-lg md:text-xl mb-6">Empower your future with our world-class services in technology, business, and marketing.</p>
            <a href="services.html" class="bg-white text-blue-600 px-6 py-3 rounded-md font-semibold hover:bg-gray-200">Explore Services</a>
            <p class="mt-4 text-sm"><a href="https://unsplash.com/photos/5fNmWej4tAA" class="text-white hover:underline" target="_blank">Image by Johannes Plenio on Unsplash</a></p>
        </div>
        <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Hero Image" class="w-full h-64 object-cover relative z-10">
    </section>

    <!-- Featured Services -->
    <section class="py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-12">Featured Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white shadow-lg rounded-lg overflow-hidden">
                    <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3" alt="Python Programming" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Python Programming</h3>
                        <p class="text-gray-600 mb-4">Learn Python from basics to advanced topics like web scraping and automation. <a href="https://unsplash.com/photos/8xAA0f9yQnE" class="text-blue-600 hover:underline" target="_blank">Image by ThisisEngineering on Unsplash</a></p>
                        <p class="text-blue-600 font-semibold">Duration: 8 weeks</p>
                    </div>
                </div>
                <div class="bg-white shadow-lg rounded-lg overflow-hidden">
                    <img src="https://images.pexels.com/photos/1181359/pexels-photo-1181359.jpeg" alt="JavaScript Mastery" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">JavaScript Mastery</h3>
                        <p class="text-gray-600 mb-4">Build dynamic web applications with JavaScript and modern frameworks. <a href="https://www.pexels.com/photo/person-coding-on-laptop-1181359/" class="text-blue-600 hover:underline" target="_blank">Image by Markus Spiske on Pexels</a></p>
                        <p class="text-blue-600 font-semibold">Duration: 10 weeks</p>
                    </div>
                </div>
                <div class="bg-white shadow-lg rounded-lg overflow-hidden">
                    <img src="https://images.pexels.com/photos/3184297/pexels-photo-3184297.jpeg" alt="Project Management" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Project Management</h3>
                        <p class="text-gray-600 mb-4">Master Agile, Scrum, and PMP methodologies for effective project delivery. <a href="https://www.pexels.com/photo/group-of-people-sitting-on-chair-in-front-of-wooden-table-inside-room-3184297/" class="text-blue-600 hover:underline" target="_blank">Image by Proxyclick Visitor Management System on Pexels</a></p>
                        <p class="text-blue-600 font-semibold">Duration: 6 weeks</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="bg-blue-600 text-white py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-4">Ready to Start Learning?</h2>
            <p class="text-lg mb-6">Join Marvin Academy today and take the first step towards a brighter future.</p>
            <a href="contact.html" class="bg-white text-blue-600 px-6 py-3 rounded-md font-semibold hover:bg-gray-200">Get in Touch</a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-lg font-semibold mb-4">Marvin Academy</h3>
                    <p class="text-gray-200">Empowering minds through education since 2015.</p>
                    <p class="text-gray-200 mt-2">Developed by Kaya Marvin</p>
                </div>
                <div>
                    <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="index.html" class="text-gray-200 hover:text-white">Home</a></li>
                        <li><a href="about.html" class="text-gray-200 hover:text-white">About Us</a></li>
                        <li><a href="services.html" class="text-gray-200 hover:text-white">Services</a></li>
                        <li><a href="gallery.html" class="text-gray-200 hover:text-white">Gallery</a></li>
                        <li><a href="contact.html" class="text-gray-200 hover:text-white">Contact Us</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-semibold mb-4">Contact Info</h3>
                    <p class="text-gray-200">123 Learning Lane, Education City, EC 12345</p>
                    <p class="text-gray-200">Email: info@marvinacademy.com</p>
                    <p class="text-gray-200">Phone: (123) 456-7890</p>
                </div>
            </div>
            <div class="mt-8 border-t border-gray-200 pt-4 text-center">
                <p class="text-gray-200">© 2025 Marvin Academy. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- tsParticles Configuration -->
    <script>
        tsParticles.load("tsparticles", {
            particles: {
                number: { value: 100, density: { enable: true, value_area: 800 } },
                shape: { type: ["circle", "triangle", "star"], stroke: { width: 0 } },
                size: { value: 5, random: true, anim: { enable: false } },
                opacity: { value: 0.7, random: true },
                color: { value: ["#ffffff", "#ffcc00", "#00ccff"] },
                move: { enable: true, speed: 2, direction: "none", random: true, straight: false, out_mode: "out" },
                line_linked: { enable: true, distance: 150, color: "#ffffff", opacity: 0.4, width: 1 }
            },
            interactivity: {
                detect_on: "canvas",
                events: { onhover: { enable: true, mode: "repulse" }, onclick: { enable: true, mode: "push" }, resize: true },
                modes: { repulse: { distance: 100, duration: 0.4 }, push: { particles_nb: 4 } }
            },
            retina_detect: true
        });
    </script>
</body>
</html>
