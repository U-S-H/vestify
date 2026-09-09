<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glamour Studio & Salon | Sadiqabad, Rawalpindi</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- AOS Animation Library -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body class="bg-slate-50 text-slate-800 font-sans selection:bg-pink-500 selection:text-white">

    <!-- Top Bar -->
    <div class="bg-slate-900 text-slate-300 text-xs py-2 px-6 hidden sm:flex justify-between items-center">
        <div><i class="fas fa-map-marker-alt text-pink-500 mr-2"></i> Main Sadiqabad Market, Rawalpindi</div>
        <div class="flex items-center gap-4">
            <span><i class="fas fa-clock text-pink-500 mr-1"></i> Open Daily: 10:00 AM - 9:00 PM</span>
            <a href="https://wa.me/923000000000" target="_blank" class="hover:text-pink-400 transition"><i class="fab fa-whatsapp text-green-400"></i> +92 300 0000000</a>
        </div>
    </div>

    <!-- Navigation Bar -->
    <header class="bg-white/90 backdrop-blur-md shadow-sm sticky top-0 z-50 transition-all">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-black tracking-wider text-slate-900">GLAMOUR<span class="text-pink-600">STUDIO</span></a>
            <nav class="hidden md:flex space-x-8 font-medium text-sm">
                <a href="#services" class="hover:text-pink-600 transition">Services</a>
                <a href="#booking" class="hover:text-pink-600 transition">Book Appointment</a>
                <a href="#gallery" class="hover:text-pink-600 transition">Gallery</a>
                <a href="#reviews" class="hover:text-pink-600 transition">Reviews</a>
                <a href="#location" class="hover:text-pink-600 transition">Location</a>
            </nav>
            <a href="#booking" class="bg-gradient-to-r from-pink-600 to-rose-500 text-white px-6 py-2.5 rounded-full text-sm font-semibold shadow-md hover:shadow-pink-500/35 hover:scale-105 transition-all">Book Now</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative min-h-[85vh] flex items-center justify-center bg-slate-900 overflow-hidden">
        <div class="absolute inset-0 z-0 opacity-40">
            <img src="https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&q=80&w=1920" alt="Salon Interior" class="w-full h-full object-cover">
        </div>
        <div class="absolute inset-0 bg-gradient-to-t from-slate-900 via-transparent to-slate-900/60 z-0"></div>

        <div class="container mx-auto px-6 relative z-10 text-center text-white max-w-3xl" data-aos="fade-up" data-aos-duration="1000">
            <span class="bg-pink-600/30 border border-pink-500/50 text-pink-300 text-xs uppercase px-4 py-1.5 rounded-full tracking-widest font-semibold inline-block mb-6">Premier Salon in Sadiqabad</span>
            <h1 class="text-4xl sm:text-6xl font-black tracking-tight mb-6 leading-tight">Elevate Your Look, <br><span class="text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-rose-300">Redefine Your Beauty</span></h1>
            <p class="text-slate-300 text-base sm:text-lg mb-8 max-w-xl mx-auto">Experience professional hair styling, luxury skin care, and flawless bridal transformations tailored just for you.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#booking" class="bg-pink-600 text-white px-8 py-3.5 rounded-full font-bold shadow-lg shadow-pink-600/40 hover:bg-pink-700 transition transform hover:-translate-y-0.5">Book Appointment Online</a>
                <a href="https://wa.me/923000000000?text=Hello,%20I%20want%20to%20inquire%20about%20salon%20services." target="_blank" class="bg-emerald-600 text-white px-8 py-3.5 rounded-full font-bold shadow-lg shadow-emerald-600/40 hover:bg-emerald-700 transition flex items-center justify-center gap-2">
                    <i class="fab fa-whatsapp text-lg"></i> Direct WhatsApp
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 container mx-auto px-6">
        <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up">
            <h2 class="text-3xl sm:text-4xl font-extrabold mb-4">Services & Pricing Menu</h2>
            <p class="text-slate-500">Choose from our premium suite of professional salon treatments.</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
            <!-- Card 1 -->
            <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-slate-100 group" data-aos="fade-up" data-aos-delay="100">
                <div class="w-12 h-12 bg-pink-50 text-pink-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6 group-hover:bg-pink-600 group-hover:text-white transition-colors">
                    <i class="fas fa-cut"></i>
                </div>
                <h3 class="text-xl font-bold mb-4">Haircuts & Styling</h3>
                <ul class="space-y-4 text-sm text-slate-600">
                    <li class="flex justify-between border-b border-slate-100 pb-3">
                        <span>Signature Haircut</span>
                        <span class="font-bold text-slate-900">Rs. 1,500 <span class="text-xs text-slate-400 font-normal">(30m)</span></span>
                    </li>
                    <li class="flex justify-between border-b border-slate-100 pb-3">
                        <span>Blow Dry & Set</span>
                        <span class="font-bold text-slate-900">Rs. 2,000 <span class="text-xs text-slate-400 font-normal">(45m)</span></span>
                    </li>
                    <li class="flex justify-between pb-1">
                        <span>Keratin Treatment</span>
                        <span class="font-bold text-slate-900">Rs. 8,000 <span class="text-xs text-slate-400 font-normal">(120m)</span></span>
                    </li>
                </ul>
            </div>

            <!-- Card 2 -->
            <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-slate-100 group" data-aos="fade-up" data-aos-delay="200">
                <div class="w-12 h-12 bg-pink-50 text-pink-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6 group-hover:bg-pink-600 group-hover:text-white transition-colors">
                    <i class="fas fa-spa"></i>
                </div>
                <h3 class="text-xl font-bold mb-4">Facial & Skin Care</h3>
                <ul class="space-y-4 text-sm text-slate-600">
                    <li class="flex justify-between border-b border-slate-100 pb-3">
                        <span>Organic Cleanup</span>
                        <span class="font-bold text-slate-900">Rs. 2,000 <span class="text-xs text-slate-400 font-normal">(40m)</span></span>
                    </li>
                    <li class="flex justify-between border-b border-slate-100 pb-3">
                        <span>Glow Facial Treatment</span>
                        <span class="font-bold text-slate-900">Rs. 3,500 <span class="text-xs text-slate-400 font-normal">(60m)</span></span>
                    </li>
                    <li class="flex justify-between pb-1">
                        <span>Advanced Hydra Facial</span>
                        <span class="font-bold text-slate-900">Rs. 6,000 <span class="text-xs text-slate-400 font-normal">(75m)</span></span>
                    </li>
                </ul>
            </div>

            <!-- Card 3 -->
            <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-xl transition-all border border-slate-100 group" data-aos="fade-up" data-aos-delay="300">
                <div class="w-12 h-12 bg-pink-50 text-pink-600 rounded-xl flex items-center justify-center text-xl font-bold mb-6 group-hover:bg-pink-600 group-hover:text-white transition-colors">
                    <i class="fas fa-crown"></i>
                </div>
                <h3 class="text-xl font-bold mb-4">Bridal & Party Makeup</h3>
                <ul class="space-y-4 text-sm text-slate-600">
                    <li class="flex justify-between border-b border-slate-100 pb-3">
                        <span>Party Makeup</span>
                        <span class="font-bold text-slate-900">Rs. 5,000 <span class="text-xs text-slate-400 font-normal">(60m)</span></span>
                    </li>
                    <li class="flex justify-between border-b border-slate-100 pb-3">
                        <span>Groom Grooming</span>
                        <span class="font-bold text-slate-900">Rs. 8,000 <span class="text-xs text-slate-400 font-normal">(90m)</span></span>
                    </li>
                    <li class="flex justify-between pb-1">
                        <span>Bridal Package Complete</span>
                        <span class="font-bold text-slate-900">Rs. 35,000 <span class="text-xs text-slate-400 font-normal">(180m)</span></span>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Smart WhatsApp Booking Section -->
    <section id="booking" class="py-24 bg-gradient-to-b from-slate-100 to-pink-50/50">
        <div class="container mx-auto px-6 max-w-xl">
            <div class="bg-white rounded-3xl p-8 sm:p-10 shadow-xl border border-slate-100" data-aos="zoom-in">
                <div class="text-center mb-8">
                    <span class="text-pink-600 font-semibold text-xs tracking-widest uppercase bg-pink-50 px-3 py-1 rounded-full">Instant Reservation</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold mt-3">Book Your Appointment</h2>
                    <p class="text-slate-500 text-sm mt-1">Fill out the form below. Details will be sent directly to our WhatsApp booking desk.</p>
                </div>

                <form id="whatsappBookingForm" class="space-y-5">
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-2">Full Name</label>
                        <input type="text" id="clientName" required class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-pink-600 focus:bg-white transition-all" placeholder="e.g. Ayesha Khan">
                    </div>

                    <div class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-2">Phone Number</label>
                            <input type="tel" id="clientPhone" required class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-pink-600 focus:bg-white transition-all" placeholder="0300 1234567">
                        </div>
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-2">Select Service</label>
                            <select id="clientService" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-pink-600 focus:bg-white transition-all">
                                <option>Signature Haircut</option>
                                <option>Blow Dry & Set</option>
                                <option>Organic Cleanup</option>
                                <option>Glow Facial Treatment</option>
                                <option>Advanced Hydra Facial</option>
                                <option>Party Makeup</option>
                                <option>Bridal Package Complete</option>
                            </select>
                        </div>
                    </div>

                    <div class="grid sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-2">Preferred Stylist</label>
                            <select id="clientStylist" class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-pink-600 focus:bg-white transition-all">
                                <option>Any Available Stylist</option>
                                <option>Sana (Senior Beautician)</option>
                                <option>Ali (Master Stylist)</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-2">Date & Time</label>
                            <input type="datetime-local" id="clientDateTime" required class="w-full bg-slate-50 border border-slate-200 rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-pink-600 focus:bg-white transition-all">
                        </div>
                    </div>

                    <button type="submit" class="w-full bg-emerald-600 text-white font-bold py-4 rounded-xl shadow-lg shadow-emerald-600/30 hover:bg-emerald-700 transition-all flex items-center justify-center gap-2 mt-4">
                        <i class="fab fa-whatsapp text-xl"></i> Confirm via WhatsApp
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-24 container mx-auto px-6">
        <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up">
            <h2 class="text-3xl sm:text-4xl font-extrabold mb-4">Our Work Portfolio</h2>
            <p class="text-slate-500">A glimpse into our recent makeovers and salon studio atmosphere.</p>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <div class="relative group overflow-hidden rounded-2xl aspect-square shadow-sm" data-aos="fade-up" data-aos-delay="100">
                <img src="https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?auto=format&fit=crop&q=80&w=600" alt="Hair Styling" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/80 via-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                    <span class="text-white font-semibold text-sm">Professional Styling</span>
                </div>
            </div>
            <div class="relative group overflow-hidden rounded-2xl aspect-square shadow-sm" data-aos="fade-up" data-aos-delay="200">
                <img src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?auto=format&fit=crop&q=80&w=600" alt="Makeup" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/80 via-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                    <span class="text-white font-semibold text-sm">Bridal Makeup</span>
                </div>
            </div>
            <div class="relative group overflow-hidden rounded-2xl aspect-square shadow-sm" data-aos="fade-up" data-aos-delay="300">
                <img src="https://images.unsplash.com/photo-1512290900672-1baf204481b2?auto=format&fit=crop&q=80&w=600" alt="Skin Care" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/80 via-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                    <span class="text-white font-semibold text-sm">Hydra Facial</span>
                </div>
            </div>
            <div class="relative group overflow-hidden rounded-2xl aspect-square shadow-sm" data-aos="fade-up" data-aos-delay="400">
                <img src="https://images.unsplash.com/photo-1562322140-8baeececf3df?auto=format&fit=crop&q=80&w=600" alt="Hair Color" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/80 via-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                    <span class="text-white font-semibold text-sm">Color Treatments</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section id="reviews" class="py-24 bg-slate-100">
        <div class="container mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up">
                <h2 class="text-3xl sm:text-4xl font-extrabold mb-4">Customer Testimonials</h2>
                <p class="text-slate-500">What our valued clients say about our services in Sadiqabad.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-200/60" data-aos="fade-up" data-aos-delay="100">
                    <div class="text-amber-400 mb-4 space-x-1">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p class="text-slate-600 text-sm mb-6 leading-relaxed">"Best salon experience in Rawalpindi! The staff is extremely professional, and the bridal makeup was absolutely flawless."</p>
                    <div class="font-bold text-slate-900 text-sm">Mahnoor Tariq</div>
                </div>

                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-200/60" data-aos="fade-up" data-aos-delay="200">
                    <div class="text-amber-400 mb-4 space-x-1">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p class="text-slate-600 text-sm mb-6 leading-relaxed">"I regularly visit for their haircut and facial treatments. Highly hygienic environment and great customer service."</p>
                    <div class="font-bold text-slate-900 text-sm">Zainab Malik</div>
                </div>

                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-200/60" data-aos="fade-up" data-aos-delay="300">
                    <div class="text-amber-400 mb-4 space-x-1">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p class="text-slate-600 text-sm mb-6 leading-relaxed">"Booking through their website was so smooth, and getting confirmation instantly on WhatsApp made it super easy!"</p>
                    <div class="font-bold text-slate-900 text-sm">Sobia Batool</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Location & Contact -->
    <section id="location" class="py-24 container mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <div data-aos="fade-right">
                <span class="text-pink-600 font-semibold text-xs tracking-widest uppercase bg-pink-50 px-3 py-1 rounded-full">Find Us</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold mt-3 mb-6">Visit Our Studio</h2>
                <div class="space-y-4 text-slate-600 text-sm mb-8">
                    <p class="flex items-start gap-3"><i class="fas fa-map-marker-alt text-pink-600 text-lg mt-1"></i> Main Sadiqabad Market, Near Commercial Area, Rawalpindi</p>
                    <p class="flex items-center gap-3"><i class="fas fa-clock text-pink-600 text-lg"></i> Monday to Sunday: 10:00 AM - 9:00 PM</p>
                    <p class="flex items-center gap-3"><i class="fas fa-phone-alt text-pink-600 text-lg"></i> +92 300 0000000</p>
                </div>
                <div class="inline-block bg-slate-900 text-white px-6 py-3 rounded-xl text-xs font-semibold tracking-wider">
                    Payment Methods: Cash / JazzCash / EasyPaisa Accepted
                </div>
            </div>
            <div class="h-96 bg-slate-200 rounded-2xl overflow-hidden shadow-inner flex items-center justify-center text-slate-500 font-medium relative" data-aos="fade-left">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d13318.5!2d73.06!3d33.64!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzPCsDM4JzI0LjAiTiA3M8KwMDMnMzYuMCJF!5e0!3m2!1sen!2spk!4v1650000000000!5m2!1sen!2spk" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="container mx-auto px-6 text-center text-sm space-y-2">
            <p>&copy; 2026 Glamour Studio Sadiqabad. All rights reserved.</p>
            <p class="text-xs text-slate-500 font-medium tracking-wide">
                Powered by <span class="text-pink-500 font-semibold">Prime Solutions</span> &bull; Developed by <span class="text-slate-300 font-semibold">Muhammad Nazim</span>
            </p>
        </div>
    </footer>

    <!-- AOS Animation Script -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            once: true,
            offset: 50,
            duration: 800
        });

        // WhatsApp Form Integration Script
        document.getElementById('whatsappBookingForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('clientName').value;
            const phone = document.getElementById('clientPhone').value;
            const service = document.getElementById('clientService').value;
            const stylist = document.getElementById('clientStylist').value;
            const datetime = document.getElementById('clientDateTime').value;

            // Salon Owner WhatsApp Number
            const ownerWhatsApp = "923000000000"; 

            const message = `*New Appointment Request*%0A%0A*Name:* ${name}%0A*Phone:* ${phone}%0A*Service:* ${service}%0A*Stylist:* ${stylist}%0A*Date & Time:* ${datetime}`;

            window.open(`https://wa.me/${ownerWhatsApp}?text=${message}`, '_blank');
        });
    </script>
</body>
</html>
