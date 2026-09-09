<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glamour Studio & Salon | Sadiqabad, Rawalpindi</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- AOS Animation Library -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body class="bg-slate-50 text-slate-800 font-sans selection:bg-pink-500 selection:text-white">

    <!-- Top Bar -->
    <div class="bg-slate-900 text-slate-300 text-xs py-2 px-6 hidden sm:block">
        <div class="container mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <span><i class="fas fa-map-marker-alt text-pink-500 mr-1"></i> Main Market, Sadiqabad, Rawalpindi</span>
                <span><i class="fas fa-clock text-pink-500 mr-1"></i> Mon-Sun: 10:00 AM - 9:00 PM</span>
            </div>
            <div>
                <span><i class="fas fa-phone-alt text-pink-500 mr-1"></i> +92 300 0000000</span>
            </div>
        </div>
    </div>

    <!-- Header / Navbar -->
    <header class="bg-white/90 backdrop-blur-md shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-black tracking-wider text-slate-900">GLAMOUR<span class="text-pink-600">STUDIO</span></a>
            <nav class="hidden md:flex space-x-8 font-medium text-slate-600">
                <a href="#services" class="hover:text-pink-600 transition">Services</a>
                <a href="#booking" class="hover:text-pink-600 transition">Book Appointment</a>
                <a href="#gallery" class="hover:text-pink-600 transition">Gallery</a>
                <a href="#reviews" class="hover:text-pink-600 transition">Reviews</a>
                <a href="#contact" class="hover:text-pink-600 transition">Location</a>
            </nav>
            <a href="#booking" class="bg-pink-600 text-white px-5 py-2.5 rounded-full font-medium shadow-md shadow-pink-600/30 hover:bg-pink-700 transition transform hover:-translate-y-0.5">Book Now</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-slate-900 text-white py-24 md:py-32 overflow-hidden">
        <div class="absolute inset-0 z-0 opacity-40">
            <img src="https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&q=80&w=1920" alt="Salon Interior" class="w-full h-full object-cover">
        </div>
        <div class="container mx-auto px-6 relative z-10 max-w-4xl text-center" data-aos="fade-up" data-aos-duration="1000">
            <span class="bg-pink-600/30 border border-pink-500 text-pink-300 text-xs uppercase tracking-widest px-4 py-1.5 rounded-full font-semibold mb-6 inline-block">Sadiqabad's Premier Salon</span>
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">Elevate Your Beauty & Style Experience</h1>
            <p class="text-lg md:text-xl text-slate-300 mb-8 max-w-2xl mx-auto">Professional hair styling, advanced skin treatments, and stunning bridal makeovers customized just for you.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#booking" class="bg-pink-600 text-white px-8 py-3.5 rounded-full font-semibold shadow-lg shadow-pink-600/40 hover:bg-pink-700 transition">Schedule Appointment</a>
                <a href="https://wa.me/923000000000" target="_blank" class="bg-emerald-600 text-white px-8 py-3.5 rounded-full font-semibold shadow-lg shadow-emerald-600/40 hover:bg-emerald-700 transition flex items-center justify-center gap-2">
                    <i class="fab fa-whatsapp text-xl"></i> Chat on WhatsApp
                </a>
            </div>
        </div>
    </section>

    <!-- Services Menu & Pricing Dashboard -->
    <section id="services" class="py-20 container mx-auto px-6">
        <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up">
            <h2 class="text-3xl md:text-4xl font-bold mb-4 text-slate-900">Services & Pricing Menu</h2>
            <p class="text-slate-500">Transparent pricing and professional treatments tailored to your needs.</p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8">
            <!-- Category 1: Haircuts -->
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 hover:shadow-xl transition duration-300 group" data-aos="fade-up" data-aos-delay="100">
                <div class="w-12 h-12 bg-pink-50 text-pink-600 rounded-xl flex items-center justify-center text-xl mb-6 group-hover:bg-pink-600 group-hover:text-white transition">
                    <i class="fas fa-cut"></i>
                </div>
                <h3 class="text-xl font-bold mb-6 text-slate-900">Haircuts & Styling</h3>
                <ul class="space-y-4 text-slate-600">
                    <li class="flex justify-between items-center border-b border-slate-100 pb-3">
                        <div>
                            <span class="font-medium block text-slate-800">Signature Haircut</span>
                            <span class="text-xs text-slate-400">30 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 1,500</span>
                    </li>
                    <li class="flex justify-between items-center border-b border-slate-100 pb-3">
                        <div>
                            <span class="font-medium block text-slate-800">Blow Dry & Styling</span>
                            <span class="text-xs text-slate-400">45 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 2,000</span>
                    </li>
                    <li class="flex justify-between items-center">
                        <div>
                            <span class="font-medium block text-slate-800">Keratin Treatment</span>
                            <span class="text-xs text-slate-400">120 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 8,000</span>
                    </li>
                </ul>
            </div>

            <!-- Category 2: Facials -->
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 hover:shadow-xl transition duration-300 group" data-aos="fade-up" data-aos-delay="200">
                <div class="w-12 h-12 bg-pink-50 text-pink-600 rounded-xl flex items-center justify-center text-xl mb-6 group-hover:bg-pink-600 group-hover:text-white transition">
                    <i class="fas fa-spa"></i>
                </div>
                <h3 class="text-xl font-bold mb-6 text-slate-900">Facials & Skin Care</h3>
                <ul class="space-y-4 text-slate-600">
                    <li class="flex justify-between items-center border-b border-slate-100 pb-3">
                        <div>
                            <span class="font-medium block text-slate-800">Glow Facial</span>
                            <span class="text-xs text-slate-400">60 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 3,500</span>
                    </li>
                    <li class="flex justify-between items-center border-b border-slate-100 pb-3">
                        <div>
                            <span class="font-medium block text-slate-800">Hydra Facial</span>
                            <span class="text-xs text-slate-400">75 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 6,000</span>
                    </li>
                    <li class="flex justify-between items-center">
                        <div>
                            <span class="font-medium block text-slate-800">Organic Cleanup</span>
                            <span class="text-xs text-slate-400">40 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 2,000</span>
                    </li>
                </ul>
            </div>

            <!-- Category 3: Packages -->
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-100 hover:shadow-xl transition duration-300 group" data-aos="fade-up" data-aos-delay="300">
                <div class="w-12 h-12 bg-pink-50 text-pink-600 rounded-xl flex items-center justify-center text-xl mb-6 group-hover:bg-pink-600 group-hover:text-white transition">
                    <i class="fas fa-crown"></i>
                </div>
                <h3 class="text-xl font-bold mb-6 text-slate-900">Special Packages</h3>
                <ul class="space-y-4 text-slate-600">
                    <li class="flex justify-between items-center border-b border-slate-100 pb-3">
                        <div>
                            <span class="font-medium block text-slate-800">Party Makeup</span>
                            <span class="text-xs text-slate-400">60 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 5,000</span>
                    </li>
                    <li class="flex justify-between items-center border-b border-slate-100 pb-3">
                        <div>
                            <span class="font-medium block text-slate-800">Bridal Package</span>
                            <span class="text-xs text-slate-400">180 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 35,000</span>
                    </li>
                    <li class="flex justify-between items-center">
                        <div>
                            <span class="font-medium block text-slate-800">Groom Package</span>
                            <span class="text-xs text-slate-400">90 mins</span>
                        </div>
                        <span class="font-bold text-pink-600">Rs. 8,000</span>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Online WhatsApp Booking Form -->
    <section id="booking" class="py-20 bg-pink-50/50">
        <div class="container mx-auto px-6 max-w-2xl bg-white p-8 md:p-12 rounded-3xl shadow-xl border border-pink-100" data-aos="zoom-in">
            <div class="text-center mb-8">
                <h2 class="text-3xl font-bold text-slate-900 mb-2">Book Your Appointment</h2>
                <p class="text-slate-500">Fill out the form below. Your request will be instantly processed via WhatsApp.</p>
            </div>
            
            <form id="whatsappBookingForm" class="space-y-6">
                <div>
                    <label class="block text-sm font-semibold text-slate-700 mb-2">Full Name</label>
                    <input type="text" id="clientName" required class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 focus:outline-none focus:border-pink-600 transition" placeholder="e.g. Ayesha Khan">
                </div>
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-semibold text-slate-700 mb-2">Phone / WhatsApp Number</label>
                        <input type="tel" id="clientPhone" required class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 focus:outline-none focus:border-pink-600 transition" placeholder="0300 1234567">
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-slate-700 mb-2">Select Service</label>
                        <select id="clientService" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 focus:outline-none focus:border-pink-600 transition">
                            <option>Signature Haircut - Rs. 1,500</option>
                            <option>Glow Facial - Rs. 3,500</option>
                            <option>Hydra Facial - Rs. 6,000</option>
                            <option>Party Makeup - Rs. 5,000</option>
                            <option>Bridal Package - Rs. 35,000</option>
                        </select>
                    </div>
                </div>
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-semibold text-slate-700 mb-2">Preferred Stylist</label>
                        <select id="clientStylist" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 focus:outline-none focus:border-pink-600 transition">
                            <option>Any Available Stylist</option>
                            <option>Sana (Senior Beautician)</option>
                            <option>Ali (Master Stylist)</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-slate-700 mb-2">Date & Time</label>
                        <input type="datetime-local" id="clientDateTime" required class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3.5 focus:outline-none focus:border-pink-600 transition">
                    </div>
                </div>
                <button type="submit" class="w-full bg-emerald-600 text-white font-bold py-4 rounded-xl shadow-lg shadow-emerald-600/30 hover:bg-emerald-700 transition flex items-center justify-center gap-2 text-lg">
                    <i class="fab fa-whatsapp text-2xl"></i> Send Booking to WhatsApp
                </button>
            </form>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 container mx-auto px-6">
        <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up">
            <h2 class="text-3xl md:text-4xl font-bold mb-4 text-slate-900">Our Work Gallery</h2>
            <p class="text-slate-500">Explore our signature transformations and styling portfolio.</p>
        </div>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <div class="relative group overflow-hidden rounded-2xl shadow-sm h-64" data-aos="fade-up" data-aos-delay="100">
                <img src="https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?auto=format&fit=crop&q=80&w=600" alt="Hair Styling" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/70 to-transparent opacity-0 group-hover:opacity-100 transition flex items-end p-6">
                    <span class="text-white font-medium text-sm">Hair Styling</span>
                </div>
            </div>
            <div class="relative group overflow-hidden rounded-2xl shadow-sm h-64" data-aos="fade-up" data-aos-delay="200">
                <img src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?auto=format&fit=crop&q=80&w=600" alt="Bridal Makeup" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/70 to-transparent opacity-0 group-hover:opacity-100 transition flex items-end p-6">
                    <span class="text-white font-medium text-sm">Bridal Makeup</span>
                </div>
            </div>
            <div class="relative group overflow-hidden rounded-2xl shadow-sm h-64" data-aos="fade-up" data-aos-delay="300">
                <img src="https://images.unsplash.com/photo-1519699047748-de8e457a634e?auto=format&fit=crop&q=80&w=600" alt="Facial Treatment" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/70 to-transparent opacity-0 group-hover:opacity-100 transition flex items-end p-6">
                    <span class="text-white font-medium text-sm">Skin Treatment</span>
                </div>
            </div>
            <div class="relative group overflow-hidden rounded-2xl shadow-sm h-64" data-aos="fade-up" data-aos-delay="400">
                <img src="https://images.unsplash.com/photo-1562322140-8baeececf3df?auto=format&fit=crop&q=80&w=600" alt="Hair Color" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/70 to-transparent opacity-0 group-hover:opacity-100 transition flex items-end p-6">
                    <span class="text-white font-medium text-sm">Hair Coloring</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Customer Reviews -->
    <section id="reviews" class="py-20 bg-slate-100">
        <div class="container mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-slate-900">What Our Clients Say</h2>
                <p class="text-slate-500">Real feedback from valued customers in Sadiqabad.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-2xl shadow-sm" data-aos="fade-up" data-aos-delay="100">
                    <div class="text-yellow-400 mb-4 space-x-1">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p class="text-slate-600 mb-6">"Amazing service and very professional staff! The haircut and styling exceeded my expectations completely."</p>
                    <span class="font-bold block text-slate-900">Mahnoor Malik</span>
                    <span class="text-xs text-slate-400">Regular Client</span>
                </div>
                <div class="bg-white p-8 rounded-2xl shadow-sm" data-aos="fade-up" data-aos-delay="200">
                    <div class="text-yellow-400 mb-4 space-x-1">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p class="text-slate-600 mb-6">"Got my bridal makeup done here and received countless compliments. Highly recommended in Rawalpindi!"</p>
                    <span class="font-bold block text-slate-900">Zainab Bibi</span>
                    <span class="text-xs text-slate-400">Bridal Client</span>
                </div>
                <div class="bg-white p-8 rounded-2xl shadow-sm" data-aos="fade-up" data-aos-delay="300">
                    <div class="text-yellow-400 mb-4 space-x-1">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p class="text-slate-600 mb-6">"Very clean environment, polite staff, and great hydraulic facial treatment. Will definitely visit again."</p>
                    <span class="font-bold block text-slate-900">Sadia Ahmed</span>
                    <span class="text-xs text-slate-400">Skin Care Client</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Location & Contact -->
    <section id="contact" class="py-24 max-w-7xl mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <div data-aos="fade-right">
                <h2 class="text-3xl md:text-5xl font-bold mb-6">Visit Our Studio</h2>
                <div class="space-y-4 text-zinc-300 mb-8">
                    <p class="flex items-center gap-3"><i class="fas fa-map-marker-alt text-pink-500 text-lg"></i> Main Market, Sadiqabad, Rawalpindi</p>
                    <p class="flex items-center gap-3"><i class="fas fa-clock text-pink-500 text-lg"></i> Monday - Sunday: 10:00 AM - 9:00 PM</p>
                    <p class="flex items-center gap-3"><i class="fas fa-phone-alt text-pink-500 text-lg"></i> +92 300 0000000</p>
                    <p class="flex items-center gap-3"><i class="fas fa-wallet text-pink-500 text-lg"></i> JazzCash / EasyPaisa / Cash Accepted</p>
                </div>
                <a href="https://maps.google.com" target="_blank" class="inline-block bg-zinc-800 hover:bg-zinc-700 text-white font-medium px-6 py-3 rounded-xl border border-zinc-700 transition">Get Google Map Directions</a>
            </div>
            <div class="h-96 rounded-3xl overflow-hidden border border-zinc-800 shadow-2xl bg-zinc-900 flex items-center justify-center text-zinc-500" data-aos="fade-left">
                <!-- Replace with real Google Map iframe -->
                <div class="text-center p-6">
                    <i class="fas fa-map-marked-alt text-4xl text-pink-500 mb-3"></i>
                    <p class="font-medium text-zinc-300">Sadiqabad, Rawalpindi Location Map</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-zinc-950 border-t border-zinc-900 py-8 text-center text-zinc-500 text-sm">
        <p>&copy; 2026 Glamour Studio Sadiqabad. All rights reserved. Crafted for Professional Excellence.</p>
    </footer>

    <!-- AOS Animation Library JS -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            once: true,
            offset: 100,
        });

        // WhatsApp Booking Form Logic
        document.getElementById('whatsappBookingForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('clientName').value;
            const phone = document.getElementById('clientPhone').value;
            const service = document.getElementById('clientService').value;
            const stylist = document.getElementById('clientStylist').value;
            const datetime = document.getElementById('clientDateTime').value;

            // Salon Owner WhatsApp Number (Replace with actual number)
            const salonWhatsAppNumber = "923000000000"; 

            const whatsappMessage = `*New Appointment Request*%0A%0A*Name:* ${name}%0A*Phone:* ${phone}%0A*Service:* ${service}%0A*Stylist:* ${stylist}%0A*Date & Time:* ${datetime}`;

            const whatsappURL = `https://wa.me/${salongWhatsAppNumber}?text=${whatsappMessage}`;
            
            window.open(whatsappURL, '_blank');
        });
    </script>
</body>
</html>
