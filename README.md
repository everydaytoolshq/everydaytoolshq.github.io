<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EverydayToolsHQ - Free Online Tools</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@500;600;700&display=swap');
        
        :root {
            --primary: #3b82f6;
        }
        
        body {
            font-family: 'Inter', system_ui, sans-serif;
        }
        
        .logo-font {
            font-family: 'Space Grotesk', sans-serif;
        }

        .hero-bg {
            background: linear-gradient(135deg, #0f172a 0%, #1e2937 100%);
        }

        .tool-card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .tool-card:hover {
            transform: translateY(-12px) scale(1.05);
            box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.4);
        }

        .rubik-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .hero-logo {
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }
    </style>
</head>
<body class="bg-zinc-950 text-white">
    <!-- Navbar -->
    <nav class="border-b border-zinc-800 bg-zinc-950/80 backdrop-blur-md fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <img src="https://everydaytoolshq.github.io/edtlogo.jpg" alt="EverydayToolsHQ Logo" class="w-9 h-9 rounded-2xl">
                <span class="logo-font text-2xl font-semibold tracking-tighter">EverydayToolsHQ</span>
            </div>
            <div class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="#" class="hover:text-blue-400 transition-colors">Tools</a>
                <a href="#" class="hover:text-blue-400 transition-colors">Blog</a>
                <a href="/about/" class="hover:text-blue-400 transition-colors">About</a>
            </div>
            <a href="#" 
               class="px-6 py-2.5 bg-white text-zinc-900 rounded-2xl font-semibold text-sm hover:bg-blue-400 hover:text-white transition-all flex items-center gap-2">
                <i class="fas fa-plus"></i>
                Suggest a Tool
            </a>
        </div>
    </nav>

    <!-- Hero -->
    <section class="hero-bg pt-32 pb-24">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <div class="flex justify-center mb-8">
                <img src="https://everydaytoolshq.github.io/edtlogo.jpg" 
                     alt="EverydayToolsHQ" 
                     class="hero-logo w-48 h-48 object-contain rounded-3xl shadow-2xl border border-white/10">
            </div>
            
            <h1 class="text-6xl md:text-7xl font-bold tracking-tighter logo-font mb-6">
                Everyday Tools.<br>
                <span class="bg-gradient-to-r from-blue-400 to-cyan-400 bg-clip-text text-transparent">Instant Answers.</span>
            </h1>
            
            <p class="text-2xl text-zinc-400 max-w-2xl mx-auto mb-10">
                Free online tools for everyday decisions
            </p>
            
            <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
                <a href="#tools" 
                   class="px-10 py-4 bg-blue-600 hover:bg-blue-500 rounded-3xl font-semibold text-lg flex items-center gap-3 transition-all">
                    <i class="fas fa-tools"></i>
                    Explore All Tools
                </a>
                <a href="#" 
                   class="px-10 py-4 border border-white/30 hover:border-white/60 rounded-3xl font-medium text-lg transition-all">
                    Watch 45-second demo
                </a>
            </div>
            
            <div class="mt-16 flex justify-center gap-8 text-sm text-zinc-500">
                <div class="flex items-center gap-2">
                    <i class="fas fa-check text-emerald-400"></i>
                    No sign-up
                </div>
                <div class="flex items-center gap-2">
                    <i class="fas fa-check text-emerald-400"></i>
                    Works offline
                </div>
                <div class="flex items-center gap-2">
                    <i class="fas fa-check text-emerald-400"></i>
                    100% Private
                </div>
            </div>
        </div>
    </section>

    <!-- Tools Grid -->
    <section id="tools" class="py-20 bg-zinc-900">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-12">
                <span class="inline-block px-4 py-2 bg-zinc-800 rounded-full text-sm font-medium tracking-widest mb-3">TOOLS COLLECTION</span>
                <h2 class="text-5xl font-bold tracking-tighter logo-font">Built like a Rubik's Cube</h2>
                <p class="text-zinc-400 mt-3 text-lg">Click any square to solve your everyday problems</p>
            </div>

            <div class="rubik-grid">
                <!-- Tool 1 -->
                <a href="#" class="tool-card group bg-zinc-800 rounded-3xl overflow-hidden border border-zinc-700 hover:border-blue-500">
                    <div class="h-64 bg-gradient-to-br from-blue-500 to-cyan-500 flex items-center justify-center relative">
                        <i class="fas fa-calculator text-8xl text-white/90"></i>
                        <div class="absolute top-4 right-4 bg-black/60 text-white text-xs px-3 py-1 rounded-full">New</div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-2xl mb-1">BMI Calculator</h3>
                        <p class="text-zinc-400 text-sm line-clamp-2">Check your Body Mass Index and get health insights instantly.</p>
                        <div class="mt-6 flex items-center justify-between text-sm">
                            <span class="text-blue-400 font-medium group-hover:underline">Open Tool →</span>
                            <span class="text-emerald-400 text-xs">• Health</span>
                        </div>
                    </div>
                </a>

                <!-- Tool 2 -->
                <a href="#" class="tool-card group bg-zinc-800 rounded-3xl overflow-hidden border border-zinc-700 hover:border-violet-500">
                    <div class="h-64 bg-gradient-to-br from-violet-500 to-purple-600 flex items-center justify-center">
                        <i class="fas fa-key text-8xl text-white/90"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-2xl mb-1">Password Generator</h3>
                        <p class="text-zinc-400 text-sm line-clamp-2">Create strong, secure passwords in seconds.</p>
                        <div class="mt-6 flex items-center justify-between text-sm">
                            <span class="text-violet-400 font-medium group-hover:underline">Open Tool →</span>
                            <span class="text-emerald-400 text-xs">• Security</span>
                        </div>
                    </div>
                </a>

                <!-- Tool 3 -->
                <a href="#" class="tool-card group bg-zinc-800 rounded-3xl overflow-hidden border border-zinc-700 hover:border-amber-500">
                    <div class="h-64 bg-gradient-to-br from-amber-500 to-orange-500 flex items-center justify-center">
                        <i class="fas fa-exchange-alt text-8xl text-white/90 rotate-12"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-2xl mb-1">Unit Converter</h3>
                        <p class="text-zinc-400 text-sm line-clamp-2">Convert between length, weight, temperature &amp; more.</p>
                        <div class="mt-6 flex items-center justify-between text-sm">
                            <span class="text-amber-400 font-medium group-hover:underline">Open Tool →</span>
                            <span class="text-emerald-400 text-xs">• Utility</span>
                        </div>
                    </div>
                </a>

                <!-- Tool 4 -->
                <a href="#" class="tool-card group bg-zinc-800 rounded-3xl overflow-hidden border border-zinc-700 hover:border-rose-500">
                    <div class="h-64 bg-gradient-to-br from-rose-500 to-pink-500 flex items-center justify-center">
                        <i class="fas fa-dollar-sign text-8xl text-white/90"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-2xl mb-1">Loan Calculator</h3>
                        <p class="text-zinc-400 text-sm line-clamp-2">Calculate monthly payments and total interest.</p>
                        <div class="mt-6 flex items-center justify-between text-sm">
                            <span class="text-rose-400 font-medium group-hover:underline">Open Tool →</span>
                            <span class="text-emerald-400 text-xs">• Finance</span>
                        </div>
                    </div>
                </a>

                <!-- Tool 5 -->
                <a href="#" class="tool-card group bg-zinc-800 rounded-3xl overflow-hidden border border-zinc-700 hover:border-emerald-500">
                    <div class="h-64 bg-gradient-to-br from-emerald-500 to-teal-500 flex items-center justify-center">
                        <i class="fas fa-qrcode text-8xl text-white/90"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-2xl mb-1">QR Code Generator</h3>
                        <p class="text-zinc-400 text-sm line-clamp-2">Create beautiful QR codes for links, WiFi, and more.</p>
                        <div class="mt-6 flex items-center justify-between text-sm">
                            <span class="text-emerald-400 font-medium group-hover:underline">Open Tool →</span>
                            <span class="text-emerald-400 text-xs">• Utility</span>
                        </div>
                    </div>
                </a>

                <!-- Tool 6 -->
                <a href="#" class="tool-card group bg-zinc-800 rounded-3xl overflow-hidden border border-zinc-700 hover:border-sky-500">
                    <div class="h-64 bg-gradient-to-br from-sky-500 to-blue-500 flex items-center justify-center">
                        <i class="fas fa-birthday-cake text-8xl text-white/90"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-2xl mb-1">Age Calculator</h3>
                        <p class="text-zinc-400 text-sm line-clamp-2">Find exact age in years, months, and days.</p>
                        <div class="mt-6 flex items-center justify-between text-sm">
                            <span class="text-sky-400 font-medium group-hover:underline">Open Tool →</span>
                            <span class="text-emerald-400 text-xs">• Fun</span>
                        </div>
                    </div>
                </a>
            </div>

            <div class="text-center mt-12">
                <a href="#" class="inline-flex items-center gap-2 text-blue-400 hover:text-blue-300 font-medium">
                    See all 50+ tools 
                    <span class="text-xl">→</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="py-20 bg-gradient-to-b from-zinc-900 to-zinc-950 border-t border-zinc-800">
        <div class="max-w-4xl mx-auto text-center px-6">
            <h2 class="text-4xl font-bold tracking-tight mb-4">Need a tool we don't have yet?</h2>
            <p class="text-zinc-400 mb-8">We're constantly adding new tools based on community requests.</p>
            <button onclick="alert('Thank you! Suggestion form would open here.')"
                    class="px-8 py-4 bg-white text-zinc-900 rounded-3xl font-semibold hover:scale-105 transition-transform flex items-center gap-3 mx-auto">
                <i class="fas fa-lightbulb"></i>
                Suggest a New Tool
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer style="margin-top:60px;padding:20px 0;border-top:1px solid #ddd;text-align:center;font-size:14px; background-color: #18181b; color: #a1a1aa;">
        <div style="max-width: 1200px; margin: 0 auto; padding: 0 20px;">
            <div style="margin-bottom:10px;">
                <strong>EverydayToolsHQ</strong>
            </div>

            <div style="margin-bottom:10px;">
                <a href="/" style="margin:0 8px; color: #a1a1aa; text-decoration: none;">Home</a>
                <a href="/about/" style="margin:0 8px; color: #a1a1aa; text-decoration: none;">About</a>
            </div>

            <div style="margin-bottom:10px;">
                <a href="https://powerstationhq.com/privacy-policy/" target="_blank" style="color: #a1a1aa; text-decoration: none;">Privacy Policy</a> |
                <a href="https://powerstationhq.com/terms-and-conditions/" target="_blank" style="color: #a1a1aa; text-decoration: none;">Terms</a> |
                <a href="https://powerstationhq.com/affiliate-disclosure/" target="_blank" style="color: #a1a1aa; text-decoration: none;">Affiliate Disclosure</a>
            </div>

            <div style="margin-top:10px;">
                Powered by
                <a href="https://powerstationhq.com/" target="_blank" style="color: #60a5fa; font-weight: bold; text-decoration: none;">PowerstationHQ</a>
            </div>
        </div>
    </footer>

    <script>
        // Tailwind script already included via CDN
        console.log('%cEverydayToolsHQ Loaded ✨', 'color:#3b82f6; font-family:monospace; font-size:13px');
    </script>
</body>
</html>
