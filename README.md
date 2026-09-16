[index.html.htm](https://github.com/user-attachments/files/32294437/index.html.htm)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WIZARD PRO | Developer Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- AOS Animation Library CDN -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <style>
        html {
            scroll-behavior: smooth;
        }
        .glass {
            background: rgba(15, 23, 42, 0.75);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .glass-card {
            background: rgba(30, 41, 59, 0.5);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .glass-card:hover {
            border-color: rgba(99, 102, 241, 0.4);
            box-shadow: 0 10px 30px -10px rgba(99, 102, 241, 0.3);
        }
        @keyframes pulse-glow {
            0%, 100% { opacity: 0.4; transform: scale(1); }
            50% { opacity: 0.7; transform: scale(1.05); }
        }
        .animate-glow {
            animation: pulse-glow 6s infinite ease-in-out;
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 font-sans selection:bg-indigo-500 selection:text-white">

    <!-- Background Animated Blobs -->
    <div class="fixed inset-0 overflow-hidden pointer-events-none -z-10">
        <div class="absolute -top-40 -left-40 w-96 h-96 bg-indigo-600/20 rounded-full blur-3xl animate-glow"></div>
        <div class="absolute top-1/2 -right-40 w-96 h-96 bg-cyan-600/20 rounded-full blur-3xl animate-glow" style="animation-delay: 3s;"></div>
    </div>

    <!-- Navigation Bar -->
    <nav class="sticky top-0 z-50 glass border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold tracking-wider text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-indigo-500 flex items-center gap-2">
                <i class="fa-solid fa-wand-magic-sparkles text-cyan-400"></i> WIZARD PRO
            </a>
            <div class="hidden md:flex gap-8 text-sm font-medium text-slate-400">
                <a href="#about" class="hover:text-cyan-400 transition-colors">About</a>
                <a href="#skills" class="hover:text-cyan-400 transition-colors">Skills</a>
                <a href="#projects" class="hover:text-cyan-400 transition-colors">Projects</a>
                <a href="#contact" class="hover:text-cyan-400 transition-colors">Contact</a>
            </div>
            <a href="#contact" class="px-4 py-2 rounded-lg bg-indigo-600 hover:bg-indigo-500 text-white text-sm font-medium transition-all shadow-lg shadow-indigo-600/30">
                Hire Me
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="about" class="max-w-6xl mx-auto px-6 pt-24 pb-20 flex flex-col items-center text-center">
        <div data-aos="fade-up" data-aos-duration="1000">
            <span class="inline-flex items-center gap-2 px-3.5 py-1 text-xs font-semibold uppercase tracking-widest text-cyan-400 bg-cyan-950/50 border border-cyan-800/50 rounded-full mb-6">
                <i class="fa-solid fa-graduation-cap text-xs"></i> MUBS Student & Software Developer
            </span>
            <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight mb-6">
                Crafted by <br />
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 via-indigo-400 to-purple-500">
                    WIZARD PRO
                </span>
            </h1>
            <p class="max-w-2xl text-slate-400 text-lg md:text-xl leading-relaxed mb-4">
                Software programmer and student at <strong>Makerere University Business School (MUBS)</strong>.
            </p>
            <p class="max-w-2xl text-slate-400 text-base md:text-lg leading-relaxed mb-10">
                Building multi-domain applications using <strong>HTML/CSS</strong>, dynamic <strong>React</strong> frontends, high-performance <strong>C++</strong> systems, and intelligent <strong>Python</strong> scripts.
            </p>

            <div class="flex flex-wrap justify-center gap-4">
                <a href="#projects" class="px-8 py-3.5 rounded-xl bg-gradient-to-r from-cyan-500 to-indigo-600 text-white font-medium shadow-lg shadow-cyan-500/25 hover:shadow-cyan-500/40 hover:-translate-y-0.5 transition-all">
                    View Projects <i class="fa-solid fa-arrow-right ml-2 text-xs"></i>
                </a>
                <a href="#contact" class="px-8 py-3.5 rounded-xl bg-slate-900 border border-slate-800 text-slate-300 font-medium hover:bg-slate-800 hover:-translate-y-0.5 transition-all">
                    Get in Touch
                </a>
            </div>
        </div>

        <!-- Terminal Widget -->
        <div class="w-full max-w-2xl mt-16 text-left" data-aos="zoom-in" data-aos-delay="200">
            <div class="bg-slate-900 border border-slate-800 rounded-xl overflow-hidden shadow-2xl">
                <div class="bg-slate-950/80 px-4 py-3 border-b border-slate-800 flex items-center gap-2">
                    <div class="w-3 h-3 rounded-full bg-red-500/80"></div>
                    <div class="w-3 h-3 rounded-full bg-yellow-500/80"></div>
                    <div class="w-3 h-3 rounded-full bg-green-500/80"></div>
                    <span class="text-xs text-slate-500 font-mono ml-2">wizard-pro@mubs ~ zsh</span>
                </div>
                <div class="p-6 font-mono text-sm leading-relaxed text-slate-300 space-y-2">
                    <p><span class="text-emerald-400">➜</span> <span class="text-cyan-400">~</span> <span class="text-slate-400">wizard-pro --identity</span></p>
                    <p class="text-slate-400">{ "brand": "WIZARD PRO", "institution": "Makerere University Business School" }</p>
                    <p><span class="text-emerald-400">➜</span> <span class="text-cyan-400">~</span> <span class="text-slate-400">wizard-pro --contact</span></p>
                    <p class="text-slate-400">[ "+256 780 432 448", "+256 703 342 170" ]</p>
                    <p><span class="text-emerald-400">➜</span> <span class="text-cyan-400">~</span> <span class="text-slate-400">wizard-pro --status</span></p>
                    <p class="text-indigo-400">"Ready for software engineering projects and collaborations."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="max-w-6xl mx-auto px-6 py-20 border-t border-slate-900">
        <div class="text-center mb-16" data-aos="fade-up">
            <h2 class="text-3xl font-bold">Tech Stack & Languages</h2>
            <p class="text-slate-400 mt-2">Core technical expertise engineered for performance and scalability.</p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- HTML/JS -->
            <div class="glass-card p-6 rounded-2xl transition-all duration-300 group" data-aos="fade-up" data-aos-delay="100">
                <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-orange-400 to-red-500 p-0.5 mb-4">
                    <div class="w-full h-full bg-slate-950 rounded-[10px] flex items-center justify-center">
                        <i class="fa-brands fa-html5 text-xl text-orange-400 group-hover:scale-110 transition-transform"></i>
                    </div>
                </div>
                <h3 class="text-xl font-bold mb-1">HTML, CSS & JS</h3>
                <span class="text-xs font-semibold px-2 py-0.5 rounded bg-slate-800 text-slate-400">Frontend Core</span>
                <p class="text-sm text-slate-400 mt-3">Semantic HTML5, responsive CSS3 designs, and modern ES6+ JavaScript.</p>
            </div>

            <!-- React -->
            <div class="glass-card p-6 rounded-2xl transition-all duration-300 group" data-aos="fade-up" data-aos-delay="200">
                <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-cyan-400 to-blue-500 p-0.5 mb-4">
                    <div class="w-full h-full bg-slate-950 rounded-[10px] flex items-center justify-center">
                        <i class="fa-brands fa-react text-xl text-cyan-400 group-hover:scale-110 transition-transform"></i>
                    </div>
                </div>
                <h3 class="text-xl font-bold mb-1">React.js</h3>
                <span class="text-xs font-semibold px-2 py-0.5 rounded bg-slate-800 text-slate-400">Frontend Lib</span>
                <p class="text-sm text-slate-400 mt-3">Component architecture, state management, interactive UIs, and SPA web apps.</p>
            </div>

            <!-- Python -->
            <div class="glass-card p-6 rounded-2xl transition-all duration-300 group" data-aos="fade-up" data-aos-delay="300">
                <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-yellow-400 to-green-500 p-0.5 mb-4">
                    <div class="w-full h-full bg-slate-950 rounded-[10px] flex items-center justify-center">
                        <i class="fa-brands fa-python text-xl text-yellow-400 group-hover:scale-110 transition-transform"></i>
                    </div>
                </div>
                <h3 class="text-xl font-bold mb-1">Python</h3>
                <span class="text-xs font-semibold px-2 py-0.5 rounded bg-slate-800 text-slate-400">Backend & Scripting</span>
                <p class="text-sm text-slate-400 mt-3">Automation scripts, data manipulation, REST APIs, and business intelligence solutions.</p>
            </div>

            <!-- C++ -->
            <div class="glass-card p-6 rounded-2xl transition-all duration-300 group" data-aos="fade-up" data-aos-delay="400">
                <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-blue-500 to-indigo-600 p-0.5 mb-4">
                    <div class="w-full h-full bg-slate-950 rounded-[10px] flex items-center justify-center">
                        <i class="fa-solid fa-code text-xl text-indigo-400 group-hover:scale-110 transition-transform"></i>
                    </div>
                </div>
                <h3 class="text-xl font-bold mb-1">C++</h3>
                <span class="text-xs font-semibold px-2 py-0.5 rounded bg-slate-800 text-slate-400">Systems & OOP</span>
                <p class="text-sm text-slate-400 mt-3">Object-Oriented Programming, memory management, algorithms, and high-speed execution.</p>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="max-w-6xl mx-auto px-6 py-20 border-t border-slate-900">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-12 gap-4" data-aos="fade-up">
            <div>
                <h2 class="text-3xl font-bold">Featured Projects</h2>
                <p class="text-slate-400 mt-2">Filter projects built by WIZARD PRO.</p>
            </div>

            <!-- Category Filter Buttons -->
            <div class="flex flex-wrap gap-2 bg-slate-900/80 p-1.5 rounded-xl border border-slate-800">
                <button onclick="filterProjects('all')" class="filter-btn active px-4 py-1.5 rounded-lg text-sm font-medium transition-all bg-indigo-600 text-white">All</button>
                <button onclick="filterProjects('react')" class="filter-btn px-4 py-1.5 rounded-lg text-sm font-medium transition-all text-slate-400 hover:text-slate-200">React</button>
                <button onclick="filterProjects('python')" class="filter-btn px-4 py-1.5 rounded-lg text-sm font-medium transition-all text-slate-400 hover:text-slate-200">Python</button>
                <button onclick="filterProjects('cpp')" class="filter-btn px-4 py-1.5 rounded-lg text-sm font-medium transition-all text-slate-400 hover:text-slate-200">C++</button>
            </div>
        </div>

        <!-- Project Cards Grid -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- C++ Project -->
            <div class="project-card cpp glass-card p-6 rounded-2xl flex flex-col justify-between transition-all duration-300" data-aos="fade-up">
                <div>
                    <div class="flex justify-between items-center mb-4">
                        <span class="text-xs font-bold px-2.5 py-1 rounded-md bg-indigo-950/80 text-indigo-400 border border-indigo-800/50">C++</span>
                        <div class="flex gap-3 text-slate-400">
                            <a href="https://x.com/samuel25666" target="_blank" class="hover:text-white transition-colors"><i class="fa-brands fa-github text-lg"></i></a>
                            <a href="#" class="hover:text-white transition-colors"><i class="fa-solid fa-arrow-up-right-from-square text-sm"></i></a>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold mb-2">High-Performance Engine</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-6">A high-speed system utility engineered in C++ utilizing custom data structures and OOP principles.</p>
                </div>
                <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-800/50">
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#cpp</span>
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#algorithms</span>
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#performance</span>
                </div>
            </div>

            <!-- Python Project -->
            <div class="project-card python glass-card p-6 rounded-2xl flex flex-col justify-between transition-all duration-300" data-aos="fade-up" data-aos-delay="100">
                <div>
                    <div class="flex justify-between items-center mb-4">
                        <span class="text-xs font-bold px-2.5 py-1 rounded-md bg-emerald-950/80 text-emerald-400 border border-emerald-800/50">Python</span>
                        <div class="flex gap-3 text-slate-400">
                            <a href="https://x.com/samuel25666" target="_blank" class="hover:text-white transition-colors"><i class="fa-brands fa-github text-lg"></i></a>
                            <a href="#" class="hover:text-white transition-colors"><i class="fa-solid fa-arrow-up-right-from-square text-sm"></i></a>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Business Data Automation</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-6">Automated data extraction and reporting pipeline built with Python for stream-lined business operations.</p>
                </div>
                <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-800/50">
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#python</span>
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#automation</span>
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#analytics</span>
                </div>
            </div>

            <!-- React Project -->
            <div class="project-card react glass-card p-6 rounded-2xl flex flex-col justify-between transition-all duration-300" data-aos="fade-up" data-aos-delay="200">
                <div>
                    <div class="flex justify-between items-center mb-4">
                        <span class="text-xs font-bold px-2.5 py-1 rounded-md bg-cyan-950/80 text-cyan-400 border border-cyan-800/50">React / JS</span>
                        <div class="flex gap-3 text-slate-400">
                            <a href="https://x.com/samuel25666" target="_blank" class="hover:text-white transition-colors"><i class="fa-brands fa-github text-lg"></i></a>
                            <a href="#" class="hover:text-white transition-colors"><i class="fa-solid fa-arrow-up-right-from-square text-sm"></i></a>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold mb-2">MUBS Web Dashboard</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-6">A modern, responsive web portal built with React, Tailwind CSS, and dynamic API data binding.</p>
                </div>
                <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-800/50">
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#react</span>
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#tailwind</span>
                    <span class="text-xs text-slate-500 font-mono bg-slate-950 px-2 py-1 rounded">#frontend</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="max-w-4xl mx-auto px-6 py-20 border-t border-slate-900 text-center">
        <div data-aos="fade-up">
            <h2 class="text-3xl font-bold mb-4">Connect with WIZARD PRO</h2>
            <p class="text-slate-400 mb-6 max-w-lg mx-auto">
                Need software developed or looking to collaborate? Reach out to me directly through any of my channels below!
            </p>

            <!-- Phone Numbers -->
            <div class="flex flex-wrap justify-center gap-4 mb-8">
                <a href="tel:0780432448" class="px-4 py-2 rounded-xl glass border border-slate-800 hover:border-cyan-400 text-cyan-400 font-mono text-sm transition-all flex items-center gap-2">
                    <i class="fa-solid fa-phone"></i> +256 780 432 448
                </a>
                <a href="tel:0703342170" class="px-4 py-2 rounded-xl glass border border-slate-800 hover:border-cyan-400 text-cyan-400 font-mono text-sm transition-all flex items-center gap-2">
                    <i class="fa-solid fa-phone"></i> +256 703 342 170
                </a>
            </div>

            <!-- Social Media Buttons -->
            <div class="flex justify-center flex-wrap gap-4 mb-12">
                <!-- X / Twitter -->
                <a href="https://x.com/samuel25666" target="_blank" title="X (Twitter) - @samuel25666" class="w-12 h-12 rounded-full glass flex items-center justify-center hover:border-cyan-400 hover:text-cyan-400 transition-all hover:-translate-y-1">
                    <i class="fa-brands fa-x-twitter text-lg"></i>
                </a>
                <!-- Facebook -->
                <a href="https://facebook.com" target="_blank" title="Facebook - Nowamani Samuel" class="w-12 h-12 rounded-full glass flex items-center justify-center hover:border-cyan-400 hover:text-cyan-400 transition-all hover:-translate-y-1">
                    <i class="fa-brands fa-facebook-f text-lg"></i>
                </a>
                <!-- Instagram -->
                <a href="https://instagram.com/wizardpro123" target="_blank" title="Instagram - wizardpro123" class="w-12 h-12 rounded-full glass flex items-center justify-center hover:border-cyan-400 hover:text-cyan-400 transition-all hover:-translate-y-1">
                    <i class="fa-brands fa-instagram text-lg"></i>
                </a>
                <!-- LinkedIn -->
                <a href="https://linkedin.com" target="_blank" title="LinkedIn - Rwamango Samuel" class="w-12 h-12 rounded-full glass flex items-center justify-center hover:border-cyan-400 hover:text-cyan-400 transition-all hover:-translate-y-1">
                    <i class="fa-brands fa-linkedin-in text-lg"></i>
                </a>
            </div>

            <p class="text-xs text-slate-500 font-mono">
                &copy; <span id="year"></span> WIZARD PRO — Makerere University Business School (MUBS).
            </p>
        </div>
    </section>

    <!-- AOS Animation Library JS -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 800,
            once: true
        });

        document.getElementById('year').textContent = new Date().getFullYear();

        function filterProjects(category) {
            const cards = document.querySelectorAll('.project-card');
            const buttons = document.querySelectorAll('.filter-btn');

            buttons.forEach(btn => {
                btn.classList.remove('bg-indigo-600', 'text-white');
                btn.classList.add('text-slate-400');
            });
            event.target.classList.add('bg-indigo-600', 'text-white');
            event.target.classList.remove('text-slate-400');

            cards.forEach(card => {
                if (category === 'all' || card.classList.contains(category)) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
        }
    </script>
</body>
</html>o
