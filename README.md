
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EverydayToolsHQ - Free Online Tools</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@500;600;700&display=swap');
        
        body {
            font-family: 'Inter', system_ui, sans-serif;
            background-color: #ffffff;
            color: #1f2937;
        }
        
        .logo-font {
            font-family: 'Space Grotesk', sans-serif;
        }

        .tool-card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            border: 2px solid #e5e7eb;
        }
        
        .tool-card:hover {
            transform: translateY(-12px) scale(1.05);
            border-color: #3b82f6;
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }

        .rubik-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 2rem;
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <div class="pt-16 pb-20 text-center">
        <div class="max-w-4xl mx-auto px-6">
            <img src="https://everydaytoolshq.github.io/edtlogo.jpg" 
                 alt="EverydayToolsHQ Logo" 
                 class="w-64 h-64 mx-auto mb-8 rounded-3xl shadow-xl">

            <h1 class="logo-font text-6xl md:text-7xl font-bold tracking-tighter mb-4 text-gray-900">
                EverydayToolsHQ
            </h1>
            
            <p class="text-3xl md:text-4xl text-gray-600 font-light max-w-2xl mx-auto">
                Free online tools for everyday decisions
            </p>
        </div>
    </div>

    <!-- Tools Grid -->
    <div class="max-w-7xl mx-auto px-6 pb-24">
        <div class="text-center mb-12">
            <h2 class="text-4xl font-semibold text-gray-800 mb-2">Our Tools</h2>
            <p class="text-gray-500">Click on any square to open the tool</p>
        </div>

        <div class="rubik-grid">
            <!-- Example Tool Cards -->
            <a href="#" class="tool-card bg-white rounded-3xl overflow-hidden group">
                <div class="h-64 bg-gradient-to-br from-blue-500 to-cyan-500 flex items-center justify-center">
                    <i class="fas fa-calculator text-8xl text-white"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-semibold text-2xl mb-1">BMI Calculator</h3>
                    <p class="text-gray-600">Calculate your Body Mass Index instantly.</p>
                    <div class="mt-6 text-blue-600 font-medium group-hover:underline">Open Tool →</div>
                </div>
            </a>

            <a href="#" class="tool-card bg-white rounded-3xl overflow-hidden group">
                <div class="h-64 bg-gradient-to-br from-violet-500 to-purple-600 flex items-center justify-center">
                    <i class="fas fa-key text-8xl text-white"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-semibold text-2xl mb-1">Password Generator</h3>
                    <p class="text-gray-600">Generate strong and secure passwords.</p>
                    <div class="mt-6 text-blue-600 font-medium group-hover:underline">Open Tool →</div>
                </div>
            </a>

            <a href="#" class="tool-card bg-white rounded-3xl overflow-hidden group">
                <div class="h-64 bg-gradient-to-br from-amber-500 to-orange-500 flex items-center justify-center">
                    <i class="fas fa-exchange-alt text-8xl text-white"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-semibold text-2xl mb-1">Unit Converter</h3>
                    <p class="text-gray-600">Convert length, weight, temperature & more.</p>
                    <div class="mt-6 text-blue-600 font-medium group-hover:underline">Open Tool →</div>
                </div>
            </a>

            <a href="#" class="tool-card bg-white rounded-3xl overflow-hidden group">
                <div class="h-64 bg-gradient-to-br from-emerald-500 to-teal-500 flex items-center justify-center">
                    <i class="fas fa-qrcode text-8xl text-white"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-semibold text-2xl mb-1">QR Code Generator</h3>
                    <p class="text-gray-600">Create custom QR codes instantly.</p>
                    <div class="mt-6 text-blue-600 font-medium group-hover:underline">Open Tool →</div>
                </div>
            </a>

            <a href="#" class="tool-card bg-white rounded-3xl overflow-hidden group">
                <div class="h-64 bg-gradient-to-br from-rose-500 to-pink-500 flex items-center justify-center">
                    <i class="fas fa-dollar-sign text-8xl text-white"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-semibold text-2xl mb-1">Loan Calculator</h3>
                    <p class="text-gray-600">Calculate EMI and total interest.</p>
                    <div class="mt-6 text-blue-600 font-medium group-hover:underline">Open Tool →</div>
                </div>
            </a>

            <a href="#" class="tool-card bg-white rounded-3xl overflow-hidden group">
                <div class="h-64 bg-gradient-to-br from-sky-500 to-blue-600 flex items-center justify-center">
                    <i class="fas fa-birthday-cake text-8xl text-white"></i>
                </div>
                <div class="p-6">
                    <h3 class="font-semibold text-2xl mb-1">Age Calculator</h3>
                    <p class="text-gray-600">Calculate exact age in years, months & days.</p>
                    <div class="mt-6 text-blue-600 font-medium group-hover:underline">Open Tool →</div>
                </div>
            </a>
        </div>
    </div>

    <!-- Footer -->
    <footer style="margin-top:60px;padding:20px 0;border-top:1px solid #ddd;text-align:center;font-size:14px; background-color: #f9fafb;">
        <div style="max-width: 1200px; margin: 0 auto; padding: 0 20px;">
            <div style="margin-bottom:10px;">
                <strong>EverydayToolsHQ</strong>
            </div>

            <div style="margin-bottom:10px;">
                <a href="/" style="margin:0 8px; color: #374151; text-decoration: none;">Home</a>
                <a href="/about/" style="margin:0 8px; color: #374151; text-decoration: none;">About</a>
            </div>

            <div style="margin-bottom:10px;">
                <a href="https://powerstationhq.com/privacy-policy/" target="_blank" style="color: #374151; text-decoration: none;">Privacy Policy</a> |
                <a href="https://powerstationhq.com/terms-and-conditions/" target="_blank" style="color: #374151; text-decoration: none;">Terms</a> |
                <a href="https://powerstationhq.com/affiliate-disclosure/" target="_blank" style="color: #374151; text-decoration: none;">Affiliate Disclosure</a>
            </div>

            <div style="margin-top:10px;">
                Powered by
                <a href="https://powerstationhq.com/" target="_blank" style="color: #2563eb; font-weight: bold; text-decoration: none;">PowerstationHQ</a>
            </div>
        </div>
    </footer>

</body>
</html>
