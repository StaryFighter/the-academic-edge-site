# the-academic-edge-site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Academic Edge | Research and Proofreading Services</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind to use Inter font and a custom color palette -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary-blue': '#1e3a8a', // Dark Blue for professionalism
                        'accent-green': '#34d399', // Light Green for growth/success
                        'gray-light': '#f9fafb',
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom styles for the Inter font and smooth scrolling */
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-light text-gray-800">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-primary-blue flex items-center">
                <!-- Icon: Book/Pencil (using inline SVG for robustness) -->
                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 mr-2 text-accent-green" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M4 4a2 2 0 012-2h4.586A2 2 0 0112 2.586L15.414 6A2 2 0 0116 7.414V16a2 2 0 01-2 2H6a2 2 0 01-2-2V4zm2 6a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1zm0 3a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
                The Academic Edge
            </a>
            <nav class="hidden md:flex space-x-8">
                <a href="#services" class="text-primary-blue hover:text-accent-green font-medium transition duration-150">Services</a>
                <a href="#process" class="text-primary-blue hover:text-accent-green font-medium transition duration-150">Our Process</a>
                <a href="#testimonials" class="text-primary-blue hover:text-accent-green font-medium transition duration-150">Success Stories</a>
                <a href="#contact" class="px-4 py-2 bg-accent-green text-white rounded-full hover:bg-green-500 transition duration-150 shadow-md">Get a Quote</a>
            </nav>
            <!-- Mobile Menu Button (hidden on desktop) -->
            <button id="mobile-menu-btn" class="md:hidden text-primary-blue">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>
        <!-- Mobile Menu (initially hidden) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-gray-100">
            <nav class="flex flex-col px-4 py-2 space-y-2">
                <a href="#services" class="block py-2 text-primary-blue hover:bg-gray-50 rounded-lg">Services</a>
                <a href="#process" class="block py-2 text-primary-blue hover:bg-gray-50 rounded-lg">Our Process</a>
                <a href="#testimonials" class="block py-2 text-primary-blue hover:bg-gray-50 rounded-lg">Success Stories</a>
                <a href="#contact" class="block py-2 text-white bg-accent-green text-center rounded-lg mt-2">Get a Quote</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-primary-blue text-white py-24 sm:py-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl sm:text-6xl font-extrabold leading-tight mb-4">
                Beyond Tutoring: Expert Research & Polished Papers
            </h1>
            <p class="text-xl sm:text-2xl font-light mb-8 max-w-3xl mx-auto">
                We empower high school and college students with the foundation for academic success: impeccable research and flawless writing.
            </p>
            <a href="#contact" class="inline-block px-10 py-4 bg-accent-green text-primary-blue font-bold text-lg rounded-full shadow-2xl hover:bg-green-500 transition duration-300 transform hover:scale-105">
                Elevate Your Grade Now
            </a>
        </div>
    </section>

    <!-- Services Section (Updated to 4 Services) -->
    <section id="services" class="py-16 sm:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-extrabold text-center text-primary-blue mb-12">
                Our Focused Academic Support Services
            </h2>
            <!-- Updated Grid to showcase four distinct services -->
            <div class="grid md:grid-cols-2 lg:grid-cols-2 gap-8">

                <!-- Service 1: Project Ideation & Scope Definition -->
                <div class="bg-gray-light p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-accent-green">
                    <h3 class="text-2xl font-bold text-primary-blue mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
                        </svg>
                        1. Project Ideation & Scope Definition
                    </h3>
                    <p class="text-gray-600 mb-4">
                        We help you move from a broad topic to a defined, manageable project. Our guidance covers creating a concrete research question, setting realistic timelines, and developing a structured outline.
                    </p>
                    <ul class="space-y-2 text-sm text-gray-700">
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Research Question Formulation</li>
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Structural Outline Development</li>
                    </ul>
                </div>

                <!-- Service 2: Advanced Research Strategy & Vetting -->
                <div class="bg-gray-light p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-accent-green">
                    <h3 class="text-2xl font-bold text-primary-blue mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-4.5 9-7.5 9s-7.5-1.858-7.5-9s4.5-9 7.5-9s7.5 1.858 7.5 9z" />
                        </svg>
                        2. Advanced Research Strategy & Vetting
                    </h3>
                    <p class="text-gray-600 mb-4">
                        Don't just Google it. We guide you in identifying and using highly credible sources—from peer-reviewed journals to industry reports and specialized databases—essential for college and graduate-level work.
                    </p>
                    <ul class="space-y-2 text-sm text-gray-700">
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Scholarly Source Identification</li>
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Annotated Bibliography Guidance</li>
                    </ul>
                </div>

                <!-- Service 3: Thesis/Project Validation Consulting (Premium) -->
                <div class="bg-gray-light p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-accent-green">
                    <h3 class="text-2xl font-bold text-primary-blue mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.108a12.025 12.025 0 011.379 3.07 12.025 12.025 0 01-1.379 3.07m-5.618-4.108a12.025 12.025 0 01-1.379 3.07 12.025 12.025 0 01-1.379 3.07m-5.618-4.108a12.025 12.025 0 01-1.379 3.07 12.025 12.025 0 01-1.379 3.07" />
                        </svg>
                        3. Thesis/Project Validation Consulting
                    </h3>
                    <p class="text-gray-600 mb-4">
                        Leveraging deep financial and market expertise, we provide high-level feedback on the **feasibility and rigor** of large projects (e.g., business plans, capstones, theses) before submission.
                    </p>
                    <ul class="space-y-2 text-sm text-gray-700">
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Market Feasibility Review</li>
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Methodology Stress-Testing</li>
                    </ul>
                </div>

                <!-- Service 4: Academic Clarity Editing (Proofreading) -->
                <div class="bg-gray-light p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300 border-t-4 border-accent-green">
                    <h3 class="text-2xl font-bold text-primary-blue mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z" />
                        </svg>
                        4. Academic Clarity Editing
                    </h3>
                    <p class="text-gray-600 mb-4">
                        Meticulous editing to ensure your written argument is flawless. We correct grammar, syntax, flow, and, most importantly, confirm 100% accurate adherence to your required citation style.
                    </p>
                    <ul class="space-y-2 text-sm text-gray-700">
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Grammar and Style Refinement</li>
                        <li class="flex items-center"><span class="text-accent-green mr-2">•</span> Citation Formatting Check (All styles)</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Process / Why Us Section -->
    <section id="process" class="py-16 sm:py-24 bg-primary-blue text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl sm:text-4xl font-extrabold mb-12">
                Why Students Trust The Academic Edge
            </h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Benefit 1 -->
                <div class="p-6 bg-white bg-opacity-10 rounded-xl shadow-lg border-b-4 border-accent-green">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto mb-4 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.108a12.025 12.025 0 011.379 3.07 12.025 12.025 0 01-1.379 3.07m-5.618-4.108a12.025 12.025 0 01-1.379 3.07 12.025 12.025 0 01-1.379 3.07m-5.618-4.108a12.025 12.025 0 01-1.379 3.07 12.025 12.025 0 01-1.379 3.07" />
                    </svg>
                    <h3 class="text-xl font-semibold mb-2">Plagiarism-Free Policy</h3>
                    <p class="text-gray-200 text-sm">Our service provides guidance and editing only. We ensure your voice and content remain 100% original and ethically sourced.</p>
                </div>

                <!-- Benefit 2 -->
                <div class="p-6 bg-white bg-opacity-10 rounded-xl shadow-lg border-b-4 border-accent-green">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto mb-4 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                    <h3 class="text-xl font-semibold mb-2">Rapid Turnaround</h3>
                    <p class="text-gray-200 text-sm">We understand deadlines. Choose from our standard or express options to get your polished work back when you need it most.</p>
                </div>

                <!-- Benefit 3 -->
                <div class="p-6 bg-white bg-opacity-10 rounded-xl shadow-lg border-b-4 border-accent-green">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto mb-4 text-accent-green" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z" />
                    </svg>
                    <h3 class="text-xl font-semibold mb-2">Expert-Driven Value</h3>
                    <p class="text-gray-200 text-sm">Our guidance is built on real-world, graduate-level research experience in technical and market domains, offering unmatched insights.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-16 sm:py-24 bg-gray-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl sm:text-4xl font-extrabold text-center text-primary-blue mb-12">
                Success Stories
            </h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-6 rounded-xl shadow-lg border-l-4 border-accent-green">
                    <p class="italic text-gray-700 mb-4">"The research assistance was a game-changer. I spent half the time finding sources and felt so much more confident in my paper's arguments. Highly recommend for any tough capstone project!"</p>
                    <p class="font-semibold text-primary-blue">- Sarah K., University Senior</p>
                </div>
                <!-- Testimonial 2 -->
                <div class="bg-white p-6 rounded-xl shadow-lg border-l-4 border-accent-green">
                    <p class="italic text-gray-700 mb-4">"My professor always knocked points off for flow and punctuation. After 'The Academic Edge' edited my work, I received my first perfect score on a history essay. Unbelievable difference!"</p>
                    <p class="font-semibold text-primary-blue">- David L., High School Junior</p>
                </div>
                <!-- Testimonial 3 -->
                <div class="bg-white p-6 rounded-xl shadow-lg border-l-4 border-accent-green">
                    <p class="italic text-gray-700 mb-4">"They caught three major APA formatting errors I totally missed. The attention to detail saved me a ton of hassle and ensured my thesis was structurally sound. Worth every penny."</p>
                    <p class="font-semibold text-primary-blue">- Mia B., Graduate Student</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact/CTA Section -->
    <section id="contact" class="py-16 sm:py-24 bg-primary-blue">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-4">
                Ready to Submit a Project?
            </h2>
            <p class="text-xl text-gray-200 mb-8 max-w-2xl mx-auto">
                Tell us about your assignment, deadline, and service needs. We'll send you a personalized quote fast.
            </p>
            <a href="mailto:info@academicedge.com" class="inline-block px-10 py-4 bg-accent-green text-primary-blue font-bold text-lg rounded-full shadow-2xl hover:bg-green-500 transition duration-300 transform hover:scale-105">
                Request Your Free Quote Today
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-4 gap-8">
            <!-- Col 1: Logo and Motto -->
            <div>
                <h4 class="text-2xl font-bold text-accent-green mb-3">The Academic Edge</h4>
                <p class="text-sm text-gray-400">Your partner in ethical academic excellence.</p>
            </div>
            <!-- Col 2: Quick Links -->
            <div>
                <h5 class="text-lg font-semibold mb-3">Quick Links</h5>
                <ul class="space-y-2 text-sm text-gray-400">
                    <li><a href="#services" class="hover:text-accent-green transition duration-150">Services Overview</a></li>
                    <li><a href="#process" class="hover:text-accent-green transition duration-150">Our Process</a></li>
                    <li><a href="#testimonials" class="hover:text-accent-green transition duration-150">Testimonials</a></li>
                </ul>
            </div>
            <!-- Col 3: Legal -->
            <div>
                <h5 class="text-lg font-semibold mb-3">Policy</h5>
                <ul class="space-y-2 text-sm text-gray-400">
                    <li><a href="#" class="hover:text-accent-green transition duration-150">Terms of Service</a></li>
                    <li><a href="#" class="hover:text-accent-green transition duration-150">Privacy Policy</a></li>
                    <li><a href="#" class="hover:text-accent-green transition duration-150">Ethical Standards</a></li>
                </ul>
            </div>
            <!-- Col 4: Contact Info -->
            <div>
                <h5 class="text-lg font-semibold mb-3">Contact</h5>
                <p class="text-sm text-gray-400">Email: info@academicedge.com</p>
                <p class="text-sm text-gray-400">Hours: Mon-Fri, 9am-6pm EST</p>
            </div>
        </div>
        <div class="mt-8 pt-8 border-t border-gray-700 text-center">
            <p class="text-sm text-gray-400">&copy; 2025 The Academic Edge. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // JavaScript for mobile menu toggle
        const menuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked (for better UX)
        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
