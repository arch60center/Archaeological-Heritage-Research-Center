<!-- 1. HEADER SECTION -->
<header class="bg-ahrcDark text-white sticky top-0 z-50 px-4 md:px-8 py-4 flex justify-between items-center border-b border-gray-800">
    <!-- Logo block -->
    <div class="bg-ahrcYellow text-black font-bold px-4 py-2 text-sm tracking-wider">
        AHRC
    </div>
    
    <!-- Navigation Links -->
    <nav class="hidden md:flex space-x-6 text-xs uppercase tracking-widest font-semibold text-gray-300">
        <a href="#" class="hover:text-white transition">Wings</a>
        <a href="#" class="hover:text-white transition">People</a>
        <a href="#" class="hover:text-white transition">Education</a>
        <a href="#" class="hover:text-white transition">Research</a>
        <a href="#" class="hover:text-white transition">Publication</a>
        <a href="#" class="hover:text-white transition">Contact</a>
    </nav>

    <!-- Right Side Utility Controls -->
    <div class="flex items-center space-x-4 text-xs font-semibold">
        <span class="cursor-pointer hover:text-ahrcYellow">EN ▾</span>
        <button class="hover:text-ahrcYellow" aria-label="Search">
            <svg xmlns="http://w3.org" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" /></svg>
        </button>
        <span class="cursor-pointer tracking-widest uppercase hover:text-ahrcYellow">☰ Menu</span>
    </div>
</header>

<!-- 2. HERO / SPLIT BANNER SECTION -->
<section class="grid grid-cols-1 md:grid-cols-2 bg-ahrcDark min-h-[550px] relative text-white">
    <!-- Left Side: Copywriting Content -->
    <div class="p-8 md:p-16 flex flex-col justify-center space-y-6">
        <span class="text-xs uppercase tracking-widest text-ahrcYellow font-bold">Conservation</span>
        <h1 class="text-3xl md:text-5xl font-bold leading-tight">
            Preserving <span class="bg-gray-800 bg-opacity-60 px-2 py-1 rounded">our</span> <br>shared cultural legacy
        </h1>
        <p class="text-sm text-gray-400 max-w-md leading-relaxed">
            We specialize in the scientific conservation of artifacts and sites, ensuring that India's archaeological heritage remains intact for future generations.
        </p>
        <div>
            <a href="#" class="inline-flex items-center space-x-2 bg-transparent text-sm font-semibold text-white group hover:text-ahrcYellow transition">
                <span>Our conservation work</span>
                <span class="bg-ahrcYellow text-black p-1 rounded-sm text-xs group-hover:bg-white transition">➔</span>
            </a>
        </div>
    </div>

    <!-- Right Side: Focus Artifact Image Visual -->
    <div class="relative min-h-[300px] md:min-h-full bg-cover bg-center" style="background-image: url('https://unsplash.com');">
        <!-- Simulated carousel slide indicator pills at the bottom center -->
        <div class="absolute bottom-4 left-1/2 transform -translate-x-1/2 flex space-x-2">
            <span class="h-1 w-8 bg-gray-500 rounded-sm"></span>
            <span class="h-1 w-8 bg-ahrcYellow rounded-sm"></span>
            <span class="h-1 w-8 bg-gray-500 rounded-sm"></span>
        </div>
    </div>
</section>

<!-- 3. ABOUT THE CENTER / DEEP BLUE STATEMENT SECTION -->
<section class="bg-ahrcNavy text-white py-12 px-6 md:px-16">
    <div class="max-w-4xl space-y-4">
        <span class="text-xs uppercase tracking-widest text-ahrcYellow font-bold">About the Center</span>
        <h2 class="text-xl md:text-2xl font-medium max-w-3xl leading-relaxed">
            The Archaeological Heritage Research Center is dedicated to the scientific preservation and scholarly study of our shared cultural legacy.
        </h2>
        <div class="pt-2">
            <a href="#" class="inline-flex items-center space-x-2 text-sm font-semibold group text-white hover:text-ahrcYellow transition">
                <span>Read the AHRC story</span>
                <span class="bg-ahrcYellow text-black p-1 rounded-sm text-xs group-hover:bg-white transition">➔</span>
            </a>
        </div>
    </div>
</section>

<!-- 4. RESEARCH WINGS / PHOTO GRID SECTION -->
<section class="py-16 px-6 md:px-16 bg-white">
    <div class="mb-10">
        <span class="text-xs uppercase tracking-widest text-gray-500 font-bold">Research Wings</span>
        <h2 class="text-2xl md:text-3xl font-bold mt-1 text-gray-900">Specialized centers for heritage science.</h2>
        <p class="text-xs text-gray-500 mt-2 max-w-xl">
            Twelve dedicated research wings focused on specific disciplines of archaeological science, heritage conservation, and spatial analysis.
        </p>
    </div>

    <!-- 3-Column Visual Grid Layout -->
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <!-- Column 1: Spatial Geomatics -->
        <div class="relative group overflow-hidden cursor-pointer aspect-[4/5]">
            <img src="https://unsplash.com" alt="Spatial Geomatics Lab" class="w-full h-full object-cover transition duration-500 group-hover:scale-105 filter grayscale contrast-125">
            <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent opacity-80"></div>
            <div class="absolute bottom-4 left-4 text-white font-semibold tracking-wide text-sm">
                Spatial Geomatics
            </div>
        </div>

        <!-- Column 2: Palaeoecology -->
        <div class="relative group overflow-hidden cursor-pointer aspect-[4/5]">
            <img src="https://unsplash.com" alt="Palaeoecology excavation stone texture" class="w-full h-full object-cover transition duration-500 group-hover:scale-105 filter grayscale contrast-125">
            <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent opacity-80"></div>
            <div class="absolute bottom-4 left-4 text-white font-semibold tracking-wide text-sm">
                Palaeoecology
            </div>
        </div>

        <!-- Column 3: Palaeography -->
        <div class="relative group overflow-hidden cursor-pointer aspect-[4/5]">
            <img src="https://unsplash.com" alt="Palaeography ancient manuscript scripts" class="w-full h-full object-cover transition duration-500 group-hover:scale-105 filter grayscale contrast-125">
            <div class="absolute inset-0 bg-gradient-to-t from-black via-transparent to-transparent opacity-80"></div>
            <div class="absolute bottom-4 left-4 text-white font-semibold tracking-wide text-sm">
                Palaeography
            </div>
        </div>
    </div>
</section>
