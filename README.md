<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dhruv Kuchekar | Full Stack Dev & AI Builder</title>
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&family=Fira+Code:wght@400;600&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['Fira Code', 'monospace'],
                    },
                    colors: {
                        brand: {
                            purple: '#7C3AED',
                            dark: '#0f0c29',
                            darker: '#0a081a',
                            light: '#e2e8f0',
                        }
                    },
                    animation: {
                        'gradient-x': 'gradient-x 15s ease infinite',
                    },
                    keyframes: {
                        'gradient-x': {
                            '0%, 100%': {
                                'background-size': '200% 200%',
                                'background-position': 'left center'
                            },
                            '50%': {
                                'background-size': '200% 200%',
                                'background-position': 'right center'
                            },
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #0f0c29;
            color: #f8fafc;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: transform 0.3s ease, border-color 0.3s ease;
        }
        .glass-card:hover {
            transform: translateY(-5px);
            border-color: rgba(124, 58, 237, 0.4);
        }
        .gradient-text {
            background: linear-gradient(to right, #a855f7, #ec4899, #8b5cf6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0a081a;
        }
        ::-webkit-scrollbar-thumb {
            background: #7C3AED;
            border-radius: 4px;
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-purple selection:text-white">

    <!-- Navbar -->
    <nav class="fixed w-full z-50 top-0 border-b border-white/5 bg-brand-dark/80 backdrop-blur-md">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex-shrink-0 font-bold text-xl tracking-tighter">
                    <span class="text-white">Dhruv</span><span class="text-brand-purple">.</span>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8 text-sm font-medium">
                        <a href="#about" class="text-gray-300 hover:text-white transition">About</a>
                        <a href="#skills" class="text-gray-300 hover:text-white transition">Skills</a>
                        <a href="#projects" class="text-gray-300 hover:text-white transition">Projects</a>
                        <a href="#contact" class="bg-brand-purple hover:bg-purple-600 text-white px-4 py-2 rounded-lg transition shadow-lg shadow-purple-500/30">Hire Me</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden">
        <div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')] opacity-5"></div>
        <div class="absolute top-0 right-0 w-96 h-96 bg-purple-600 rounded-full mix-blend-multiply filter blur-[128px] opacity-20 animate-pulse"></div>
        <div class="absolute bottom-0 left-0 w-96 h-96 bg-pink-600 rounded-full mix-blend-multiply filter blur-[128px] opacity-20 animate-pulse"></div>
        
        <div class="relative max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/5 border border-white/10 text-sm text-gray-300 mb-6">
                <span class="relative flex h-2 w-2">
                  <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
                  <span class="relative inline-flex rounded-full h-2 w-2 bg-green-500"></span>
                </span>
                Open to SDE & Full Stack Roles
            </div>
            <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight mb-6">
                Hi, I'm Dhruv Kuchekar<br/>
                <span class="gradient-text animate-gradient-x">Full Stack Dev & AI Builder</span>
            </h1>
            <p class="mt-4 max-w-2xl mx-auto text-xl text-gray-400">
                Bridging the gap between intelligent AI models and scalable, user-facing digital products. 🏆 1st Place Winner at VNPS'26.
            </p>
            <div class="mt-10 flex justify-center gap-4">
                <a href="https://github.com/dhruvKuchekar123" target="_blank" class="glass-card px-6 py-3 rounded-lg flex items-center gap-2 hover:bg-white/5 transition">
                    <i class="fab fa-github text-xl"></i> GitHub
                </a>
                <a href="https://www.linkedin.com/in/dhruv-kuchekar-9601501b1/" target="_blank" class="glass-card px-6 py-3 rounded-lg flex items-center gap-2 hover:bg-white/5 transition text-[#0A66C2]">
                    <i class="fab fa-linkedin text-xl"></i> LinkedIn
                </a>
                <a href="mailto:dhruvkuchekar0@gmail.com" class="glass-card px-6 py-3 rounded-lg flex items-center gap-2 hover:bg-white/5 transition text-pink-400">
                    <i class="fas fa-envelope text-xl"></i> Email
                </a>
            </div>
        </div>
    </section>

    <!-- About Code Snippet -->
    <section id="about" class="py-20 bg-brand-darker border-y border-white/5">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center gap-4 mb-10">
                <div class="h-px bg-white/10 flex-1"></div>
                <h2 class="text-2xl font-bold text-gray-200">👨‍💻 About Me</h2>
                <div class="h-px bg-white/10 flex-1"></div>
            </div>
            
            <div class="glass-card rounded-xl overflow-hidden shadow-2xl">
                <div class="flex items-center px-4 py-3 border-b border-white/5 bg-black/40">
                    <div class="flex space-x-2">
                        <div class="w-3 h-3 rounded-full bg-red-500"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500"></div>
                    </div>
                    <div class="ml-4 text-xs text-gray-500 font-mono">dhruv.js</div>
                </div>
                <div class="p-6 overflow-x-auto">
<pre class="font-mono text-sm leading-relaxed">
<span class="text-pink-500">const</span> <span class="text-blue-400">dhruv</span> <span class="text-white">=</span> {
  <span class="text-gray-400">role:</span>             <span class="text-green-400">"Full Stack Developer & AI Builder"</span>,
  <span class="text-gray-400">education:</span>        <span class="text-green-400">"B.E. Computer Engineering, VCET (2022–2026)"</span>,
  <span class="text-gray-400">experience:</span>       [<span class="text-green-400">"Ex-Full Stack Intern @ Inlignhn Global Pvt. Ltd."</span>],
  <span class="text-gray-400">corePhilosophy:</span>   <span class="text-green-400">"Build fast, fail safely, and optimize for scalable business impact."</span>,
  <span class="text-gray-400">aiStack:</span>          [<span class="text-green-400">"n8n Orchestration"</span>, <span class="text-green-400">"LLMs"</span>, <span class="text-green-400">"Agentic Workflows"</span>],
  <span class="text-gray-400">availableForHire:</span> <span class="text-purple-400">true</span>
};
</pre>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="py-20 relative">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-12 text-center">Technical Arsenal</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Frontend -->
                <div class="glass-card p-6 rounded-xl">
                    <div class="w-12 h-12 bg-blue-500/20 text-blue-400 rounded-lg flex items-center justify-center text-2xl mb-4">
                        <i class="fab fa-react"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Frontend & UI</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">React.js</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">JavaScript (ES6+)</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">Tailwind CSS</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">HTML5/CSS3</span>
                    </div>
                </div>

                <!-- Backend -->
                <div class="glass-card p-6 rounded-xl">
                    <div class="w-12 h-12 bg-green-500/20 text-green-400 rounded-lg flex items-center justify-center text-2xl mb-4">
                        <i class="fab fa-node-js"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Backend & DB</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">Node.js</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">Python</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">Express.js</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">MongoDB</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">MySQL</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">REST APIs</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">JWT / RBAC</span>
                    </div>
                </div>

                <!-- AI -->
                <div class="glass-card p-6 rounded-xl border-purple-500/30">
                    <div class="w-12 h-12 bg-purple-500/20 text-purple-400 rounded-lg flex items-center justify-center text-2xl mb-4">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">AI & Automation</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 text-xs rounded-full bg-purple-500/20 border border-purple-500/30 text-purple-300">n8n Workflows</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-purple-500/20 border border-purple-500/30 text-purple-300">AI Agents</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">OpenAI Whisper</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">Gemini Vision</span>
                        <span class="px-3 py-1 text-xs rounded-full bg-white/5 border border-white/10">Prompt Engineering</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-20 bg-brand-darker border-t border-white/5">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-4 text-center">Featured Work</h2>
            <p class="text-gray-400 text-center mb-12 max-w-2xl mx-auto">Architecting full-stack solutions and AI workflows to solve real-world bottlenecks.</p>
            
            <div class="space-y-12">
                <!-- Project 1 -->
                <div class="glass-card rounded-2xl p-6 md:p-8 flex flex-col md:flex-row gap-8 items-center border-l-4 border-l-purple-500">
                    <div class="flex-1 space-y-4">
                        <div class="flex items-center gap-3">
                            <h3 class="text-2xl font-bold">Kaccha Bill Bot</h3>
                            <span class="bg-purple-500/20 text-purple-300 text-xs px-2 py-1 rounded">AI Agent</span>
                        </div>
                        <p class="text-gray-300 font-medium">Agentic Invoice Automation Workflow</p>
                        <p class="text-sm text-gray-400 leading-relaxed">
                            <strong class="text-white">Problem:</strong> Manual entry of messy handwritten shop bills into bookkeeping ledgers is error-prone.<br/>
                            <strong class="text-white">Solution:</strong> Built an agentic workflow using n8n and a Telegram Bot to convert photos into verified digital invoices.<br/>
                            <strong class="text-white">Architecture:</strong> Designed a deterministic rules layer combining Gemini Vision data extraction with a human-in-the-loop safeguard, ensuring the agent fails safely instead of silently trusting AI.
                        </p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="text-xs font-mono text-purple-400">#n8n</span>
                            <span class="text-xs font-mono text-purple-400">#GeminiVision</span>
                            <span class="text-xs font-mono text-purple-400">#TelegramAPI</span>
                        </div>
                        <div class="pt-4">
                            <a href="https://github.com/dhruvKuchekar123/Kaccha-Bill-Bot" target="_blank" class="text-sm hover:text-purple-400 transition flex items-center gap-2"><i class="fab fa-github"></i> View Repository</a>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="glass-card rounded-2xl p-6 md:p-8 flex flex-col md:flex-row gap-8 items-center border-l-4 border-l-pink-500">
                    <div class="flex-1 space-y-4">
                        <div class="flex items-center gap-3">
                            <h3 class="text-2xl font-bold">SyncDub</h3>
                            <span class="bg-pink-500/20 text-pink-300 text-xs px-2 py-1 rounded">🏆 1st Place VNPS'26</span>
                        </div>
                        <p class="text-gray-300 font-medium">AI Audio-Video Dubbing Pipeline</p>
                        <p class="text-sm text-gray-400 leading-relaxed">
                            <strong class="text-white">Problem:</strong> Video localization is highly expensive and manually intensive.<br/>
                            <strong class="text-white">Solution:</strong> Optimized Python AI pipeline for multilingual video dubbing achieving 98% frame-accurate lip sync.<br/>
                            <strong class="text-white">Architecture:</strong> Modular MVC pipeline (Audio Extraction → OpenAI Whisper STT → TTS → Wav2Lip Generation). Reduced localization costs by 80% and PyTorch latency by 40%.
                        </p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="text-xs font-mono text-pink-400">#Python</span>
                            <span class="text-xs font-mono text-pink-400">#OpenAIWhisper</span>
                            <span class="text-xs font-mono text-pink-400">#Wav2Lip</span>
                            <span class="text-xs font-mono text-pink-400">#PyTorch</span>
                        </div>
                        <div class="pt-4">
                            <a href="https://github.com/dhruvKuchekar123/SyncDub-AI-based-Audio-Video-Dubbing-and-Lip-Syncing" target="_blank" class="text-sm hover:text-pink-400 transition flex items-center gap-2"><i class="fab fa-github"></i> View Repository</a>
                        </div>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="glass-card rounded-2xl p-6 md:p-8 flex flex-col md:flex-row gap-8 items-center border-l-4 border-l-blue-500">
                    <div class="flex-1 space-y-4">
                        <div class="flex items-center gap-3">
                            <h3 class="text-2xl font-bold">Wanderlust</h3>
                            <span class="bg-blue-500/20 text-blue-300 text-xs px-2 py-1 rounded">Full Stack MERN</span>
                        </div>
                        <p class="text-gray-300 font-medium">Property Listing Web Application</p>
                        <p class="text-sm text-gray-400 leading-relaxed">
                            <strong class="text-white">Problem:</strong> Need for a seamless, secure, and fast platform for managing property listings and bookings.<br/>
                            <strong class="text-white">Solution:</strong> A production-ready MERN stack platform featuring responsive UIs and robust backend routing.<br/>
                            <strong class="text-white">Architecture:</strong> Developed 10+ REST APIs secured with JWT and RBAC. Integrated Cloudinary for media and Mapbox for location search. Hosted scalable backend on Render.
                        </p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="text-xs font-mono text-blue-400">#MongoDB</span>
                            <span class="text-xs font-mono text-blue-400">#React.js</span>
                            <span class="text-xs font-mono text-blue-400">#Node.js</span>
                            <span class="text-xs font-mono text-blue-400">#TailwindCSS</span>
                        </div>
                        <div class="pt-4 flex gap-6">
                            <a href="https://wanderlust-1-ca6k.onrender.com/signup" target="_blank" class="text-sm hover:text-blue-400 transition flex items-center gap-2"><i class="fas fa-external-link-alt"></i> Live Demo</a>
                            <a href="https://github.com/dhruvKuchekar123/Wanderlust" target="_blank" class="text-sm hover:text-blue-400 transition flex items-center gap-2"><i class="fab fa-github"></i> View Repository</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <section id="contact" class="py-12 border-t border-white/10 bg-black">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-2xl font-bold mb-6">Let's Build Something Together</h2>
            <p class="text-gray-400 mb-8">I am actively looking for Full Stack Developer and SDE roles. My inbox is always open.</p>
            <a href="mailto:dhruvkuchekar0@gmail.com" class="inline-block bg-white text-black font-bold py-3 px-8 rounded-full hover:scale-105 transition transform shadow-lg shadow-white/20">
                Say Hello
            </a>
            
            <div class="mt-12 flex justify-center gap-6 text-gray-500">
                <a href="https://github.com/dhruvKuchekar123" target="_blank" class="hover:text-white transition text-2xl"><i class="fab fa-github"></i></a>
                <a href="https://www.linkedin.com/in/dhruv-kuchekar-9601501b1/" target="_blank" class="hover:text-[#0A66C2] transition text-2xl"><i class="fab fa-linkedin"></i></a>
                <a href="https://wa.me/918080869407" target="_blank" class="hover:text-[#25D366] transition text-2xl"><i class="fab fa-whatsapp"></i></a>
            </div>
            <p class="mt-8 text-xs text-gray-600">&copy; 2026 Dhruv Kuchekar. Built with ❤️ and Code.</p>
        </div>
    </section>

</body>
</html>
