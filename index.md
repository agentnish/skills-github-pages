<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nish | The Banker's Perspective - Mortgage & Real Estate Authority</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Inter:wght@300;400;600;700&display=swap');
        
        :root {
            --primary: #0f172a;
            --accent: #b99d6b;
        }

        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        h1, h2, h3, .font-serif { font-family: 'Playfair Display', serif; }

        .gold-border { border-color: #b99d6b; }
        .bg-navy { background-color: #0f172a; }
        .text-gold { color: #b99d6b; }
        .btn-gold { 
            background: linear-gradient(135deg, #b99d6b 0%, #8e7345 100%);
            transition: all 0.3s ease;
        }
        .btn-gold:hover { transform: translateY(-2px); box-shadow: 0 10px 15px -3px rgba(185, 157, 107, 0.4); }

        .image-overlay {
            position: relative;
            display: inline-block;
        }
        .image-overlay::after {
            content: '';
            position: absolute;
            top: 20px;
            left: 20px;
            right: -20px;
            bottom: -20px;
            border: 2px solid #b99d6b;
            z-index: -1;
            border-radius: 0.5rem;
        }
    </style>
</head>
<body class="bg-white text-slate-900 overflow-x-hidden">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-slate-100">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex justify-between h-20 items-center">
                <div class="text-xl font-bold tracking-tighter uppercase">
                    <span class="text-navy">Nish</span> <span class="text-gold">| Banker's Perspective</span>
                </div>
                <div class="hidden md:flex space-x-8 items-center text-sm font-semibold tracking-wide">
                    <a href="#bio" class="hover:text-gold transition-colors">MEET NISH</a>
                    <a href="#services" class="hover:text-gold transition-colors">SOLUTIONS</a>
                    <a href="#process" class="hover:text-gold transition-colors">METHODOLOGY</a>
                    <a href="#contact" class="btn-gold text-white px-6 py-2 rounded shadow-md">CONNECT TODAY</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative min-h-screen flex items-center pt-20 bg-slate-50">
        <div class="absolute right-0 top-0 w-1/3 h-full bg-navy hidden lg:block"></div>
        <div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-12 items-center relative z-10">
            <div>
                <span class="text-gold font-bold tracking-[0.3em] uppercase text-xs mb-4 block">10+ Years Institutional Banking Experience</span>
                <h1 class="text-5xl md:text-7xl font-bold text-navy leading-tight mb-6">
                    Commercial <span class="italic font-serif text-gold">Ambition</span>. Residential Dreams.
                </h1>
                <p class="text-lg text-slate-600 mb-10 max-w-lg leading-relaxed">
                    Nish brings the knowledge and insights from the banking vault directly to your real estate portfolio. From retail spaces to your first home, experience financing engineered by an expert.
                </p>
                <div class="flex flex-wrap gap-4">
                    <a href="#contact" class="btn-gold text-white px-8 py-4 rounded font-bold text-sm uppercase tracking-widest shadow-xl">Start Your Journey</a>
                    <a href="#services" class="border border-slate-200 bg-white px-8 py-4 rounded font-bold text-sm uppercase tracking-widest hover:bg-slate-50 transition-all">Commercial & Residential</a>
                </div>
            </div>
            <div class="relative">
                <div class="image-overlay w-full">
                    <img src="Nish-BW-SQ-03-q7ymdi8dc8x3jzr6y68gfly3vyk486cau9l82i3v4s.jpg" 
                         onerror="this.src='https://images.unsplash.com/photo-1560250097-0b93528c311a?auto=format&fit=crop&q=80&w=1000'"
                         alt="Nish - Mortgage & Real Estate Expert" 
                         class="rounded shadow-2xl w-full h-[600px] object-cover">
                </div>
            </div>
        </div>
    </header>

    <!-- The Bio Section -->
    <section id="bio" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid lg:grid-cols-3 gap-16">
                <div class="lg:col-span-1">
                    <h2 class="text-4xl font-bold text-navy mb-6">Versatile <span class="text-gold italic">Expertise</span> for a complex market.</h2>
                    <div class="h-1 w-20 bg-gold mb-8"></div>
                    <p class="text-slate-500 font-medium">Transitioned from Banking to Client Advocacy.</p>
                </div>
                <div class="lg:col-span-2 space-y-6 text-lg text-slate-600 leading-relaxed">
                    <p>
                        Introducing **Nish**, a versatile mortgage expert specializing in commercial and residential financing. With over 10 years of experience in the field, Nish has been instrumental in helping numerous clients achieve their real estate dreams across different domains.
                    </p>
                    <p>
                        Having transitioned from banking to becoming a mortgage and real estate agent, Nish brings deep knowledge and insights to the table. Whether you are searching for commercial properties to fuel your entrepreneurial ambitions or a cozy residential home to call your own, he navigates the complexities with finesse.
                    </p>
                    <p class="font-semibold text-navy">
                        In the commercial realm, Nish thrives on the excitement of securing the funding businesses need to thrive and expand—from retail spaces and office buildings to industrial properties.
                    </p>
                    <div class="pt-8 grid grid-cols-2 gap-8 border-t border-slate-100">
                        <div>
                            <h4 class="text-navy font-bold text-sm uppercase mb-2">Commercial Focus</h4>
                            <p class="text-sm">Retail Spaces, Office Buildings, and Industrial Properties.</p>
                        </div>
                        <div>
                            <h4 class="text-navy font-bold text-sm uppercase mb-2">The Personal Touch</h4>
                            <p class="text-sm">Witnessing the delight of clients as they step into their dream homes.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Dual Service Breakdown -->
    <section id="services" class="py-24 bg-navy text-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-20">
                <h2 class="text-4xl md:text-5xl font-bold mb-4">A Legacy of Success</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Unwavering dedication throughout the entire process, ensuring you find the perfect loan for your unique financial goals.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10">
                <!-- Commercial -->
                <div class="bg-white/5 p-10 rounded-xl border border-white/10 hover:border-gold/50 transition-all group">
                    <i class="fa-solid fa-city text-3xl text-gold mb-6 block"></i>
                    <h3 class="text-2xl font-bold mb-4">Commercial Fuel</h3>
                    <p class="text-slate-400 mb-6 text-sm leading-relaxed">Helping businesses secure the funding to thrive and expand. Nish understands the complexities of commercial debt like an insider.</p>
                    <ul class="text-xs space-y-2 text-slate-300 mb-8 uppercase tracking-widest">
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Retail & Office Spaces</li>
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Industrial Properties</li>
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Business Expansion Loans</li>
                    </ul>
                </div>

                <!-- Residential -->
                <div class="bg-white/5 p-10 rounded-xl border border-white/10 hover:border-gold/50 transition-all">
                    <i class="fa-solid fa-house-chimney text-3xl text-gold mb-6 block"></i>
                    <h3 class="text-2xl font-bold mb-4">Residential Dreams</h3>
                    <p class="text-slate-400 mb-6 text-sm leading-relaxed">Navigating the intricacies of residential mortgages to align with your unique needs. We find the loan that feels like home.</p>
                    <ul class="text-xs space-y-2 text-slate-300 mb-8 uppercase tracking-widest">
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> First-Time Home Buyers</li>
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Premium Refinancing</li>
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Investment Property Debt</li>
                    </ul>
                </div>

                <!-- Advisory -->
                <div class="bg-white/5 p-10 rounded-xl border border-white/10 hover:border-gold/50 transition-all">
                    <i class="fa-solid fa-handshake text-3xl text-gold mb-6 block"></i>
                    <h3 class="text-2xl font-bold mb-4">Trusted Advisory</h3>
                    <p class="text-slate-400 mb-6 text-sm leading-relaxed">Professional guidance for informed decisions. As a licensed realtor and mortgage agent, Nish manages both sides of your real estate journey.</p>
                    <ul class="text-xs space-y-2 text-slate-300 mb-8 uppercase tracking-widest">
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Strategic Property Search</li>
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Expert Negotiation</li>
                        <li><i class="fa-solid fa-check text-gold mr-2"></i> Portfolio Audits</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- The Methodology -->
    <section id="process" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex flex-col lg:flex-row gap-16 items-center">
                <div class="lg:w-1/2">
                    <h2 class="text-4xl font-bold text-navy mb-8">Nish's <span class="italic font-serif text-gold">Path to Approval</span></h2>
                    <div class="space-y-12">
                        <div class="flex gap-6">
                            <span class="text-4xl font-bold text-slate-200">01</span>
                            <div>
                                <h4 class="text-xl font-bold text-navy mb-2">Insider Insight</h4>
                                <p class="text-slate-600">We leverage a decade of banking experience to anticipate underwriter concerns before they even arise.</p>
                            </div>
                        </div>
                        <div class="flex gap-6">
                            <span class="text-4xl font-bold text-slate-200">02</span>
                            <div>
                                <h4 class="text-xl font-bold text-navy mb-2">Custom Alignment</h4>
                                <p class="text-slate-600">No two deals are the same. We find the specific loan product that aligns with your specific 5-year and 10-year goals.</p>
                            </div>
                        </div>
                        <div class="flex gap-6">
                            <span class="text-4xl font-bold text-slate-200">03</span>
                            <div>
                                <h4 class="text-xl font-bold text-navy mb-2">Technical Execution</h4>
                                <p class="text-slate-600">In commercial financing, the magic is in the details. We manage the P&Ls, rent rolls, and appraisals with precision.</p>
                            </div>
                        </div>
                        <div class="flex gap-6">
                            <span class="text-4xl font-bold text-slate-200">04</span>
                            <div>
                                <h4 class="text-xl font-bold text-navy mb-2">Unwavering Support</h4>
                                <p class="text-slate-600">From the first handshake to the key in the lock, Nish provides dedication that lasts well beyond the closing date.</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="contact" class="lg:w-1/2 bg-white p-12 rounded-2xl shadow-2xl border border-slate-100">
                    <div class="text-center">
                        <i class="fa-solid fa-user-tie text-5xl text-gold mb-6"></i>
                        <h3 class="text-3xl font-bold text-navy mb-4">Connect with Nish</h3>
                        <p class="text-slate-500 mb-8">Take the first step towards achieving your real estate aspirations today.</p>
                        <form class="space-y-4 text-left">
                            <div class="grid grid-cols-2 gap-4">
                                <input type="text" placeholder="First Name" class="w-full p-4 bg-slate-50 border border-slate-200 rounded focus:outline-none focus:border-gold">
                                <input type="text" placeholder="Last Name" class="w-full p-4 bg-slate-50 border border-slate-200 rounded focus:outline-none focus:border-gold">
                            </div>
                            <input type="email" placeholder="Preferred Email" class="w-full p-4 bg-slate-50 border border-slate-200 rounded focus:outline-none focus:border-gold">
                            <select class="w-full p-4 bg-slate-50 border border-slate-200 rounded focus:outline-none focus:border-gold text-slate-500">
                                <option>Commercial Financing (Retail/Office/Industrial)</option>
                                <option>Residential Mortgage (Primary/Investment)</option>
                                <option>Real Estate Consultation</option>
                            </select>
                            <textarea placeholder="How can Nish help you today?" rows="4" class="w-full p-4 bg-slate-50 border border-slate-200 rounded focus:outline-none focus:border-gold"></textarea>
                            <button class="w-full btn-gold text-white py-5 rounded font-bold uppercase tracking-widest">Schedule a Call with Nish</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-20 border-t border-slate-100">
        <div class="max-w-7xl mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-12">
                <div class="col-span-2">
                    <div class="text-xl font-bold tracking-tighter uppercase mb-6">
                        <span class="text-navy">Nish</span> <span class="text-gold">| Banker's Perspective</span>
                    </div>
                    <p class="text-slate-500 max-w-sm mb-8">Dedicated expertise in the commercial and residential realms. Navigating the path toward your real estate dreams together.</p>
                </div>
                <div>
                    <h4 class="font-bold text-navy mb-6">Capabilities</h4>
                    <ul class="text-slate-500 space-y-4 text-sm">
                        <li>Retail Financing</li>
                        <li>Office Acquisitions</li>
                        <li>Industrial Mortgages</li>
                        <li>Residential Home Loans</li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold text-navy mb-6">Professional Info</h4>
                    <p class="text-xs text-slate-400 leading-relaxed uppercase tracking-tighter">
                        Nish - Dual-Licensed Agent<br>
                        Mortgage License #1234567<br>
                        Real Estate License #888999<br>
                        Member of [Your Board Name]<br>
                        Licensed through [Brokerage Name]
                    </p>
                </div>
            </div>
            <div class="mt-20 pt-8 border-t border-slate-50 text-center text-slate-400 text-xs">
                &copy; 2024 Nish. All Rights Reserved. Built for GoHighLevel.
            </div>
        </div>
    </footer>

</body>
</html>
