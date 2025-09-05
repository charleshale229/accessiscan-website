# accessiscan-website<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AccessiScan - Website Accessibility Compliance Scanner | Avoid ADA Lawsuits</title>
    <meta name="description" content="Protect your business from ADA lawsuits with automated website accessibility scanning. 96% of websites fail compliance. Start free trial today.">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>
    
    <!-- Custom Styles -->
    <style>
        /* Custom gradient background */
        .gradient-bg {
            background: linear-gradient(135deg, #7c3aed 0%, #6d28d9 50%, #4338ca 100%);
        }
        
        /* Glassmorphism effect */
        .glass {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        /* Smooth scrolling */
        html {
            scroll-behavior: smooth;
        }
        
        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .fade-in-up {
            animation: fadeInUp 0.6s ease-out;
        }
        
        /* Button hover effects */
        .btn-primary {
            background: #fbbf24;
            color: #000;
            transition: all 0.3s ease;
        }
        
        .btn-primary:hover {
            background: #f59e0b;
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(251, 191, 36, 0.3);
        }
        
        .btn-secondary {
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.3);
            transition: all 0.3s ease;
        }
        
        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-2px);
        }
        
        /* Card hover effects */
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
        }
        
        /* Pricing card special styling */
        .pricing-popular {
            transform: scale(1.05);
            border: 2px solid #fbbf24;
        }
        
        /* Loading animation */
        @keyframes spin {
            to {
                transform: rotate(360deg);
            }
        }
        
        .animate-spin {
            animation: spin 1s linear infinite;
        }
        
        /* Counter animation */
        .counter {
            font-variant-numeric: tabular-nums;
        }
    </style>
</head>
<body class="gradient-bg min-h-screen">
    <!-- Header -->
    <header class="glass sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i data-lucide="shield" class="h-8 w-8 text-white"></i>
                <span class="text-2xl font-bold text-white">AccessiScan</span>
            </div>
            <div class="hidden md:flex items-center space-x-6">
                <a href="#features" class="text-white/90 hover:text-white transition-colors">Features</a>
                <a href="#pricing" class="text-white/90 hover:text-white transition-colors">Pricing</a>
                <a href="#testimonials" class="text-white/90 hover:text-white transition-colors">Reviews</a>
                <button class="btn-secondary px-6 py-2 rounded-lg font-medium">
                    Start Free Trial
                </button>
            </div>
            <!-- Mobile menu button -->
            <button id="mobile-menu-btn" class="md:hidden text-white">
                <i data-lucide="menu" class="h-6 w-6"></i>
            </button>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white/10 backdrop-blur-md border-t border-white/20">
            <div class="px-4 py-4 space-y-4">
                <a href="#features" class="block text-white/90 hover:text-white transition-colors">Features</a>
                <a href="#pricing" class="block text-white/90 hover:text-white transition-colors">Pricing</a>
                <a href="#testimonials" class="block text-white/90 hover:text-white transition-colors">Reviews</a>
                <button class="btn-secondary w-full px-6 py-2 rounded-lg font-medium">
                    Start Free Trial
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="container mx-auto px-4 py-16 text-center text-white fade-in-up">
        <div class="max-w-4xl mx-auto">
            <div class="inline-flex items-center bg-red-500/20 text-red-100 border border-red-400/30 rounded-full px-4 py-2 mb-6">
                <i data-lucide="alert-triangle" class="h-4 w-4 mr-2"></i>
                8,800+ ADA Lawsuits Filed in 2024
            </div>
            
            <h1 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">
                Don't Be the Next
                <span class="text-yellow-300"> ADA Lawsuit</span>
            </h1>
            
            <p class="text-xl md:text-2xl mb-8 text-white/90 leading-relaxed">
                96% of websites fail accessibility compliance. Protect your business with automated WCAG 2.1 scanning and avoid costly $15,000 settlements.
            </p>

            <div class="flex flex-col sm:flex-row gap-4 justify-center mb-12">
                <button class="btn-primary text-lg px-8 py-4 rounded-lg font-semibold inline-flex items-center justify-center">
                    Start Free 14-Day Trial
                    <i data-lucide="arrow-right" class="ml-2 h-5 w-5"></i>
                </button>
                <button class="btn-secondary text-lg px-8 py-4 rounded-lg font-semibold inline-flex items-center justify-center">
                    Watch Demo (2 min)
                </button>
            </div>

            <div class="flex flex-col sm:flex-row items-center justify-center space-y-2 sm:space-y-0 sm:space-x-8 text-sm text-white/80">
                <div class="flex items-center">
                    <i data-lucide="check-circle" class="h-4 w-4 mr-2 text-green-400"></i>
                    No Credit Card Required
                </div>
                <div class="flex items-center">
                    <i data-lucide="check-circle" class="h-4 w-4 mr-2 text-green-400"></i>
                    Setup in 2 Minutes
                </div>
                <div class="flex items-center">
                    <i data-lucide="check-circle" class="h-4 w-4 mr-2 text-green-400"></i>
                    Cancel Anytime
                </div>
            </div>
        </div>
    </section>

    <!-- Live Demo Section -->
    <section class="container mx-auto px-4 py-16">
        <div class="max-w-2xl mx-auto bg-white/95 backdrop-blur-sm shadow-2xl rounded-2xl p-8">
            <div class="text-center mb-6">
                <h2 class="text-2xl font-bold text-gray-800 mb-2">
                    Try AccessiScan Free - Scan Your Website Now
                </h2>
                <p class="text-lg text-gray-600">
                    Get instant accessibility compliance report in 30 seconds
                </p>
            </div>
            
            <div class="space-y-4">
                <div>
                    <label for="url" class="block text-base font-medium text-gray-700 mb-2">Website URL</label>
                    <input
                        id="url"
                        type="url"
                        placeholder="https://yourwebsite.com"
                        class="w-full text-lg py-3 px-4 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                    />
                </div>
                <button 
                    id="scan-btn"
                    class="w-full bg-purple-600 hover:bg-purple-700 text-white text-lg py-3 px-4 rounded-lg font-semibold transition-all duration-300 flex items-center justify-center"
                >
                    <i data-lucide="zap" class="mr-2 h-5 w-5"></i>
                    Scan for Accessibility Issues
                </button>
                <p class="text-center text-sm text-gray-600">
                    Join <span id="customer-count" class="counter font-semibold">487</span>+ businesses protecting themselves from ADA lawsuits
                </p>
            </div>
        </div>
    </section>

    <!-- Social Proof Stats -->
    <section class="glass py-16">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center text-white">
                <div class="fade-in-up">
                    <div class="text-4xl font-bold text-yellow-300 mb-2">96%</div>
                    <div class="text-white/80">Websites Fail Compliance</div>
                </div>
                <div class="fade-in-up">
                    <div class="text-4xl font-bold text-yellow-300 mb-2">$15K</div>
                    <div class="text-white/80">Average Lawsuit Cost</div>
                </div>
                <div class="fade-in-up">
                    <div class="text-4xl font-bold text-yellow-300 mb-2">8,800+</div>
                    <div class="text-white/80">Lawsuits in 2024</div>
                </div>
                <div class="fade-in-up">
                    <div class="text-4xl font-bold text-yellow-300 mb-2 counter" id="stat-counter">487+</div>
                    <div class="text-white/80">Protected Businesses</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="container mx-auto px-4 py-16">
        <div class="text-center mb-16 fade-in-up">
            <h2 class="text-4xl font-bold text-white mb-4">
                Why Choose AccessiScan?
            </h2>
            <p class="text-xl text-white/80 max-w-2xl mx-auto">
                Built on axe-core, the industry-standard accessibility testing engine trusted by millions of developers
            </p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
            <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                <i data-lucide="zap" class="h-12 w-12 text-yellow-400 mb-4"></i>
                <h3 class="text-xl font-bold mb-4">Fast & Accurate</h3>
                <p class="text-white/80">
                    Powered by axe-core, finds 57% of accessibility issues automatically. Complete scans in under 30 seconds.
                </p>
            </div>

            <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                <i data-lucide="bar-chart-3" class="h-12 w-12 text-blue-400 mb-4"></i>
                <h3 class="text-xl font-bold mb-4">Detailed Reports</h3>
                <p class="text-white/80">
                    Get comprehensive reports with specific issues, impact levels, and step-by-step remediation guidance.
                </p>
            </div>

            <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                <i data-lucide="shield" class="h-12 w-12 text-green-400 mb-4"></i>
                <h3 class="text-xl font-bold mb-4">Legal Protection</h3>
                <p class="text-white/80">
                    Ensure compliance with ADA, WCAG 2.1, and Section 508 requirements to avoid costly lawsuits.
                </p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="bg-white/5 backdrop-blur-md py-16">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16 fade-in-up">
                <h2 class="text-4xl font-bold text-white mb-4">
                    Trusted by 500+ Businesses
                </h2>
                <p class="text-xl text-white/80">
                    See how AccessiScan has protected businesses from lawsuits and expanded their reach
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                    <div class="flex items-center space-x-1 mb-4">
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                    </div>
                    <p class="text-white/80 text-base mb-6">
                        "AccessiScan saved us from a potential $15,000 lawsuit. The automated scanning caught issues our developers missed."
                    </p>
                    <div>
                        <div class="font-semibold">Sarah Chen</div>
                        <div class="text-sm text-white/60">CEO, TechStart Solutions</div>
                    </div>
                </div>

                <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                    <div class="flex items-center space-x-1 mb-4">
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                    </div>
                    <p class="text-white/80 text-base mb-6">
                        "We've avoided 3 ADA lawsuits since implementing AccessiScan. It's essential for any business with a website."
                    </p>
                    <div>
                        <div class="font-semibold">Mike Rodriguez</div>
                        <div class="text-sm text-white/60">Managing Partner, Rodriguez Law Firm</div>
                    </div>
                </div>

                <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                    <div class="flex items-center space-x-1 mb-4">
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                        <i data-lucide="star" class="h-4 w-4 fill-yellow-400 text-yellow-400"></i>
                    </div>
                    <p class="text-white/80 text-base mb-6">
                        "Our website traffic increased 28% after fixing accessibility issues. AccessiScan pays for itself."
                    </p>
                    <div>
                        <div class="font-semibold">Jennifer Walsh</div>
                        <div class="text-sm text-white/60">Marketing Director, E-Commerce Plus</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="container mx-auto px-4 py-16">
        <div class="text-center mb-16 fade-in-up">
            <h2 class="text-4xl font-bold text-white mb-4">
                Simple, Transparent Pricing
            </h2>
            <p class="text-xl text-white/80 mb-8">
                Choose the plan that fits your business. All plans include 14-day free trial.
            </p>
            <div class="inline-flex items-center bg-green-500/20 text-green-100 border border-green-400/30 rounded-full px-4 py-2">
                <i data-lucide="dollar-sign" class="h-4 w-4 mr-2"></i>
                Save 20% with Annual Billing
            </div>
        </div>

        <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
            <!-- Starter Plan -->
            <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                <div class="text-center mb-6">
                    <h3 class="text-2xl font-bold mb-2">Starter</h3>
                    <p class="text-white/80 mb-4">Perfect for small businesses</p>
                    <div>
                        <span class="text-4xl font-bold">$29</span>
                        <span class="text-lg text-white/80">/month</span>
                    </div>
                </div>
                
                <ul class="space-y-3 mb-8">
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Scan up to 5 pages</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Monthly compliance reports</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Email support</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Basic remediation guidance</span>
                    </li>
                </ul>
                
                <button class="w-full btn-secondary py-3 px-4 rounded-lg font-semibold">
                    Start Free Trial
                </button>
            </div>

            <!-- Professional Plan (Popular) -->
            <div class="bg-white text-gray-800 rounded-2xl p-8 card-hover fade-in-up pricing-popular relative">
                <div class="absolute -top-4 left-1/2 transform -translate-x-1/2 bg-yellow-400 text-black px-4 py-1 rounded-full text-sm font-semibold">
                    Most Popular
                </div>
                
                <div class="text-center mb-6">
                    <h3 class="text-2xl font-bold mb-2">Professional</h3>
                    <p class="text-gray-600 mb-4">Most popular for growing businesses</p>
                    <div>
                        <span class="text-4xl font-bold">$99</span>
                        <span class="text-lg text-gray-600">/month</span>
                    </div>
                </div>
                
                <ul class="space-y-3 mb-8">
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-600"></i>
                        <span class="text-gray-700">Unlimited page scanning</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-600"></i>
                        <span class="text-gray-700">Weekly automated scans</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-600"></i>
                        <span class="text-gray-700">Priority support</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-600"></i>
                        <span class="text-gray-700">Detailed remediation guides</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-600"></i>
                        <span class="text-gray-700">API access</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-600"></i>
                        <span class="text-gray-700">Compliance certificates</span>
                    </li>
                </ul>
                
                <button class="w-full bg-purple-600 hover:bg-purple-700 text-white py-3 px-4 rounded-lg font-semibold transition-all duration-300">
                    Start Free Trial
                </button>
            </div>

            <!-- Agency Plan -->
            <div class="glass text-white rounded-2xl p-8 card-hover fade-in-up">
                <div class="text-center mb-6">
                    <h3 class="text-2xl font-bold mb-2">Agency</h3>
                    <p class="text-white/80 mb-4">White-label solution for agencies</p>
                    <div>
                        <span class="text-4xl font-bold">$299</span>
                        <span class="text-lg text-white/80">/month</span>
                    </div>
                </div>
                
                <ul class="space-y-3 mb-8">
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Multiple client sites</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">White-label dashboard</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Daily monitoring</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Custom branding</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Dedicated account manager</span>
                    </li>
                    <li class="flex items-center">
                        <i data-lucide="check-circle" class="h-4 w-4 mr-3 text-green-400"></i>
                        <span class="text-white/90">Partner revenue sharing</span>
                    </li>
                </ul>
                
                <button class="w-full btn-secondary py-3 px-4 rounded-lg font-semibold">
                    Start Free Trial
                </button>
            </div>
        </div>

        <div class="text-center mt-12 fade-in-up">
            <p class="text-white/80 mb-4">
                Need a custom solution for enterprise? 
            </p>
            <button class="btn-secondary px-6 py-3 rounded-lg font-semibold">
                Contact Sales
            </button>
        </div>
    </section>

    <!-- Urgency Section -->
    <section class="bg-red-600/20 backdrop-blur-md py-16 border-y border-red-400/30">
        <div class="container mx-auto px-4 text-center fade-in-up">
            <div class="max-w-4xl mx-auto">
                <i data-lucide="alert-triangle" class="h-16 w-16 text-red-400 mx-auto mb-6"></i>
                <h2 class="text-3xl font-bold text-white mb-4">
                    Don't Wait Until You're Sued
                </h2>
                <p class="text-xl text-white/90 mb-8">
                    ADA lawsuits increased 7% in 2024. The average settlement is $15,000. Protect your business now for less than $100/month.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <button class="btn-primary text-lg px-8 py-4 rounded-lg font-semibold">
                        Protect My Business Now
                    </button>
                    <button class="btn-secondary text-lg px-8 py-4 rounded-lg font-semibold">
                        Calculate My Risk
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="container mx-auto px-4 py-16">
        <div class="text-center mb-16 fade-in-up">
            <h2 class="text-4xl font-bold text-white mb-4">
                Frequently Asked Questions
            </h2>
        </div>

        <div class="max-w-4xl mx-auto space-y-6">
            <div class="glass rounded-2xl p-6 fade-in-up">
                <button class="faq-question w-full text-left flex justify-between items-center text-white font-semibold text-lg">
                    What is ADA compliance and why do I need it?
                    <i data-lucide="chevron-down" class="h-5 w-5 transition-transform duration-300"></i>
                </button>
                <div class="faq-answer hidden mt-4 text-white/80">
                    The Americans with Disabilities Act requires websites to be accessible to people with disabilities. Non-compliance can result in lawsuits with settlements averaging $15,000.
                </div>
            </div>

            <div class="glass rounded-2xl p-6 fade-in-up">
                <button class="faq-question w-full text-left flex justify-between items-center text-white font-semibold text-lg">
                    How accurate is automated accessibility testing?
                    <i data-lucide="chevron-down" class="h-5 w-5 transition-transform duration-300"></i>
                </button>
                <div class="faq-answer hidden mt-4 text-white/80">
                    AccessiScan finds approximately 57% of accessibility issues automatically using axe-core. We provide guidance for manual testing to catch the remaining issues.
                </div>
            </div>

            <div class="glass rounded-2xl p-6 fade-in-up">
                <button class="faq-question w-full text-left flex justify-between items-center text-white font-semibold text-lg">
                    Can I cancel anytime?
                    <i data-lucide="chevron-down" class="h-5 w-5 transition-transform duration-300"></i>
                </button>
                <div class="faq-answer hidden mt-4 text-white/80">
                    Yes, you can cancel your subscription at any time. No long-term contracts or cancellation fees.
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA Section -->
    <section class="container mx-auto px-4 py-16 text-center fade-in-up">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-4xl font-bold text-white mb-6">
                Ready to Protect Your Business?
            </h2>
            <p class="text-xl text-white/80 mb-8">
                Join 500+ businesses using AccessiScan to avoid lawsuits and reach more customers. Start your free trial today - no credit card required.
            </p>
            <button class="btn-primary text-xl px-12 py-5 rounded-lg font-semibold">
                Start Free 14-Day Trial
            </button>
            <p class="text-white/60 mt-4">
                Setup takes 2 minutes • Cancel anytime • 24/7 support
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white/5 backdrop-blur-md py-16 border-t border-white/10">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i data-lucide="shield" class="h-6 w-6 text-white"></i>
                        <span class="text-xl font-bold text-white">AccessiScan</span>
                    </div>
                    <p class="text-white/70">
                        Professional website accessibility compliance scanner. 
                        Protect your business from ADA lawsuits.
                    </p>
                </div>
                <div>
                    <h4 class="font-semibold text-white mb-4">Product</h4>
                    <ul class="space-y-2 text-white/70">
                        <li><a href="#features" class="hover:text-white transition-colors">Features</a></li>
                        <li><a href="#pricing" class="hover:text-white transition-colors">Pricing</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">API</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Integrations</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold text-white mb-4">Resources</h4>
                    <ul class="space-y-2 text-white/70">
                        <li><a href="#" class="hover:text-white transition-colors">Documentation</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Blog</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Case Studies</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Support</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold text-white mb-4">Company</h4>
                    <ul class="space-y-2 text-white/70">
                        <li><a href="#" class="hover:text-white transition-colors">About</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Contact</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Privacy</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Terms</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-white/10 pt-8 text-center text-white/70">
                <p>&copy; 2025 AccessiScan. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // FAQ toggle functionality
        const faqQuestions = document.querySelectorAll('.faq-question');
        
        faqQuestions.forEach(question => {
            question.addEventListener('click', () => {
                const answer = question.nextElementSibling;
                const icon = question.querySelector('[data-lucide="chevron-down"]');
                
                answer.classList.toggle('hidden');
                icon.style.transform = answer.classList.contains('hidden') ? 'rotate(0deg)' : 'rotate(180deg)';
            });
        });

        // Website scanner functionality
        const scanBtn = document.getElementById('scan-btn');
        const urlInput = document.getElementById('url');
        
        scanBtn.addEventListener('click', async () => {
            const url = urlInput.value.trim();
            
            if (!url) {
                alert('Please enter a website URL');
                return;
            }
            
            if (!isValidUrl(url)) {
                alert('Please enter a valid URL (e.g., https://example.com)');
                return;
            }
            
            // Start scanning animation
            scanBtn.innerHTML = `
                <i data-lucide="clock" class="mr-2 h-5 w-5 animate-spin"></i>
                Scanning Your Website...
            `;
            scanBtn.disabled = true;
            
            // Simulate scanning process
            setTimeout(() => {
                // Reset button
                scanBtn.innerHTML = `
                    <i data-lucide="zap" class="mr-2 h-5 w-5"></i>
                    Scan for Accessibility Issues
                `;
                scanBtn.disabled = false;
                
                // Show results (in real implementation, this would show actual results)
                showScanResults(url);
                
                // Re-initialize icons
                lucide.createIcons();
            }, 3000);
        });

        // URL validation function
        function isValidUrl(string) {
            try {
                new URL(string);
                return true;
            } catch (_) {
                return false;
            }
        }

        // Show scan results (mock implementation)
        function showScanResults(url) {
            const results = `
                <div class="fixed inset-0 bg-black/50 backdrop-blur-sm z-50 flex items-center justify-center p-4">
                    <div class="bg-white rounded-2xl p-8 max-w-2xl w-full max-h-[90vh] overflow-y-auto">
                        <div class="flex justify-between items-center mb-6">
                            <h3 class="text-2xl font-bold text-gray-800">Accessibility Scan Results</h3>
                            <button id="close-results" class="text-gray-500 hover:text-gray-700">
                                <i data-lucide="x" class="h-6 w-6"></i>
                            </button>
                        </div>
                        
                        <div class="space-y-6">
                            <div class="bg-red-50 border border-red-200 rounded-lg p-4">
                                <div class="flex items-center mb-2">
                                    <i data-lucide="alert-triangle" class="h-5 w-5 text-red-500 mr-2"></i>
                                    <span class="font-semibold text-red-800">7 Critical Issues Found</span>
                                </div>
                                <p class="text-red-700 text-sm">Your website has accessibility violations that could trigger ADA lawsuits.</p>
                            </div>
                            
                            <div class="space-y-4">
                                <div class="border border-gray-200 rounded-lg p-4">
                                    <h4 class="font-semibold text-gray-800 mb-2">Missing Alt Text on Images</h4>
                                    <p class="text-gray-600 text-sm mb-2">12 images found without alternative text descriptions.</p>
                                    <span class="inline-block bg-red-100 text-red-800 text-xs px-2 py-1 rounded">Critical</span>
                                </div>
                                
                                <div class="border border-gray-200 rounded-lg p-4">
                                    <h4 class="font-semibold text-gray-800 mb-2">Poor Color Contrast</h4>
                                    <p class="text-gray-600 text-sm mb-2">5 elements don't meet WCAG contrast requirements.</p>
                                    <span class="inline-block bg-orange-100 text-orange-800 text-xs px-2 py-1 rounded">Moderate</span>
                                </div>
                                
                                <div class="border border-gray-200 rounded-lg p-4">
                                    <h4 class="font-semibold text-gray-800 mb-2">Missing Form Labels</h4>
                                    <p class="text-gray-600 text-sm mb-2">3 form inputs lack proper accessibility labels.</p>
                                    <span class="inline-block bg-red-100 text-red-800 text-xs px-2 py-1 rounded">Critical</span>
                                </div>
                            </div>
                            
                            <div class="bg-yellow-50 border border-yellow-200 rounded-lg p-4">
                                <div class="flex items-center mb-2">
                                    <i data-lucide="alert-triangle" class="h-5 w-5 text-yellow-600 mr-2"></i>
                                    <span class="font-semibold text-yellow-800">Lawsuit Risk: HIGH</span>
                                </div>
                                <p class="text-yellow-700 text-sm">These issues put you at risk for ADA lawsuits. Average settlement: $15,000.</p>
                            </div>
                            
                            <div class="flex flex-col sm:flex-row gap-4">
                                <button class="btn-primary flex-1 py-3 px-6 rounded-lg font-semibold">
                                    Get Detailed Report & Fix Guide
                                </button>
                                <button class="btn-secondary flex-1 py-3 px-6 rounded-lg font-semibold">
                                    Start Free Trial
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            `;
            
            document.body.insertAdjacentHTML('beforeend', results);
            
            // Close results modal
            document.getElementById('close-results').addEventListener('click', () => {
                document.querySelector('.fixed.inset-0').remove();
            });
            
            // Re-initialize icons
            lucide.createIcons();
        }

        // Customer counter animation
        let customerCount = 487;
        const customerCountElement = document.getElementById('customer-count');
        const statCounterElement = document.getElementById('stat-counter');
        
        // Simulate live customer growth
        setInterval(() => {
            if (Math.random() < 0.3) { // 30% chance every interval
                customerCount += Math.floor(Math.random() * 3) + 1;
                customerCountElement.textContent = customerCount.toLocaleString();
                statCounterElement.textContent = customerCount + '+';
            }
        }, 30000); // Every 30 seconds

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll-triggered animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Observe all fade-in-up elements
        document.querySelectorAll('.fade-in-up').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(30px)';
            el.style.transition = 'opacity 0.6s ease-out, transform 0.6s ease-out';
            observer.observe(el);
        });

        // Add click tracking for buttons (for analytics)
        document.querySelectorAll('button').forEach(button => {
            button.addEventListener('click', (e) => {
                const buttonText = e.target.textContent.trim();
                console.log('Button clicked:', buttonText);
                
                // Here you would send analytics data to your tracking service
                // Example: gtag('event', 'click', { button_text: buttonText });
            });
        });

        // Form validation for URL input
        urlInput.addEventListener('input', (e) => {
            const url = e.target.value.trim();
            if (url && !isValidUrl(url)) {
                e.target.style.borderColor = '#ef4444';
            } else {
                e.target.style.borderColor = '#d1d5db';
            }
        });

        // Add keyboard navigation support
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Enter' && document.activeElement === urlInput) {
                scanBtn.click();
            }
        });
    </script>
</body>
</html>
