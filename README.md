<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Safi's Spa & MedSpa | Wuse II, Abuja</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --color-slate: #2C3E50;
            --color-gold: #D4AF37;
            --color-light: #F8F9FA;
            --color-white: #FFFFFF;
        }
        html { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; background-color: var(--color-light); color: var(--color-slate); }
        h1, h2, h3, h4, .serif { font-family: 'Playfair Display', serif; }
        
        .hero-bg {
            background: linear-gradient(to right, rgba(44, 62, 80, 0.85), rgba(44, 62, 80, 0.4)), 
                        url('https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&q=80&w=2070');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .btn-primary {
            background-color: var(--color-gold);
            color: white;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.15em;
            font-weight: 600;
        }
        .btn-primary:hover {
            background-color: #B5952F;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }

        .medspa-card { background: white; border-top: 4px solid var(--color-gold); transition: all 0.4s ease; }
        .medspa-card:hover { box-shadow: 0 20px 40px rgba(0,0,0,0.08); transform: translateY(-5px); }

        .nav-link { position: relative; transition: color 0.3s ease; }
        .nav-link::after {
            content: ''; position: absolute; width: 0; height: 1px;
            bottom: -4px; left: 0; background-color: var(--color-gold);
            transition: width 0.3s ease;
        }
        .nav-link:hover::after { width: 100%; }

        /* Carousel Styles */
        .carousel-track { display: flex; transition: transform 0.5s ease-in-out; }
        .carousel-slide { min-width: 100%; }
    </style>
</head>
<body class="antialiased">

    <nav class="flex justify-between items-center px-6 py-8 md:px-16 absolute w-full z-50 text-white">
        <div class="text-2xl font-bold tracking-[0.3em] uppercase">Safi's</div>
        <div class="hidden lg:flex space-x-8 uppercase text-xs font-medium tracking-[0.2em]">
            <a href="#sanctuary" class="nav-link">Sanctuary</a>
            <a href="#clinical" class="nav-link">MedSpa</a>
            <a href="#gallery" class="nav-link">Gallery</a>
            <a href="#reviews" class="nav-link">Reviews</a>
        </div>
        <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'm%20viewing%20your%20Executive%20Portal.%20I%20would%20like%20to%20request%20a%20concierge%20booking.%0A%0AService:%20[Enter%20Service]%0APreferred%20Date:%20[Enter%20Date]" target="_blank" class="border border-white/50 px-6 py-3 text-xs font-bold uppercase tracking-[0.1em] hover:bg-white hover:text-[--color-slate] transition-colors text-center hidden md:inline-block">Secure a Time</a>
    </nav>

    <section class="hero-bg min-h-screen flex flex-col justify-center px-6 md:px-20 pt-20">
        <div class="max-w-3xl text-white">
            <span class="uppercase tracking-[0.4em] text-xs mb-6 block text-[--color-gold] font-bold">Wuse II, Abuja • Open Until 10 PM</span>
            <h1 class="text-5xl md:text-7xl mb-8 leading-[1.1] font-semibold">
                Abuja’s Best Kept Secret for the <br><span class="italic text-[--color-gold] font-normal">Executive Glow.</span>
            </h1>
            <p class="text-lg md:text-xl font-light leading-relaxed mb-10 text-gray-200 max-w-2xl">
                Experience the sanctuary where luxury meets medical precision. Clinical results, wrapped in absolute serenity.
            </p>
            <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-6">
                <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'm%20viewing%20your%20Executive%20Portal.%20I%20would%20like%20to%20request%20a%20concierge%20booking.%0A%0AService:%20[Enter%20Service]%0APreferred%20Date:%20[Enter%20Date]" target="_blank" class="btn-primary px-10 py-5 text-sm text-center">Book Your Sanctuary</a>
                <a href="#clinical" class="border border-white/30 backdrop-blur-sm px-10 py-5 text-sm uppercase tracking-widest font-medium hover:bg-white/10 text-center transition-colors">View Clinical Menu</a>
            </div>
        </div>
    </section>

    <section id="sanctuary" class="py-24 px-6 md:px-20 bg-white">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 items-center">
            <div class="space-y-8 pr-0 md:pr-12">
                <h2 class="text-4xl md:text-5xl leading-tight text-[--color-slate]">Abuja is fast and demanding. <br><span class="italic font-light text-gray-500">You deserve a space that isn't.</span></h2>
                <div class="w-16 h-1 bg-[--color-gold]"></div>
                <p class="text-gray-600 leading-loose text-lg font-light">
                    At Safi’s Spa, we don’t just provide 'massages'—we offer a total executive reset. From our indoor heated pool to our signature therapies, every minute is designed to help you unplug, recover, and emerge as the best version of yourself.
                </p>
                <div class="flex items-center space-x-4 pt-4 text-sm font-semibold tracking-widest uppercase text-[--color-slate]">
                    <span class="text-[--color-gold]">✔</span> <span>Global Standard Therapists</span>
                </div>
                <div class="flex items-center space-x-4 text-sm font-semibold tracking-widest uppercase text-[--color-slate]">
                    <span class="text-[--color-gold]">✔</span> <span>Late Night Executive Hours (10 PM)</span>
                </div>
            </div>
            <div class="relative">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&q=80&w=1000" alt="Spa Sanctuary" class="w-full h-[500px] object-cover shadow-2xl rounded-sm">
            </div>
        </div>
    </section>

    <footer id="booking" class="bg-[--color-light] text-[--color-slate] pt-24 pb-12 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-6 md:px-20 grid lg:grid-cols-2 gap-16 mb-16">
            <div>
                <h2 class="text-4xl md:text-5xl serif italic mb-8">Ready for the <br>Safi Experience?</h2>
                <div class="space-y-4 mb-10 text-sm opacity-80">
                    <p><strong>Address:</strong> No. 4 Agadez Crescent, Wuse 2, Abuja</p>
                    <p><strong>Direct Line:</strong> 0803 247 0735</p>
                    <p><strong>Hours:</strong> 09:00 AM — 10:00 PM Daily</p>
                </div>
                <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'd%20like%20to%20book%20a%20session." target="_blank" class="btn-primary px-10 py-5 text-sm inline-block shadow-lg">Confirm Booking via WhatsApp</a>
            </div>
            <div class="bg-gray-200 h-[300px] rounded-sm">
                 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3939.851965253818!2d7.472714!3d9.083321!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x104e0a5392e66b8b%3A0xc6222b4676465492!2sAgadez%20Crescent%2C%20Wuse%202%2C%20Abuja!5e0!3m2!1sen!2sng!4v1620000000000!5m2!1sen!2sng" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
        <div class="text-center text-[10px] text-gray-500 tracking-[0.2em] uppercase font-bold border-t border-gray-300 pt-8">
            © 2026 Safi's Spa | Digital Infrastructure by <span class="text-[--color-gold]">Digital Kato</span>
        </div>
    </footer>

</body>
</html>                        url('https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&q=80&w=2070');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .btn-primary {
            background-color: var(--color-gold);
            color: white;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.15em;
            font-weight: 600;
        }
        .btn-primary:hover {
            background-color: #B5952F;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }

        .medspa-card { background: white; border-top: 4px solid var(--color-gold); transition: all 0.4s ease; }
        .medspa-card:hover { box-shadow: 0 20px 40px rgba(0,0,0,0.08); transform: translateY(-5px); }

        .nav-link { position: relative; transition: color 0.3s ease; }
        .nav-link::after {
            content: ''; position: absolute; width: 0; height: 1px;
            bottom: -4px; left: 0; background-color: var(--color-gold);
            transition: width 0.3s ease;
        }
        .nav-link:hover::after { width: 100%; }

        /* Carousel Styles */
        .carousel-track { display: flex; transition: transform 0.5s ease-in-out; }
        .carousel-slide { min-width: 100%; }
        .carousel-btn { transition: all 0.3s ease; }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <nav class="flex justify-between items-center px-6 py-8 md:px-16 absolute w-full z-50 text-white">
        <div class="text-2xl font-bold tracking-[0.3em] uppercase">Safi's</div>
        <div class="hidden lg:flex space-x-8 uppercase text-xs font-medium tracking-[0.2em]">
            <a href="#sanctuary" class="nav-link">Sanctuary</a>
            <a href="#clinical" class="nav-link">MedSpa</a>
            <a href="#gallery" class="nav-link">Gallery</a>
            <a href="#reviews" class="nav-link">Reviews</a>
        </div>
        <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'm%20viewing%20your%20Executive%20Portal.%20I%20would%20like%20to%20request%20a%20concierge%20booking.%0A%0AService:%20[Enter%20Service]%0APreferred%20Date:%20[Enter%20Date]" target="_blank" class="border border-white/50 px-6 py-3 text-xs font-bold uppercase tracking-[0.1em] hover:bg-white hover:text-[--color-slate] transition-colors text-center hidden md:inline-block">Secure a Time</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero-bg min-h-screen flex flex-col justify-center px-6 md:px-20 pt-20">
        <div class="max-w-3xl text-white">
            <span class="uppercase tracking-[0.4em] text-xs mb-6 block text-[--color-gold] font-bold">Wuse II, Abuja • Open Until 10 PM</span>
            <h1 class="text-5xl md:text-7xl mb-8 leading-[1.1] font-semibold">
                Abuja’s Best Kept Secret for the <br><span class="italic text-[--color-gold] font-normal">Executive Glow.</span>
            </h1>
            <p class="text-lg md:text-xl font-light leading-relaxed mb-10 text-gray-200 max-w-2xl">
                Experience the sanctuary where luxury meets medical precision. Clinical results, wrapped in absolute serenity.
            </p>
            <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-6">
                <!-- Primary WhatsApp Booking Link -->
                <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'm%20viewing%20your%20Executive%20Portal.%20I%20would%20like%20to%20request%20a%20concierge%20booking.%0A%0AService:%20[Enter%20Service]%0APreferred%20Date:%20[Enter%20Date]" target="_blank" class="btn-primary px-10 py-5 text-sm text-center">Book Your Sanctuary</a>
                <a href="#clinical" class="border border-white/30 backdrop-blur-sm px-10 py-5 text-sm uppercase tracking-widest font-medium hover:bg-white/10 text-center transition-colors">View Clinical Menu</a>
            </div>
        </div>
    </section>

    <!-- The Hook -->
    <section id="sanctuary" class="py-24 px-6 md:px-20 bg-white">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 items-center">
            <div class="space-y-8 pr-0 md:pr-12">
                <h2 class="text-4xl md:text-5xl leading-tight text-[--color-slate]">Abuja is fast and demanding. <br><span class="italic font-light text-gray-500">You deserve a space that isn't.</span></h2>
                <div class="w-16 h-1 bg-[--color-gold]"></div>
                <p class="text-gray-600 leading-loose text-lg font-light">
                    At Safi’s Spa, we don’t just provide 'massages'—we offer a total executive reset. From our indoor heated pool to our signature therapies, every minute is designed to help you unplug, recover, and emerge as the best version of yourself.
                </p>
                <div class="flex items-center space-x-4 pt-4 text-sm font-semibold tracking-widest uppercase text-[--color-slate]">
                    <span class="text-[--color-gold]">✔</span> <span>Global Standard Therapists</span>
                </div>
                <div class="flex items-center space-x-4 text-sm font-semibold tracking-widest uppercase text-[--color-slate]">
                    <span class="text-[--color-gold]">✔</span> <span>Late Night Executive Hours (10 PM)</span>
                </div>
            </div>
            <div class="relative">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&q=80&w=1000" alt="Spa Sanctuary" class="w-full h-[500px] object-cover shadow-2xl rounded-sm">
            </div>
        </div>
    </section>

    <!-- Clinical Menu -->
    <section id="clinical" class="py-24 px-6 md:px-20 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <span class="uppercase tracking-widest text-xs font-bold text-[--color-gold]">Advanced Care</span>
                <h2 class="text-4xl md:text-5xl serif mt-4">The Clinical Edge</h2>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="medspa-card p-10 flex flex-col">
                    <h3 class="text-2xl mb-4 serif">The Luminous Ritual</h3>
                    <p class="text-sm font-light text-gray-500 leading-relaxed mb-6">Our premier high-ticket bundle for immediate, camera-ready radiance.</p>
                    <div class="mt-auto pt-6 border-t border-gray-100 flex justify-between items-center">
                        <span class="text-[--color-gold] font-bold">₦125,000</span>
                        <a href="https://wa.me/2348032470735?text=Hello,%20I'm%20interested%20in%20The%20Luminous%20Ritual." target="_blank" class="text-xs uppercase tracking-widest font-bold text-[--color-slate] hover:text-[--color-gold]">Enquire</a>
                    </div>
                </div>
                <div class="medspa-card p-10 flex flex-col">
                    <h3 class="text-2xl mb-4 serif">Body Contouring</h3>
                    <p class="text-sm font-light text-gray-500 leading-relaxed mb-6">Non-invasive medical procedures to refine and sculpt your silhouette.</p>
                    <div class="mt-auto pt-6 border-t border-gray-100">
                        <a href="https://wa.me/2348032470735?text=Hello,%20I'm%20interested%20in%20Body%20Contouring." target="_blank" class="text-xs uppercase tracking-widest font-bold text-[--color-slate] hover:text-[--color-gold]">Book Consultation</a>
                    </div>
                </div>
                <div class="medspa-card p-10 flex flex-col">
                    <h3 class="text-2xl mb-4 serif">Executive Reset</h3>
                    <p class="text-sm font-light text-gray-500 leading-relaxed mb-6">A deep-tissue focus combined with oxygen therapy for the modern professional.</p>
                    <div class="mt-auto pt-6 border-t border-gray-100">
                        <a href="https://wa.me/2348032470735?text=Hello,%20I'm%20interested%20in%20the%20Executive%20Reset." target="_blank" class="text-xs uppercase tracking-widest font-bold text-[--color-slate] hover:text-[--color-gold]">Enquire</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Reviews -->
    <section id="reviews" class="py-24 bg-[--color-slate] text-white text-center px-6">
        <div class="max-w-4xl mx-auto">
            <h2 class="uppercase tracking-widest text-xs font-bold text-[--color-gold] mb-12">Client Experiences</h2>
            <div id="carouselTrack" class="overflow-hidden relative h-64">
                <div class="flex transition-transform duration-500 ease-in-out h-full" id="innerTrack">
                    <div class="min-w-full flex flex-col justify-center px-4">
                        <p class="font-light text-xl md:text-2xl italic leading-relaxed mb-6">"The indoor heated pool before the massage was life-changing. Abuja's finest sanctuary."</p>
                        <p class="text-xs uppercase tracking-widest font-bold opacity-70">— Sarah O.</p>
                    </div>
                    <div class="min-w-full flex flex-col justify-center px-4">
                        <p class="font-light text-xl md:text-2xl italic leading-relaxed mb-6">"Their late-night availability is a lifesaver for my schedule. Truly executive service."</p>
                        <p class="text-xs uppercase tracking-widest font-bold opacity-70">— Amina M.</p>
                    </div>
                </div>
            </div>
            <div class="flex justify-center space-x-4 mt-8">
                <button onclick="moveSlide(-1)" class="opacity-50 hover:opacity-100 p-2">Prev</button>
                <button onclick="moveSlide(1)" class="opacity-50 hover:opacity-100 p-2">Next</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="booking" class="bg-[--color-light] text-[--color-slate] pt-24 pb-12 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-6 md:px-20 grid lg:grid-cols-2 gap-16 mb-16">
            <div>
                <h2 class="text-4xl md:text-5xl serif italic mb-8">Ready for the <br>Safi Experience?</h2>
                <div class="space-y-4 mb-10 text-sm opacity-80">
                    <p><strong>Address:</strong> No. 4 Agadez Crescent, Wuse 2, Abuja</p>
                    <p><strong>Direct Line:</strong> 0803 247 0735</p>
                    <p><strong>Hours:</strong> 09:00 AM — 10:00 PM Daily</p>
                </div>
                <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'd%20like%20to%20book%20a%20session." target="_blank" class="btn-primary px-10 py-5 text-sm inline-block shadow-lg">Confirm Booking via WhatsApp</a>
            </div>
            <div class="bg-gray-200 h-[300px] rounded-sm">
                 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3939.851965253818!2d7.472714!3d9.083321!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x104e0a5392e66b8b%3A0xc6222b4676465492!2sAgadez%20Crescent%2C%20Wuse%202%2C%20Abuja!5e0!3m2!1sen!2sng!4v1620000000000!5m2!1sen!2sng" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
        <div class="text-center text-[10px] text-gray-500 tracking-[0.2em] uppercase font-bold border-t border-gray-300 pt-8">
            © 2026 Safi's Spa | Digital Infrastructure by <span class="text-[--color-gold]">Digital Kato</span>
        </div>
    </footer>

    <script>
        let currentSlide = 0;
        const track = document.getElementById('innerTrack');
        function moveSlide(dir) {
            const total = track.children.length;
            currentSlide = (currentSlide + dir + total) % total;
            track.style.transform = `translateX(-${currentSlide * 100}%)`;
        }
        setInterval(() => moveSlide(1), 5000);
    </script>
</body>
</html>            background: linear-gradient(to right, rgba(44, 62, 80, 0.85), rgba(44, 62, 80, 0.4)), 
                        url('https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&q=80&w=2070');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .btn-primary {
            background-color: var(--color-gold);
            color: white;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.15em;
            font-weight: 600;
        }
        .btn-primary:hover {
            background-color: #B5952F;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }

        .medspa-card { background: white; border-top: 4px solid var(--color-gold); transition: all 0.4s ease; }
        .medspa-card:hover { box-shadow: 0 20px 40px rgba(0,0,0,0.08); transform: translateY(-5px); }

        .nav-link { position: relative; transition: color 0.3s ease; }
        .nav-link::after {
            content: ''; position: absolute; width: 0; height: 1px;
            bottom: -4px; left: 0; background-color: var(--color-gold);
            transition: width 0.3s ease;
        }
        .nav-link:hover::after { width: 100%; }

        /* Carousel Styles */
        .carousel-track { display: flex; transition: transform 0.5s ease-in-out; }
        .carousel-slide { min-width: 100%; }
        .carousel-btn { transition: all 0.3s ease; }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <nav class="flex justify-between items-center px-6 py-8 md:px-16 absolute w-full z-50 text-white">
        <div class="text-2xl font-bold tracking-[0.3em] uppercase">Safi's</div>
        <div class="hidden lg:flex space-x-8 uppercase text-xs font-medium tracking-[0.2em]">
            <a href="#sanctuary" class="nav-link">Sanctuary</a>
            <a href="#clinical" class="nav-link">MedSpa</a>
            <a href="#gallery" class="nav-link">Gallery</a>
            <a href="#reviews" class="nav-link">Reviews</a>
        </div>
        <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'm%20viewing%20your%20Executive%20Portal.%20I%20would%20like%20to%20request%20a%20concierge%20booking.%0A%0AService:%20[Enter%20Service]%0APreferred%20Date:%20[Enter%20Date]" target="_blank" class="border border-white/50 px-6 py-3 text-xs font-bold uppercase tracking-[0.1em] hover:bg-white hover:text-[--color-slate] transition-colors text-center hidden md:inline-block">Secure a Time</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero-bg min-h-screen flex flex-col justify-center px-6 md:px-20 pt-20">
        <div class="max-w-3xl text-white">
            <span class="uppercase tracking-[0.4em] text-xs mb-6 block text-[--color-gold] font-bold">Wuse II, Abuja • Open Until 10 PM</span>
            <h1 class="text-5xl md:text-7xl mb-8 leading-[1.1] font-semibold">
                Abuja’s Best Kept Secret for the <br><span class="italic text-[--color-gold] font-normal">Executive Glow.</span>
            </h1>
            <p class="text-lg md:text-xl font-light leading-relaxed mb-10 text-gray-200 max-w-2xl">
                Experience the sanctuary where luxury meets medical precision. Clinical results, wrapped in absolute serenity.
            </p>
            <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-6">
                <!-- Primary WhatsApp Booking Link -->
                <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'm%20viewing%20your%20Executive%20Portal.%20I%20would%20like%20to%20request%20a%20concierge%20booking.%0A%0AService:%20[Enter%20Service]%0APreferred%20Date:%20[Enter%20Date]" target="_blank" class="btn-primary px-10 py-5 text-sm text-center">Book Your Sanctuary</a>
                <a href="#clinical" class="border border-white/30 backdrop-blur-sm px-10 py-5 text-sm uppercase tracking-widest font-medium hover:bg-white/10 text-center transition-colors">View Clinical Menu</a>
            </div>
        </div>
    </section>

    <!-- The Hook -->
    <section id="sanctuary" class="py-24 px-6 md:px-20 bg-white">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 items-center">
            <div class="space-y-8 pr-0 md:pr-12">
                <h2 class="text-4xl md:text-5xl leading-tight text-[--color-slate]">Abuja is fast and demanding. <br><span class="italic font-light text-gray-500">You deserve a space that isn't.</span></h2>
                <div class="w-16 h-1 bg-[--color-gold]"></div>
                <p class="text-gray-600 leading-loose text-lg font-light">
                    At Safi’s Spa, we don’t just provide 'massages'—we offer a total executive reset. From our indoor heated pool to our signature therapies, every minute is designed to help you unplug, recover, and emerge as the best version of yourself.
                </p>
                <div class="flex items-center space-x-4 pt-4 text-sm font-semibold tracking-widest uppercase text-[--color-slate]">
                    <span class="text-[--color-gold]">✔</span> <span>Global Standard Therapists</span>
                </div>
                <div class="flex items-center space-x-4 text-sm font-semibold tracking-widest uppercase text-[--color-slate]">
                    <span class="text-[--color-gold]">✔</span> <span>Late Night Executive Hours (10 PM)</span>
                </div>
            </div>
            <div class="relative">
                <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&q=80&w=1000" alt="Spa Sanctuary" class="w-full h-[500px] object-cover shadow-2xl rounded-sm">
            </div>
        </div>
    </section>

    <!-- Clinical Menu -->
    <section id="clinical" class="py-24 px-6 md:px-20 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <span class="uppercase tracking-widest text-xs font-bold text-[--color-gold]">Advanced Care</span>
                <h2 class="text-4xl md:text-5xl serif mt-4">The Clinical Edge</h2>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="medspa-card p-10 flex flex-col">
                    <h3 class="text-2xl mb-4 serif">The Luminous Ritual</h3>
                    <p class="text-sm font-light text-gray-500 leading-relaxed mb-6">Our premier high-ticket bundle for immediate, camera-ready radiance.</p>
                    <div class="mt-auto pt-6 border-t border-gray-100 flex justify-between items-center">
                        <span class="text-[--color-gold] font-bold">₦125,000</span>
                        <a href="https://wa.me/2348032470735?text=Hello,%20I'm%20interested%20in%20The%20Luminous%20Ritual." target="_blank" class="text-xs uppercase tracking-widest font-bold text-[--color-slate] hover:text-[--color-gold]">Enquire</a>
                    </div>
                </div>
                <div class="medspa-card p-10 flex flex-col">
                    <h3 class="text-2xl mb-4 serif">Body Contouring</h3>
                    <p class="text-sm font-light text-gray-500 leading-relaxed mb-6">Non-invasive medical procedures to refine and sculpt your silhouette.</p>
                    <div class="mt-auto pt-6 border-t border-gray-100">
                        <a href="https://wa.me/2348032470735?text=Hello,%20I'm%20interested%20in%20Body%20Contouring." target="_blank" class="text-xs uppercase tracking-widest font-bold text-[--color-slate] hover:text-[--color-gold]">Book Consultation</a>
                    </div>
                </div>
                <div class="medspa-card p-10 flex flex-col">
                    <h3 class="text-2xl mb-4 serif">Executive Reset</h3>
                    <p class="text-sm font-light text-gray-500 leading-relaxed mb-6">A deep-tissue focus combined with oxygen therapy for the modern professional.</p>
                    <div class="mt-auto pt-6 border-t border-gray-100">
                        <a href="https://wa.me/2348032470735?text=Hello,%20I'm%20interested%20in%20the%20Executive%20Reset." target="_blank" class="text-xs uppercase tracking-widest font-bold text-[--color-slate] hover:text-[--color-gold]">Enquire</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Reviews -->
    <section id="reviews" class="py-24 bg-[--color-slate] text-white text-center px-6">
        <div class="max-w-4xl mx-auto">
            <h2 class="uppercase tracking-widest text-xs font-bold text-[--color-gold] mb-12">Client Experiences</h2>
            <div id="carouselTrack" class="overflow-hidden relative h-64">
                <div class="flex transition-transform duration-500 ease-in-out h-full" id="innerTrack">
                    <div class="min-w-full flex flex-col justify-center px-4">
                        <p class="font-light text-xl md:text-2xl italic leading-relaxed mb-6">"The indoor heated pool before the massage was life-changing. Abuja's finest sanctuary."</p>
                        <p class="text-xs uppercase tracking-widest font-bold opacity-70">— Sarah O.</p>
                    </div>
                    <div class="min-w-full flex flex-col justify-center px-4">
                        <p class="font-light text-xl md:text-2xl italic leading-relaxed mb-6">"Their late-night availability is a lifesaver for my schedule. Truly executive service."</p>
                        <p class="text-xs uppercase tracking-widest font-bold opacity-70">— Amina M.</p>
                    </div>
                </div>
            </div>
            <div class="flex justify-center space-x-4 mt-8">
                <button onclick="moveSlide(-1)" class="opacity-50 hover:opacity-100 p-2">Prev</button>
                <button onclick="moveSlide(1)" class="opacity-50 hover:opacity-100 p-2">Next</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="booking" class="bg-[--color-light] text-[--color-slate] pt-24 pb-12 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-6 md:px-20 grid lg:grid-cols-2 gap-16 mb-16">
            <div>
                <h2 class="text-4xl md:text-5xl serif italic mb-8">Ready for the <br>Safi Experience?</h2>
                <div class="space-y-4 mb-10 text-sm opacity-80">
                    <p><strong>Address:</strong> No. 4 Agadez Crescent, Wuse 2, Abuja</p>
                    <p><strong>Direct Line:</strong> 0803 247 0735</p>
                    <p><strong>Hours:</strong> 09:00 AM — 10:00 PM Daily</p>
                </div>
                <a href="https://wa.me/2348032470735?text=Hello%20Safi's%20Spa,%20I'd%20like%20to%20book%20a%20session." target="_blank" class="btn-primary px-10 py-5 text-sm inline-block shadow-lg">Confirm Booking via WhatsApp</a>
            </div>
            <div class="bg-gray-200 h-[300px] rounded-sm">
                 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3939.851965253818!2d7.472714!3d9.083321!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x104e0a5392e66b8b%3A0xc6222b4676465492!2sAgadez%20Crescent%2C%20Wuse%202%2C%20Abuja!5e0!3m2!1sen!2sng!4v1620000000000!5m2!1sen!2sng" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
        <div class="text-center text-[10px] text-gray-500 tracking-[0.2em] uppercase font-bold border-t border-gray-300 pt-8">
            © 2026 Safi's Spa | Digital Infrastructure by <span class="text-[--color-gold]">Digital Kato</span>
        </div>
    </footer>

    <script>
        let currentSlide = 0;
        const track = document.getElementById('innerTrack');
        function moveSlide(dir) {
            const total = track.children.length;
            currentSlide = (currentSlide + dir + total) % total;
            track.style.transform = `translateX(-${currentSlide * 100}%)`;
        }
        setInterval(() => moveSlide(1), 5000);
    </script>
</body>
</html>
