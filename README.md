<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reaksa </title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #1c1917; color: #f5f5f4; }
        .hero-gradient {
            background: radial-gradient(circle at center, rgba(120, 53, 15, 0.2) 0%, rgba(28, 25, 23, 1) 70%);
        }
        #progress-bar {
            height: 100%; background: #d97706; width: 0%; transition: width 0.1s ease;
        }
    </style>
</head>
<body class="font-sans antialiased">

    <div class="fixed top-0 left-0 w-full h-1 z-[100] bg-stone-900">
        <div id="progress-bar"></div>
    </div>

    <nav class="fixed top-6 left-1/2 -translate-x-1/2 z-50 w-[90%] md:w-auto">
        <div class="bg-stone-900/90 backdrop-blur-md border border-stone-700/50 px-8 py-3 rounded-full flex justify-center gap-8 text-sm font-medium text-stone-400 shadow-xl">
            <a href="#home" class="hover:text-amber-500 transition">Home</a>
            <a href="#about" class="hover:text-amber-500 transition">About</a>
            <a href="#projects" class="hover:text-amber-500 transition">Projects</a>
            <a href="#experience" class="hover:text-amber-500 transition">Experience</a>
            <a href="#skills" class="hover:text-amber-500 transition">Skills</a>   
            <a href="#contact" class="hover:text-amber-500 transition">Contact</a>
        </div>
    </nav>

    <section id="home" class="hero-gradient min-h-screen flex flex-col items-center justify-center text-center px-4">
        <div class="w-40 h-40 rounded-full border-4 border-stone-700 overflow-hidden mb-8 shadow-2xl ring-4 ring-amber-900/20">
            <img src="photo_2025-12-27_20-15-24.jpg" alt="Reaksa" class="w-full h-full object-cover">
        </div>
        <h1 class="text-6xl md:text-8xl font-bold mb-4 tracking-tight text-stone-100"><span class="text-amber-600">Reaksa</span></h1>
        <p class="text-xl md:text-2xl text-stone-400 max-w-2xl leading-relaxed italic mb-10">
            I AM A STUDENT
        </p>
        <div class="flex gap-10 text-3xl">
            <a href="YOUR_LINKEDIN_LINK" target="_blank" class="text-stone-500 hover:text-amber-500 transition-all"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://t.me/YOUR_USERNAME" target="_blank" class="text-stone-500 hover:text-amber-500 transition-all"><i class="fa-brands fa-telegram"></i></a>
        </div>
    </section>

    <section id="about" class="py-32 max-w-4xl mx-auto px-6">
        <h2 class="text-3xl font-bold text-center mb-16 text-amber-100 tracking-widest uppercase">About Me</h2>
        <div class="flex flex-col md:flex-row items-center gap-12">
            <div class="w-full max-w-sm rounded-2xl overflow-hidden shadow-2xl border border-stone-800">
                <img src="2026.jpg" alt="Reaksa" class="w-full transition duration-700">

            </div>
            <div class="space-y-6 text-stone-400 text-lg">
                <p>
                     Hello i  am Reaksa, i'm a student M1 Year3 samester1 at Royal University of Phome Penh.
                </p>
                
            </div>
        </div>
    </section>

    <section id="projects" class="py-32 max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold text-center mb-16 text-amber-100 tracking-widest uppercase">Projects</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
            <div class="bg-stone-900/60 border border-stone-800 rounded-3xl overflow-hidden group">
                <img src="1.jpg" alt="Login Application" class="w-full h-56 object-cover opacity-70 group-hover:opacity-100 transition duration-500">
                <div class="p-8">
                    <h3 class="text-2xl font-bold text-amber-500 mb-2">Java Login App</h3>
                    <p class="text-stone-400 text-sm mb-6">A secure desktop interface featuring Java Swing UI and authentication logic.</p>
                    <div class="flex gap-2">
                        <span class="px-3 py-1 bg-stone-800 text-amber-400 text-[10px] font-bold rounded-full">JAVA SWING</span>
                    </div>
                </div>
            </div>
            <div class="bg-stone-900/60 border border-stone-800 rounded-3xl overflow-hidden group">
                <img src="2.jpg" alt="Student System" class="w-full h-56 object-cover opacity-70 group-hover:opacity-100 transition duration-500">
                <div class="p-8">
                    <h3 class="text-2xl font-bold text-amber-500 mb-2">Student Database System</h3>
                    <p class="text-stone-400 text-sm mb-6">A management tool utilizing SQL to organize, store, and retrieve student information.</p>
                    <div class="flex gap-2">
                        <span class="px-3 py-1 bg-stone-800 text-amber-400 text-[10px] font-bold rounded-full">SQL DATABASE</span>
                    </div>
                </div>
            </div>

            <div class="bg-stone-900/60 border border-stone-800 rounded-3xl overflow-hidden group">
                <img src="3.jpg" alt="Student System" class="w-full h-56 object-cover opacity-70 group-hover:opacity-100 transition duration-500">
                <div class="p-8">
                    <h3 class="text-2xl font-bold text-amber-500 mb-2">ISA project</h3>
                    <p class="text-stone-400 text-sm mb-6">Data aflow Diagram.</p>
                    <div class="flex gap-2">
                        <span class="px-3 py-1 bg-stone-800 text-amber-400 text-[10px] font-bold rounded-full">ISA </span>
                    </div>
                </div>
            </div>
        </div>
    </section>
<section id="experience" class="py-32 bg-stone-900/20">
    <div class="max-w-5xl mx-auto px-6">
        <h2 class="text-3xl font-bold text-center mb-20 text-amber-100 tracking-widest uppercase">My Experience</h2>
        
        <div class="relative timeline-line space-y-16">
            
            <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
                <div class="flex items-center justify-center w-12 h-12 rounded-full border-4 border-stone-900 bg-amber-700 text-white z-10 md:absolute md:left-1/2 md:-translate-x-1/2 shadow-xl">
                    <i class="fa-solid fa-users-rectangle"></i>
                </div>
                <div class="w-[calc(100%-3.5rem)] md:w-[45%] p-8 rounded-2xl border border-stone-800 bg-stone-900/60 shadow-lg hover:border-amber-600 transition">
                    <h4 class="font-bold text-xl text-amber-100">Class Projects</h4>
                    <p class="text-amber-600 font-semibold mb-4 text-sm italic">Team Assignments</p>
                    <p class="text-stone-400 text-sm leading-relaxed">
                        Worked with team members to build real-world applications. We followed project requirements from our teacher to create functional software using.
                    </p>
                </div>
            </div>

            <div class="relative flex items-center justify-between md:justify-normal group">
                <div class="flex items-center justify-center w-12 h-12 rounded-full border-4 border-stone-900 bg-stone-700 text-white z-10 md:absolute md:left-1/2 md:-translate-x-1/2 shadow-xl">
                    <i class="fa-solid fa-code-commit"></i>
                </div>
                <div class="w-[calc(100%-3.5rem)] md:w-[45%] p-8 rounded-2xl border border-stone-800 bg-stone-900/60 shadow-lg hover:border-amber-600 transition">
                    <h4 class="font-bold text-xl text-amber-100">Assignments</h4>
                    <p class="text-amber-600 font-semibold mb-4 text-sm italic"></p>
                    <p class="text-stone-400 text-sm leading-relaxed">
                        Completed advanced  assignments  queries given by teachers.
                    </p>
                </div>
            </div>

        </div>
    </div>
    <section id="skills" class="py-24 bg-stone-900/40 border-y border-stone-800">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-16 text-amber-100 tracking-widest uppercase">My Skills</h2>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="p-8 bg-stone-800/40 rounded-3xl border border-stone-700 hover:border-amber-600 transition-all duration-300 group shadow-lg">
                    <i class="fa-brands fa-java text-5xl mb-4 text-stone-500 group-hover:text-amber-600 transition-colors"></i>
                    <h3 class="font-bold text-stone-200 text-lg">Java</h3>
                    <p class="text-[10px] text-stone-500 mt-2 uppercase tracking-tighter"></p>
                </div>

                <div class="p-8 bg-stone-800/40 rounded-3xl border border-stone-700 hover:border-amber-600 transition-all duration-300 group shadow-lg">
                    <i class="fa-solid fa-database text-5xl mb-4 text-stone-500 group-hover:text-amber-600 transition-colors"></i>
                    <h3 class="font-bold text-stone-200 text-lg">SQL</h3>
                    <p class="text-[10px] text-stone-500 mt-2 uppercase tracking-tighter"></p>
                </div>

                <div class="p-8 bg-stone-800/40 rounded-3xl border border-stone-700 hover:border-amber-600 transition-all duration-300 group shadow-lg">
                    <i class="fa-brands fa-html5 text-5xl mb-4 text-stone-500 group-hover:text-amber-600 transition-colors"></i>
                    <h3 class="font-bold text-stone-200 text-lg">HTML</h3>
                    <p class="text-[10px] text-stone-500 mt-2 uppercase tracking-tighter"></p>
                </div>

                <div class="p-8 bg-stone-800/40 rounded-3xl border border-stone-700 hover:border-amber-600 transition-all duration-300 group shadow-lg">
                    <i class="fa-brands fa-css3-alt text-5xl mb-4 text-stone-500 group-hover:text-amber-600 transition-colors"></i>
                    <h3 class="font-bold text-stone-200 text-lg">CSS</h3>
                    <p class="text-[10px] text-stone-500 mt-2 uppercase tracking-tighter"></p>
                </div>
                
                <div class="p-8 bg-stone-800/40 rounded-3xl border border-stone-700 hover:border-amber-600 transition-all duration-300 group shadow-lg">
                    <i class="fa-brands fa-python text-5xl mb-4 text-stone-500 group-hover:text-amber-600 transition-colors"></i>
                    <h3 class="font-bold text-stone-200 text-lg">PYTHON</h3>
                    <p class="text-[10px] text-stone-500 mt-2 uppercase tracking-tighter"></p>
                </div>
            </div>
        </div>
    </section>
</section>
    <section id="contact" class="py-32 max-w-xl mx-auto px-6 text-center">
        <h2 class="text-3xl font-bold mb-10 text-amber-100 uppercase tracking-widest">Connect</h2>
        <div class="flex flex-col gap-4">
            <a href="https://t.me/Reaksa_koem" target="_blank" class="w-full py-5 bg-amber-700 hover:bg-amber-600 text-white rounded-2xl font-bold transition-all shadow-lg flex items-center justify-center gap-3">
                <i class="fa-brands fa-telegram text-2xl"></i> Telegram
            </a>
            <a href="https://www.linkedin.com/in/koem-reaksa-689b15363?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank" class="w-full py-5 bg-stone-800 hover:bg-stone-700 text-white rounded-2xl font-bold transition-all border border-stone-700 flex items-center justify-center gap-3">
                <i class="fa-brands fa-linkedin text-2xl"></i> LinkedIn
            </a>
        </div>
    </section>

    <footer class="py-12 text-center text-stone-600 text-[11px] border-t border-stone-900 tracking-[0.2em]">
        © 2026 REAKSA | JAVA & SQL DEVELOPER
    </footer>

    <script>
        window.onscroll = function() {
            let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
            let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            let scrolled = (winScroll / height) * 100;
            document.getElementById("progress-bar").style.width = scrolled + "%";
        };
    </script>
</body>
</html>
