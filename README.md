<!DOCTYPE html>
<html lang="hi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>डिजिटल विज़न | डिजिटल मार्केटिंग और वेब समाधान</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts (Hind for Devanagari) -->
    <link href="https://fonts.googleapis.com/css2?family=Hind:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            800: '#0F172A',
                            900: '#020617',
                        },
                        brand: {
                            blue: '#2563EB',
                            light: '#3B82F6',
                            accent: '#F59E0B',
                        }
                    },
                    fontFamily: {
                        sans: ['Hind', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Hind', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-blue selection:text-white">

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md shadow-sm border-b border-slate-100 transition-all">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center gap-3 cursor-pointer" onclick="scrollToSection('hero')">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-blue to-cyan-400 flex items-center justify-center text-white text-xl font-bold shadow-md shadow-brand-blue/30">
                        <i class="fa-solid font-bold">DV</i>
                    </div>
                    <div>
                        <span class="text-2xl font-bold tracking-tight text-navy-900">डिजिटल<span class="text-brand-blue"> विज़न</span></span>
                        <span class="block text-xs text-slate-500 font-medium -mt-1">ग्रोथ एजेंसी</span>
                    </div>
                </div>

                <!-- Desktop Navigation Links -->
                <nav class="hidden md:flex space-x-8 text-base font-semibold text-slate-700">
                    <a href="#hero" class="hover:text-brand-blue transition-colors duration-200">होम</a>
                    <a href="#services" class="hover:text-brand-blue transition-colors duration-200">सेवाएं</a>
                    <a href="#testimonials" class="hover:text-brand-blue transition-colors duration-200">टेस्टामोनियल्स</a>
                    <a href="#team" class="hover:text-brand-blue transition-colors duration-200">हमारी टीम</a>
                    <a href="#contact" class="hover:text-brand-blue transition-colors duration-200">संपर्क करें</a>
                </nav>

                <!-- CTA Button -->
                <div class="hidden md:flex items-center">
                    <a href="#contact" class="bg-brand-blue hover:bg-navy-800 text-white px-6 py-2.5 rounded-xl font-semibold shadow-md shadow-brand-blue/20 hover:shadow-lg transition-all duration-300 transform hover:-translate-y-0.5">
                        मुफ्त परामर्श लें
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-700 hover:text-brand-blue focus:outline-none p-2 rounded-lg" aria-label="Toggle Menu">
                        <i class="fa-solid fa-bars text-2xl" id="menu-icon"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-6 space-y-3">
            <a href="#hero" class="mobile-link block px-3 py-2 rounded-lg text-base font-medium text-slate-700 hover:bg-slate-100 hover:text-brand-blue">होम</a>
            <a href="#services" class="mobile-link block px-3 py-2 rounded-lg text-base font-medium text-slate-700 hover:bg-slate-100 hover:text-brand-blue">सेवाएं</a>
            <a href="#testimonials" class="mobile-link block px-3 py-2 rounded-lg text-base font-medium text-slate-700 hover:bg-slate-100 hover:text-brand-blue">टेस्टामोनियल्स</a>
            <a href="#team" class="mobile-link block px-3 py-2 rounded-lg text-base font-medium text-slate-700 hover:bg-slate-100 hover:text-brand-blue">हमारी टीम</a>
            <a href="#contact" class="mobile-link block px-3 py-2 rounded-lg text-base font-medium text-slate-700 hover:bg-slate-100 hover:text-brand-blue">संपर्क करें</a>
            <div class="pt-2">
                <a href="#contact" class="mobile-link block text-center w-full bg-brand-blue text-white px-5 py-3 rounded-xl font-semibold shadow-md">
                    मुफ्त परामर्श लें
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="relative pt-12 pb-20 md:pt-20 md:pb-32 overflow-hidden bg-gradient-to-b from-slate-50 via-blue-50/30 to-slate-50">
        <!-- Background decorative elements -->
        <div class="absolute top-1/4 left-10 w-72 h-72 bg-brand-light/10 rounded-full blur-3xl -z-10 pointer-events-none"></div>
        <div class="absolute bottom-10 right-10 w-96 h-96 bg-brand-accent/10 rounded-full blur-3xl -z-10 pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-8 items-center">
                <!-- Text Content -->
                <div class="text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-blue-100/80 border border-blue-200 text-brand-blue text-sm font-semibold mb-6">
                        <span class="flex h-2 w-2 rounded-full bg-brand-blue animate-pulse"></span>
                        भारत की नंबर-1 ग्रोइंग डिजिटल एजेंसी
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-navy-900 tracking-tight leading-tight mb-6">
                        अपने व्यवसाय को <span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-blue to-cyan-500">डिजिटल युग</span> में नई ऊँचाइयों पर ले जाएँ
                    </h1>
                    <p class="text-lg sm:text-xl text-slate-600 font-normal mb-8 max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                        हम आपके ब्रांड को नई पहचान देने, बिक्री बढ़ाने और सही ग्राहकों तक पहुँचाने के लिए आधुनिक डिजिटल मार्केटिंग और वेब समाधान प्रदान करते हैं।
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
                        <a href="#contact" class="bg-brand-blue hover:bg-navy-800 text-white font-semibold text-lg px-8 py-4 rounded-xl shadow-lg shadow-brand-blue/30 hover:shadow-xl transition-all duration-300 text-center transform hover:-translate-y-1">
                            आज ही शुरुआत करें <i class="fa-solid fa-arrow-right ml-2 text-sm"></i>
                        </a>
                        <a href="#services" class="bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 font-semibold text-lg px-8 py-4 rounded-xl shadow-sm hover:shadow transition-all duration-300 text-center">
                            हमारी सेवाएं देखें
                        </a>
                    </div>
                    <!-- Trust Metrics -->
                    <div class="mt-12 pt-8 border-t border-slate-200/80 grid grid-cols-3 gap-4 text-center lg:text-left">
                        <div>
                            <p class="text-3xl font-extrabold text-navy-900">500+</p>
                            <p class="text-sm text-slate-500 font-medium">सफल प्रोजेक्ट्स</p>
                        </div>
                        <div>
                            <p class="text-3xl font-extrabold text-navy-900">98%</p>
                            <p class="text-sm text-slate-500 font-medium">संतुष्ट ग्राहक</p>
                        </div>
                        <div>
                            <p class="text-3xl font-extrabold text-navy-900">10x</p>
                            <p class="text-sm text-slate-500 font-medium">बिजनेस ग्रोथ</p>
                        </div>
                    </div>
                </div>

                <!-- Graphic/Illustration Card Showcase -->
                <div class="relative mx-auto w-full max-w-lg lg:max-w-none">
                    <div class="relative rounded-2xl bg-gradient-to-tr from-navy-900 to-slate-800 p-6 shadow-2xl overflow-hidden text-white border border-slate-700">
                        <!-- Header Mockup -->
                        <div class="flex items-center justify-between pb-6 border-b border-slate-700/60 mb-6">
                            <div class="flex space-x-2">
                                <div class="w-3 h-3 rounded-full bg-red-500"></div>
                                <div class="w-3 h-3 rounded-full bg-amber-500"></div>
                                <div class="w-3 h-3 rounded-full bg-emerald-500"></div>
                            </div>
                            <span class="text-xs font-mono text-slate-400">digitalvision-dashboard.com</span>
                        </div>

                        <!-- Dashboard Graphic Content -->
                        <div class="space-y-6">
                            <div class="grid grid-cols-2 gap-4">
                                <div class="bg-slate-800/80 p-4 rounded-xl border border-slate-700">
                                    <p class="text-xs text-slate-400 mb-1">कुल ट्रैफिक</p>
                                    <p class="text-2xl font-bold text-white">+142% <i class="fa-solid fa-arrow-trend-up text-emerald-400 text-sm"></i></p>
                                    <p class="text-xs text-slate-500 mt-2">पिछली तिमाही की तुलना में</p>
                                </div>
                                <div class="bg-slate-800/80 p-4 rounded-xl border border-slate-700">
                                    <p class="text-xs text-slate-400 mb-1">रूपांतरण दर (Conversion)</p>
                                    <p class="text-2xl font-bold text-brand-accent">8.4% <i class="fa-solid fa-chart-line text-xs"></i></p>
                                    <p class="text-xs text-slate-500 mt-2">औसत उद्योग मानक 2.5%</p>
                                </div>
                            </div>

                            <!-- Fake Graph Banner -->
                            <div class="bg-slate-800/80 p-5 rounded-xl border border-slate-700 relative overflow-hidden">
                                <div class="flex justify-between items-center mb-4">
                                    <span class="text-sm font-semibold text-slate-200">मासिक बिक्री वृद्धि</span>
                                    <span class="text-xs px-2.5 py-1 bg-emerald-500/20 text-emerald-300 rounded-md">लाइव डेटा</span>
                                </div>
                                <div class="h-28 flex items-end justify-between gap-2 pt-4">
                                    <div class="w-full bg-slate-700 rounded-t h-[40%]"></div>
                                    <div class="w-full bg-slate-700 rounded-t h-[55%]"></div>
                                    <div class="w-full bg-slate-700 rounded-t h-[45%]"></div>
                                    <div class="w-full bg-brand-blue rounded-t h-[75%]"></div>
                                    <div class="w-full bg-brand-blue rounded-t h-[65%]"></div>
                                    <div class="w-full bg-gradient-to-t from-brand-blue to-cyan-400 rounded-t h-[95%]"></div>
                                </div>
                            </div>
                        </div>

                        <!-- Floating Badge -->
                        <div class="absolute -bottom-4 -right-4 bg-white text-navy-900 p-4 rounded-2xl shadow-xl flex items-center gap-3 border border-slate-100 transform hover:scale-105 transition-transform">
                            <div class="w-12 h-12 bg-amber-100 rounded-xl flex items-center justify-center text-brand-accent text-2xl font-bold">
                                <i class="fa-solid fa-trophy"></i>
                            </div>
                            <div>
                                <p class="text-xs text-slate-500 font-semibold">पुरस्कार विजेता</p>
                                <p class="text-sm font-bold text-navy-900">बेस्ट एजेंसी 2025</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs uppercase font-bold tracking-widest text-brand-blue mb-2">हमारी विशेषज्ञता</h2>
                <p class="text-3xl sm:text-4xl font-extrabold text-navy-900">डिजिटल समाधान जो आपका बिज़नेस बढ़ाएं</p>
                <p class="text-slate-600 mt-4 text-lg">हम आपकी हर ऑनलाइन ज़रूरत के लिए आधुनिक और परिणाम-उन्मुख डिजिटल सेवाएं प्रदान करते हैं।</p>
            </div>

            <!-- Services Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl p-8 hover:bg-white hover:shadow-xl hover:border-brand-blue/30 transition-all duration-300 group">
                    <div class="w-14 h-14 bg-blue-100 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors duration-300">
                        <i class="fa-solid fa-magnifying-glass-chart"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-3">SEO ऑप्टिमाइजेशन</h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">गूगल के पहले पेज पर अपनी वेबसाइट लाएं। हम सर्च इंजन रैंकिंग सुधारकर ऑर्गेनिक ट्रैफिक बढ़ाते हैं।</p>
                    <a href="#contact" class="inline-flex items-center text-brand-blue font-semibold hover:text-navy-900 transition-colors">
                        और जानें <i class="fa-solid fa-chevron-right ml-2 text-xs group-hover:translate-x-1 transition-transform"></i>
                    </a>
                </div>

                <!-- Service 2 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl p-8 hover:bg-white hover:shadow-xl hover:border-brand-blue/30 transition-all duration-300 group">
                    <div class="w-14 h-14 bg-blue-100 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors duration-300">
                        <i class="fa-solid fa-hashtag"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-3">सोशल मीडिया मार्केटिंग</h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">इंस्टाग्राम, फेसबुक और लिंक्डइन पर लक्षित अभियानों के साथ अपने ब्रांड की मजबूत उपस्थिति बनाएं।</p>
                    <a href="#contact" class="inline-flex items-center text-brand-blue font-semibold hover:text-navy-900 transition-colors">
                        और जानें <i class="fa-solid fa-chevron-right ml-2 text-xs group-hover:translate-x-1 transition-transform"></i>
                    </a>
                </div>

                <!-- Service 3 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl p-8 hover:bg-white hover:shadow-xl hover:border-brand-blue/30 transition-all duration-300 group">
                    <div class="w-14 h-14 bg-blue-100 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors duration-300">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-3">वेब डेवलपमेंट</h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">फास्ट, सुरक्षित और मोबाइल-फ्रेंडली वेबसाइट्स और ई-कॉमर्स स्टोर्स का निर्माण जो यूज़र्स को ग्राहक बनाए।</p>
                    <a href="#contact" class="inline-flex items-center text-brand-blue font-semibold hover:text-navy-900 transition-colors">
                        और जानें <i class="fa-solid fa-chevron-right ml-2 text-xs group-hover:translate-x-1 transition-transform"></i>
                    </a>
                </div>

                <!-- Service 4 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl p-8 hover:bg-white hover:shadow-xl hover:border-brand-blue/30 transition-all duration-300 group">
                    <div class="w-14 h-14 bg-blue-100 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors duration-300">
                        <i class="fa-solid fa-pen-nib"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-3">ग्राफिक डिज़ाइन और ब्रांडिंग</h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">प्रोफेशनल लोगो, सोशल मीडिया पोस्ट, और विज्ञापन क्रिएटिव्स जो ग्राहकों का ध्यान तुरंत खींचते हैं।</p>
                    <a href="#contact" class="inline-flex items-center text-brand-blue font-semibold hover:text-navy-900 transition-colors">
                        और जानें <i class="fa-solid fa-chevron-right ml-2 text-xs group-hover:translate-x-1 transition-transform"></i>
                    </a>
                </div>

                <!-- Service 5 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl p-8 hover:bg-white hover:shadow-xl hover:border-brand-blue/30 transition-all duration-300 group">
                    <div class="w-14 h-14 bg-blue-100 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors duration-300">
                        <i class="fa-solid fa-rectangle-ad"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-3">पे-पर-क्लिक (PPC) एड्स</h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">गूगल एड्स और मेटा एड्स के माध्यम से तुरंत लीड्स और बिक्री प्राप्त करें। बजट का सही उपयोग।</p>
                    <a href="#contact" class="inline-flex items-center text-brand-blue font-semibold hover:text-navy-900 transition-colors">
                        और जानें <i class="fa-solid fa-chevron-right ml-2 text-xs group-hover:translate-x-1 transition-transform"></i>
                    </a>
                </div>

                <!-- Service 6 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl p-8 hover:bg-white hover:shadow-xl hover:border-brand-blue/30 transition-all duration-300 group">
                    <div class="w-14 h-14 bg-blue-100 text-brand-blue rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors duration-300">
                        <i class="fa-solid fa-lightbulb"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-3">कंटेंट स्ट्रेटेजी</h3>
                    <p class="text-slate-600 mb-6 leading-relaxed">आपके बिज़नेस के लिए प्रभावशाली ब्लॉग, आर्टिकल्स और वीडियो स्क्रिप्ट जो ग्राहकों में भरोसा पैदा करें।</p>
                    <a href="#contact" class="inline-flex items-center text-brand-blue font-semibold hover:text-navy-900 transition-colors">
                        और जानें <i class="fa-solid fa-chevron-right ml-2 text-xs group-hover:translate-x-1 transition-transform"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-slate-100/70 border-y border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs uppercase font-bold tracking-widest text-brand-blue mb-2">सफलता की कहानियां</h2>
                <p class="text-3xl sm:text-4xl font-extrabold text-navy-900">हमारे ग्राहक क्या कहते हैं</p>
                <p class="text-slate-600 mt-4 text-lg">जानिए कैसे हमने विभिन्न व्यवसायों की ऑनलाइन उपस्थिति बदलकर उनकी ग्रोथ में मदद की।</p>
            </div>

            <!-- Testimonial Grid -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="flex text-amber-400 gap-1 mb-4 text-sm">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-slate-700 italic mb-6 leading-relaxed">
                            "डिजिटल विज़न ने हमारी ई-कॉमर्स वेबसाइट को फिर से डिजाइन किया और SEO संभाला। केवल 4 महीनों में हमारी ऑनलाइन सेल्स 3 गुना बढ़ गई!"
                        </p>
                    </div>
                    <div class="flex items-center gap-4 pt-4 border-t border-slate-100">
                        <img src="https://placehold.co/100x100/2563EB/FFFFFF?text=आर+के" alt="रवि कुमार" class="w-12 h-12 rounded-full object-cover">
                        <div>
                            <h4 class="font-bold text-navy-900">रवि कुमार</h4>
                            <p class="text-xs text-slate-500 font-medium">संस्थापक, एपेक्स रिटेल्स</p>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="flex text-amber-400 gap-1 mb-4 text-sm">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-slate-700 italic mb-6 leading-relaxed">
                            "इनकी सोशल मीडिया टीम कमाल की है! हमारे ब्रांड की विजिबिलिटी और इंस्टाग्राम फॉलोअर्स में ज़बरदस्त उछाल आया है। बहुत ही पेशेवर सेवा।"
                        </p>
                    </div>
                    <div class="flex items-center gap-4 pt-4 border-t border-slate-100">
                        <img src="https://placehold.co/100x100/F59E0B/FFFFFF?text=एस+एस" alt="सुनीता शर्मा" class="w-12 h-12 rounded-full object-cover">
                        <div>
                            <h4 class="font-bold text-navy-900">सुनीता शर्मा</h4>
                            <p class="text-xs text-slate-500 font-medium">मार्केटिंग हेड, ग्रीनटेक समाधान</p>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 3 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="flex text-amber-400 gap-1 mb-4 text-sm">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i>
                        </div>
                        <p class="text-slate-700 italic mb-6 leading-relaxed">
                            "पे-पर-क्लिक एड्स अभियान के लिए डिजिटल विज़न सबसे बेहतरीन विकल्प है। कम बजट में भी हमें बहुत उच्च गुणवत्ता वाली लीड्स प्राप्त हुईं।"
                        </p>
                    </div>
                    <div class="flex items-center gap-4 pt-4 border-t border-slate-100">
                        <img src="https://placehold.co/100x100/0F172A/FFFFFF?text=ए+वि" alt="अमित वर्मा" class="w-12 h-12 rounded-full object-cover">
                        <div>
                            <h4 class="font-bold text-navy-900">अमित वर्मा</h4>
                            <p class="text-xs text-slate-500 font-medium">सीईओ, अर्बन रियल एस्टेट</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Our Team Section -->
    <section id="team" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs uppercase font-bold tracking-widest text-brand-blue mb-2">विशेषज्ञ टीम</h2>
                <p class="text-3xl sm:text-4xl font-extrabold text-navy-900">मिलिए हमारे विशेषज्ञों से</p>
                <p class="text-slate-600 mt-4 text-lg">अनुभवी और ऊर्जावान पेशेवरों की टीम जो आपके बिज़नेस के लिए समर्पित है।</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Team Member 1 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl overflow-hidden shadow-sm hover:shadow-lg transition-all text-center group">
                    <div class="relative overflow-hidden">
                        <img src="https://placehold.co/400x400/0F172A/FFFFFF?text=अजय+सिंह" alt="अजय सिंह" class="w-full h-64 object-cover group-hover:scale-105 transition-transform duration-300">
                        <div class="absolute inset-0 bg-navy-900/60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4 text-white">
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-linkedin-in"></i></a>
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-x-twitter"></i></a>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-navy-900">अजय सिंह</h3>
                        <p class="text-brand-blue font-medium text-sm mb-2">मुख्य कार्यकारी अधिकारी (CEO)</p>
                        <p class="text-xs text-slate-500">10+ वर्षों का डिजिटल रणनीति अनुभव</p>
                    </div>
                </div>

                <!-- Team Member 2 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl overflow-hidden shadow-sm hover:shadow-lg transition-all text-center group">
                    <div class="relative overflow-hidden">
                        <img src="https://placehold.co/400x400/2563EB/FFFFFF?text=नेहा+गुप्ता" alt="नेहा गुप्ता" class="w-full h-64 object-cover group-hover:scale-105 transition-transform duration-300">
                        <div class="absolute inset-0 bg-navy-900/60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4 text-white">
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-linkedin-in"></i></a>
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-instagram"></i></a>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-navy-900">नेहा गुप्ता</h3>
                        <p class="text-brand-blue font-medium text-sm mb-2">हेड ऑफ SEO & डिजिटल मार्केटिंग</p>
                        <p class="text-xs text-slate-500">सर्च इंजन रैंकिंग विशेषज्ञ</p>
                    </div>
                </div>

                <!-- Team Member 3 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl overflow-hidden shadow-sm hover:shadow-lg transition-all text-center group">
                    <div class="relative overflow-hidden">
                        <img src="https://placehold.co/400x400/3B82F6/FFFFFF?text=विक्रम+आदित्य" alt="विक्रम आदित्य" class="w-full h-64 object-cover group-hover:scale-105 transition-transform duration-300">
                        <div class="absolute inset-0 bg-navy-900/60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4 text-white">
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-github"></i></a>
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-linkedin-in"></i></a>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-navy-900">विक्रम आदित्य</h3>
                        <p class="text-brand-blue font-medium text-sm mb-2">लीड वेब डेवलपर</p>
                        <p class="text-xs text-slate-500">फुल-स्टैक और UI/UX विशेषज्ञ</p>
                    </div>
                </div>

                <!-- Team Member 4 -->
                <div class="bg-slate-50 border border-slate-100 rounded-2xl overflow-hidden shadow-sm hover:shadow-lg transition-all text-center group">
                    <div class="relative overflow-hidden">
                        <img src="https://placehold.co/400x400/F59E0B/FFFFFF?text=पूजा+मेहरा" alt="पूजा मेहरा" class="w-full h-64 object-cover group-hover:scale-105 transition-transform duration-300">
                        <div class="absolute inset-0 bg-navy-900/60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4 text-white">
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-behance"></i></a>
                            <a href="#" class="w-9 h-9 bg-white/20 hover:bg-brand-blue rounded-full flex items-center justify-center transition-colors"><i class="fa-brands fa-dribbble"></i></a>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-navy-900">पूजा मेहरा</h3>
                        <p class="text-brand-blue font-medium text-sm mb-2">क्रिएटिव आर्ट डायरेक्टर</p>
                        <p class="text-xs text-slate-500">ब्रांडिंग एवं क्रिएटिव डिज़ाइनर</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact / Inquiry Section -->
    <section id="contact" class="py-20 bg-gradient-to-br from-navy-900 via-slate-900 to-navy-800 text-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                
                <!-- Contact Details -->
                <div>
                    <span class="text-brand-light uppercase font-bold tracking-widest text-xs">हमसे संपर्क करें</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold mt-2 mb-6">क्या आप अपने बिज़नेस को आगे बढ़ाने के लिए तैयार हैं?</h2>
                    <p class="text-slate-300 text-lg mb-8 leading-relaxed">
                        हमें अपनी प्रोजेक्ट की आवश्यकताओं के बारे में बताएं। हमारी टीम 24 घंटों के भीतर आपसे संपर्क करेगी और एक मुफ्त रणनीति प्रदान करेगी।
                    </p>

                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-white/10 rounded-xl flex items-center justify-center text-brand-light text-xl flex-shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg">हमारा पता</h4>
                                <p class="text-slate-300 text-sm">साइबर सिटी, टावर B, गुरुग्राम, हरियाणा - 122002, भारत</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-white/10 rounded-xl flex items-center justify-center text-brand-light text-xl flex-shrink-0">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg">ईमेल करें</h4>
                                <p class="text-slate-300 text-sm">info@digitalvision.in / contact@digitalvision.in</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-white/10 rounded-xl flex items-center justify-center text-brand-light text-xl flex-shrink-0">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg">फ़ोन करें</h4>
                                <p class="text-slate-300 text-sm">+91 98765 43210 / +91 0124 456789</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Contact Form Card -->
                <div class="bg-white rounded-3xl p-8 sm:p-10 text-slate-800 shadow-2xl relative">
                    <h3 class="text-2xl font-bold text-navy-900 mb-2">मुफ्त परामर्श फॉर्म</h3>
                    <p class="text-slate-500 text-sm mb-6">नीचे दिए गए फ़ॉर्म को भरें, हम आपसे तुरंत जुड़ेंगे।</p>

                    <!-- Alert Box for Submission -->
                    <div id="form-alert" class="hidden mb-6 p-4 rounded-xl bg-emerald-100 border border-emerald-300 text-emerald-800 text-sm font-medium flex items-center gap-3">
                        <i class="fa-solid fa-circle-check text-lg text-emerald-600"></i>
                        <span>धन्यवाद! आपका संदेश सफलतापूर्वक भेज दिया गया है। हमारी टीम जल्द आपसे संपर्क करेगी।</span>
                    </div>

                    <form id="inquiry-form" onsubmit="handleFormSubmit(event)" class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold text-slate-700 mb-1">आपका नाम *</label>
                            <input type="text" required placeholder="जैसे: राहुल शर्मा" class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-blue/50 focus:border-brand-blue text-sm transition-all">
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-1">ईमेल आईडी *</label>
                                <input type="email" required placeholder="name@example.com" class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-blue/50 focus:border-brand-blue text-sm transition-all">
                            </div>
                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-1">फोन नंबर *</label>
                                <input type="tel" required placeholder="+91 9876543210" class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-blue/50 focus:border-brand-blue text-sm transition-all">
                            </div>
                        </div>

                        <div>
                            <label class="block text-sm font-semibold text-slate-700 mb-1">किस सेवा में रुचि है? *</label>
                            <select required class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-blue/50 focus:border-brand-blue text-sm transition-all bg-white text-slate-700">
                                <option value="" disabled selected>एक सेवा चुनें...</option>
                                <option value="seo">SEO ऑप्टिमाइजेशन</option>
                                <option value="smm">सोशल मीडिया मार्केटिंग</option>
                                <option value="web">वेब डेवलपमेंट</option>
                                <option value="design">ग्राफिक डिजाइन व ब्रांडिंग</option>
                                <option value="ppc">पे-पर-क्लिक (PPC) एड्स</option>
                                <option value="other">अन्य</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-sm font-semibold text-slate-700 mb-1">आपका संदेश / प्रोजेक्ट विवरण</label>
                            <textarea rows="4" placeholder="अपने बिज़नेस या प्रोजेक्ट के बारे में कुछ बताएं..." class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-blue/50 focus:border-brand-blue text-sm transition-all"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-brand-blue hover:bg-navy-900 text-white font-bold py-3.5 rounded-xl shadow-lg shadow-brand-blue/30 transition-all duration-300">
                            संदेश भेजें <i class="fa-solid fa-paper-plane ml-2"></i>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-navy-900 text-slate-400 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
                <!-- Company Info -->
                <div class="md:col-span-1">
                    <div class="flex items-center gap-2 mb-4">
                        <div class="w-8 h-8 rounded-lg bg-brand-blue flex items-center justify-center text-white font-bold text-sm">
                            DV
                        </div>
                        <span class="text-xl font-bold text-white tracking-tight">डिजिटल<span class="text-brand-blue"> विज़न</span></span>
                    </div>
                    <p class="text-sm text-slate-400 leading-relaxed mb-4">
                        हम आपके ब्रांड को डिजिटल दुनिया में स्थापित करने और उच्च विकास प्राप्त करने में मदद करते हैं।
                    </p>
                    <div class="flex space-x-3 text-slate-300">
                        <a href="#" class="w-9 h-9 bg-slate-800 rounded-lg flex items-center justify-center hover:bg-brand-blue hover:text-white transition-colors"><i class="fa-brands fa-facebook-f"></i></a>
                        <a href="#" class="w-9 h-9 bg-slate-800 rounded-lg flex items-center justify-center hover:bg-brand-blue hover:text-white transition-colors"><i class="fa-brands fa-instagram"></i></a>
                        <a href="#" class="w-9 h-9 bg-slate-800 rounded-lg flex items-center justify-center hover:bg-brand-blue hover:text-white transition-colors"><i class="fa-brands fa-x-twitter"></i></a>
                        <a href="#" class="w-9 h-9 bg-slate-800 rounded-lg flex items-center justify-center hover:bg-brand-blue hover:text-white transition-colors"><i class="fa-brands fa-linkedin-in"></i></a>
                    </div>
                </div>

                <!-- Quick Links -->
                <div>
                    <h4 class="text-white font-bold mb-4 text-base">त्वरित लिंक्स</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li><a href="#hero" class="hover:text-white transition-colors">होम</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors">हमारी सेवाएं</a></li>
                        <li><a href="#testimonials" class="hover:text-white transition-colors">ग्राहकों की राय</a></li>
                        <li><a href="#team" class="hover:text-white transition-colors">हमारी टीम</a></li>
                        <li><a href="#contact" class="hover:text-white transition-colors">संपर्क करें</a></li>
                    </ul>
                </div>

                <!-- Services List -->
                <div>
                    <h4 class="text-white font-bold mb-4 text-base">हमारी सेवाएं</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li><a href="#services" class="hover:text-white transition-colors">SEO ऑप्टिमाइजेशन</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors">सोशल मीडिया मार्केटिंग</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors">वेबसाइट डिज़ाइनिंग</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors">पे-पर-क्लिक विज्ञापन</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors">ब्रांडिंग व लोगो</a></li>
                    </ul>
                </div>

                <!-- Newsletter -->
                <div>
                    <h4 class="text-white font-bold mb-4 text-base">न्यूज़लेटर की सदस्यता लें</h4>
                    <p class="text-xs text-slate-400 mb-4">डिजिटल मार्केटिंग के नए टिप्स और अपडेट्स सीधे अपने ईमेल पर पाएं।</p>
                    <div class="flex flex-col space-y-2">
                        <input type="email" placeholder="आपकी ईमेल आईडी" class="bg-slate-800 border border-slate-700 text-white px-4 py-2.5 rounded-xl text-sm focus:outline-none focus:border-brand-blue">
                        <button class="bg-brand-blue text-white px-4 py-2.5 rounded-xl font-semibold text-sm hover:bg-blue-600 transition-colors">
                            सब्सक्राइब करें
                        </button>
                    </div>
                </div>
            </div>

            <!-- Copyright -->
            <div class="border-t border-slate-800 pt-8 flex flex-col md:flex-row justify-between items-center text-xs text-slate-500 gap-4">
                <p>© 2026 डिजिटल विज़न (Digital Vision). सभी अधिकार सुरक्षित हैं।</p>
                <div class="flex space-x-6">
                    <a href="#" class="hover:text-slate-400">गोपनीयता नीति (Privacy Policy)</a>
                    <a href="#" class="hover:text-slate-400">सेवा की शर्तें (Terms of Service)</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Interactive Scripts -->
    <script>
        // Mobile Menu Toggle Logic
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const menuIcon = document.getElementById('menu-icon');
        const mobileLinks = document.querySelectorAll('.mobile-link');

        mobileMenuBtn.addEventListener('click', () => {
            const isHidden = mobileMenu.classList.contains('hidden');
            if (isHidden) {
                mobileMenu.classList.remove('hidden');
                menuIcon.classList.remove('fa-bars');
                menuIcon.classList.add('fa-xmark');
            } else {
                mobileMenu.classList.add('hidden');
                menuIcon.classList.remove('fa-xmark');
                menuIcon.classList.add('fa-bars');
            }
        });

        // Close mobile menu when link is clicked
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuIcon.classList.remove('fa-xmark');
                menuIcon.classList.add('fa-bars');
            });
        });

        // Smooth Scrolling Helper
        function scrollToSection(id) {
            const element = document.getElementById(id);
            if (element) {
                element.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // Contact Form Submission Handler
        function handleFormSubmit(event) {
            event.preventDefault();
            const alertBox = document.getElementById('form-alert');
            const form = document.getElementById('inquiry-form');

            // Show Notification Alert
            alertBox.classList.remove('hidden');

            // Reset Form Fields
            form.reset();

            // Auto-hide alert after 6 seconds
            setTimeout(() => {
                alertBox.classList.add('hidden');
            }, 6000);
        }
    </script>
</body>
</html>
