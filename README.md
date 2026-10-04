# AAK
A website for senior citizens 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apka Apna Kutumbh | A Home Filled With Love</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        h1, h2 { font-family: 'Playfair Display', serif; }
        .hero-gradient { 
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1516627145497-ae6968895b74?auto=format&fit=crop&w=1600'); 
            background-size: cover; 
            background-position: center;
        }
    </style>
</head>
<body class="bg-stone-50 text-gray-800">

    <!-- Emergency Top Bar -->
    <div class="bg-red-600 text-white py-2 px-4 flex flex-col sm:flex-row justify-between items-center text-sm font-bold sticky top-0 z-50 gap-2">
        <span><i class="fas fa-phone-alt"></i> 24/7 ELDERLY EMERGENCY: +91 9876543210</span>
        <a href="tel:+919876543210" class="bg-white text-red-600 px-3 py-1 rounded animate-pulse">Call SOS Now</a>
    </div>

    <!-- Navigation -->
    <nav class="bg-white shadow-sm p-4 md:p-6">
        <div class="container mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="bg-orange-100 p-2 rounded-full">
                    <i class="fas fa-hands-helping text-orange-600 text-xl sm:text-2xl"></i>
                </div>
                <h1 class="text-xl sm:text-2xl font-bold text-orange-800 tracking-tight">
                    APKA APNA <span class="text-gray-600 underline decoration-orange-300">KUTUMBH</span>
                </h1>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#about" class="hover:text-orange-600">Our Mission</a>
                <a href="#services" class="hover:text-orange-600">Services</a>
                <a href="#global" class="hover:text-orange-600">NGO Network</a>
                <a href="#donate" class="bg-orange-600 text-white px-6 py-2 rounded-full hover:bg-orange-700 transition">Support Us</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero-gradient min-h-[500px] md:h-[600px] flex items-center justify-center text-center text-white px-4 py-12">
        <div class="max-w-3xl">
            <h2 class="text-4xl md:text-6xl font-bold mb-6 italic">Not an Institution, <br>But Your Own Family.</h2>
            <p class="text-lg md:text-xl mb-8 font-light tracking-wide">Providing dignified living, medical care, and unconditional love to our elders at Apka Apna Kutumbh.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#services" class="bg-white text-orange-800 px-8 py-3 rounded font-bold hover:bg-orange-100">Our Services</a>
                <a href="#contact" class="border-2 border-white px-8 py-3 rounded font-bold hover:bg-white hover:text-orange-800 transition">Partner With Us</a>
            </div>
        </div>
    </header>

    <!-- Global Network Section -->
    <section id="global" class="py-16 bg-orange-50">
        <div class="container mx-auto px-4 text-center">
            <h3 class="text-3xl font-bold text-orange-900 mb-4">Connecting Hearts Worldwide</h3>
            <p class="text-gray-600 max-w-2xl mx-auto mb-12">We are part of a global network of NGOs. We collaborate with international healthcare providers and volunteer organizations to bring world-class care to our home.</p>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 md:gap-6">
                <div class="p-6 bg-white rounded-xl shadow-sm border-b-4 border-orange-400">
                    <h4 class="font-bold text-xl">15+</h4>
                    <p class="text-xs sm:text-sm text-gray-500 uppercase">Partner NGOs</p>
                </div>
                <div class="p-6 bg-white rounded-xl shadow-sm border-b-4 border-orange-400">
                    <h4 class="font-bold text-xl">Global</h4>
                    <p class="text-xs sm:text-sm text-gray-500 uppercase">Volunteer Access</p>
                </div>
                <div class="p-6 bg-white rounded-xl shadow-sm border-b-4 border-orange-400">
                    <h4 class="font-bold text-xl">24/7</h4>
                    <p class="text-xs sm:text-sm text-gray-500 uppercase">Medical Support</p>
                </div>
                <div class="p-6 bg-white rounded-xl shadow-sm border-b-4 border-orange-400">
                    <h4 class="font-bold text-xl">Worldwide</h4>
                    <p class="text-xs sm:text-sm text-gray-500 uppercase">Donation Reach</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-20 container mx-auto px-4">
        <div class="flex flex-col md:flex-row items-center gap-12">
            <div class="w-full md:w-1/2">
                <img src="https://images.unsplash.com/photo-1581578731522-632de05ee939?auto=format&fit=crop&w=800" class="rounded-2xl shadow-2xl w-full object-cover">
            </div>
            <div class="w-full md:w-1/2">
                <h3 class="text-3xl md:text-4xl font-bold mb-6 text-orange-900">Comprehensive Care Services</h3>
                <ul class="space-y-6">
                    <li class="flex items-start">
                        <i class="fas fa-heartbeat mt-1 text-orange-600 mr-4 text-xl"></i>
                        <div>
                            <h5 class="font-bold text-lg">Geriatric Medical Care</h5>
                            <p class="text-gray-600">Regular health check-ups and specialized doctors for age-related ailments.</p>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-utensils mt-1 text-orange-600 mr-4 text-xl"></i>
                        <div>
                            <h5 class="font-bold text-lg">Nutritious Home-Cooked Meals</h5>
                            <p class="text-gray-600">Dietary plans customized for each resident’s health requirements.</p>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <i class="fas fa-om mt-1 text-orange-600 mr-4 text-xl"></i>
                        <div>
                            <h5 class="font-bold text-lg">Spiritual & Mental Well-being</h5>
                            <p class="text-gray-600">Daily Yoga, meditation sessions, and community interactive activities.</p>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

</body>
</html>
