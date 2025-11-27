<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emergency Appliance Repair Leads | Local Fridge, Washer, Oven Fix</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind to use Inter font and custom colors -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary': '#10b981', // Emerald green for action
                        'primary-dark': '#059669',
                        'secondary': '#fcd34d', // Amber/Yellow for urgency
                        'gray-bg': '#f3f4f6',
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom styles for professional look and feel */
        .card {
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .cta-button {
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 15px rgba(16, 185, 129, 0.4);
        }
        /* Style for the fixed call button on mobile */
        @media (max-width: 768px) {
            #mobile-cta {
                display: block;
            }
            .main-content {
                padding-bottom: 72px; /* Ensure space for fixed footer CTA */
            }
        }
        @media (min-width: 769px) {
            #mobile-cta {
                display: none;
            }
        }
    </style>
</head>
<body class="bg-gray-bg font-sans antialiased">

    <!-- Fixed Mobile CTA Bar (High Conversion on Mobile) -->
    <div id="mobile-cta" class="fixed bottom-0 left-0 w-full bg-primary p-3 text-center z-50 shadow-2xl md:hidden">
        <!-- The href and content are set via JavaScript using the defined constant -->
        <a id="mobile-cta-link" href="#" class="cta-button inline-flex items-center justify-center w-full py-3 px-6 bg-secondary text-gray-900 font-extrabold text-xl rounded-lg shadow-lg hover:bg-yellow-400">
            <svg class="w-6 h-6 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
            CALL NOW FOR FAST REPAIR: 0800 555 0199
        </a>
    </div>

    <!-- Header Section -->
    <header class="bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <h1 class="text-3xl font-extrabold text-gray-900">
                <span class="text-primary">Local</span> Repair Leads
            </h1>
            <!-- The href and content are set via JavaScript using the defined constant -->
            <a id="header-cta-link" href="#" class="hidden md:block text-lg font-semibold text-gray-700 hover:text-primary transition duration-150">
                <span class="text-gray-500 text-sm">Need Help Now? Call:</span> <span id="header-cta-number" class="text-primary-dark font-bold text-xl">0800 555 0199</span>
            </a>
        </div>
    </header>

    <!-- Main Content Area -->
    <main class="main-content max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 lg:py-16">

        <!-- Hero Section -->
        <section class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center mb-16">
            <!-- Left Side: Value Proposition & Urgency -->
            <div class="space-y-6">
                <h2 class="text-5xl lg:text-6xl font-extrabold text-gray-900 leading-tight">
                    <span class="text-primary">Need Emergency Repair?</span> Get Vetted Local Engineers Fast.
                </h2>
                <p class="text-xl text-gray-600">
                    Your fridge, washer, or oven is broken. We connect you instantly to **pre-screened, local white goods repair experts** in your area who are ready to book your job right now.
                </p>
                
                <!-- Trust & Urgency Features -->
                <ul class="space-y-3 text-lg text-gray-700">
                    <li class="flex items-center">
                        <svg class="w-6 h-6 text-primary mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                        <strong>Fast Response:</strong> Connect in under 60 seconds.
                    </li>
                    <li class="flex items-center">
                        <svg class="w-6 h-6 text-primary mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.618a8.6 8.6 0 00-12.77 0m12.77 0a8.6 8.6 0 01-12.77 0m12.77 0l-4.243 4.243a4 4 0 01-5.657 0L8.382 7.382m4.243-4.243a4 4 0 015.657 0m-5.657 0a4 4 0 00-5.657 0"></path></svg>
                        <strong>Vetted Pros:</strong> Fully insured and certified local technicians.
                    </li>
                    <li class="flex items-center">
                        <svg class="w-6 h-6 text-primary mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c1.657 0 3 .895 3 2s-1.343 2-3 2-3-.895-3-2 1.343-2 3-2zM12 10.5a1 1 0 100-2 1 1 0 000 2zM12 12.75l-4.75 4.75m4.75-4.75l4.75 4.75m-4.75-4.75V19m-7-7a8 8 0 1014 0 8 8 0 00-14 0z"></path></svg>
                        <strong>All Major Brands:</strong> Fridge, Freezer, Oven, Dishwasher, Washer, Dryer.
                    </li>
                </ul>
            </div>

            <!-- Right Side: Conversion Form & Primary CTA -->
            <div class="card bg-white p-8 lg:p-10 rounded-xl">
                <h3 class="text-3xl font-bold text-gray-900 mb-6 text-center">
                    Get Your FREE, Instant Quote
                </h3>
                
                <!-- PRIMARY CTA: Phone Call (Highest Intent) -->
                <div class="mb-6">
                    <!-- The href and content are set via JavaScript using the defined constant -->
                    <a id="hero-cta-link" href="#" class="cta-button w-full flex items-center justify-center py-4 px-6 bg-primary text-white font-extrabold text-2xl rounded-lg shadow-xl hover:bg-primary-dark">
                        <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                        Tap to Call Now: 0800 555 0199
                    </a>
                    <p class="text-center text-sm text-gray-500 mt-2">
                        Fastest way to book service. Call tracking in use.
                    </p>
                </div>
                
                <div class="relative flex items-center justify-center py-4">
                    <div class="flex-grow border-t border-gray-300"></div>
                    <span class="flex-shrink mx-4 text-gray-500 font-medium">OR</span>
                    <div class="flex-grow border-t border-gray-300"></div>
                </div>

                <!-- Secondary CTA: Lead Form (For less urgent customers) -->
                <form id="lead-form" class="space-y-4">
                    <div>
                        <label for="postcode" class="block text-sm font-medium text-gray-700">1. Your Postcode / ZIP Code</label>
                        <input type="text" id="postcode" name="postcode" placeholder="e.g., SW1A 0AA" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:ring-primary focus:border-primary">
                    </div>
                    <div>
                        <label for="appliance" class="block text-sm font-medium text-gray-700">2. Appliance Type & Issue</label>
                        <textarea id="appliance" name="appliance" rows="2" placeholder="e.g., Fridge - not cooling, Washer - leaking water" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:ring-primary focus:border-primary"></textarea>
                    </div>
                    <div>
                        <label for="phone" class="block text-sm font-medium text-gray-700">3. Best Contact Phone Number</label>
                        <input type="tel" id="phone" name="phone" placeholder="Your mobile number" required class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm p-3 focus:ring-primary focus:border-primary">
                    </div>
                    
                    <button type="submit" class="cta-button w-full py-3 px-6 bg-secondary text-gray-900 font-extrabold text-xl rounded-lg shadow-md hover:bg-yellow-400">
                        Submit & Get Multiple Quotes
                    </button>
                    <p id="form-message" class="text-center text-sm text-primary font-semibold hidden pt-2">Thank you! Matching you with a local pro now...</p>
                </form>
            </div>
        </section>

        <!-- Service Area & Guarantee Section -->
        <section class="bg-white p-8 rounded-xl card my-12">
            <h3 class="text-2xl font-bold text-gray-900 mb-6 text-center">Why Choose a Vetted Engineer?</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div class="space-y-2">
                    <img src="https://placehold.co/80x80/10b981/ffffff?text=🛡️" alt="Vetted" class="mx-auto">
                    <p class="font-semibold text-lg">Guaranteed Quality</p>
                    <p class="text-gray-600 text-sm">All engineers are fully certified, insured, and verified for quality workmanship.</p>
                </div>
                <div class="space-y-2">
                    <img src="https://placehold.co/80x80/10b981/ffffff?text=⏰" alt="Speed" class="mx-auto">
                    <p class="font-semibold text-lg">Unmatched Speed</p>
                    <p class="text-gray-600 text-sm">We only connect you to technicians with availability to ensure same-day or next-day service.</p>
                </div>
                <div class="space-y-2">
                    <img src="https://placehold.co/80x80/10b981/ffffff?text=📍" alt="Local" class="mx-auto">
                    <p class="font-semibold text-lg">Hyper-Local Service</p>
                    <p class="text-gray-600 text-sm">Engineers are based right here in the local area, saving you time and travel costs.</p>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white p-6 text-center">
        <div class="max-w-7xl mx-auto text-sm">
            <p>&copy; <span id="year"></span> Local Repair Leads. We are a lead generation service connecting customers with independent, local appliance repair professionals.</p>
            <p class="mt-2 text-gray-400">Disclaimer: We do not perform the repairs ourselves. All service is provided by third-party contractors.</p>
        </div>
    </footer>

    <!-- JavaScript for Form Submission and Dynamic CTA Number -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // --- START CONFIGURATION: CHANGE THIS VARIABLE TO UPDATE THE NUMBER EVERYWHERE ---
            const CALL_TO_ACTION_NUMBER = '0800 555 0199';
            // Formats the number for the tel: link (removes spaces, replaces with hyphens)
            const CALL_TO_ACTION_TEL = 'tel:' + CALL_TO_ACTION_NUMBER.replace(/\s/g, '-'); 
            // --- END CONFIGURATION ---

            // Set current year in footer
            document.getElementById('year').textContent = new Date().getFullYear();

            // 1. Update Mobile CTA Link and Text
            const mobileCtaLink = document.getElementById('mobile-cta-link');
            if (mobileCtaLink) {
                mobileCtaLink.href = CALL_TO_ACTION_TEL;
                // Rebuild the content to include the SVG and the new number
                mobileCtaLink.innerHTML = `
                    <svg class="w-6 h-6 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                    CALL NOW FOR FAST REPAIR: ${CALL_TO_ACTION_NUMBER}
                `;
            }

            // 2. Update Header CTA Link and Number Text
            const headerCtaLink = document.getElementById('header-cta-link');
            const headerCtaNumber = document.getElementById('header-cta-number');
            if (headerCtaLink && headerCtaNumber) {
                headerCtaLink.href = CALL_TO_ACTION_TEL;
                headerCtaNumber.textContent = CALL_TO_ACTION_NUMBER;
            }

            // 3. Update Hero CTA Link and Text
            const heroCtaLink = document.getElementById('hero-cta-link');
            if (heroCtaLink) {
                heroCtaLink.href = CALL_TO_ACTION_TEL;
                // Rebuild the content to include the SVG and the new number
                heroCtaLink.innerHTML = `
                    <svg class="w-7 h-7 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                    Tap to Call Now: ${CALL_TO_ACTION_NUMBER}
                `;
            }


            // Form submission logic (remains the same)
            const form = document.getElementById('lead-form');
            const formMessage = document.getElementById('form-message');

            form.addEventListener('submit', async function(e) {
                e.preventDefault();
                
                // Show temporary message to the customer
                formMessage.textContent = 'Processing your request... Please wait.';
                formMessage.classList.remove('hidden', 'text-primary');
                formMessage.classList.add('text-secondary', 'animate-pulse');

                // --- START OF LEAD DATA COLLECTION (For Your Business) ---
                
                const formData = {
                    postcode: document.getElementById('postcode').value,
                    applianceIssue: document.getElementById('appliance').value,
                    phone: document.getElementById('phone').value,
                    source: 'Web Form Submission',
                    timestamp: new Date().toISOString()
                };

                console.log('New Lead Captured:', formData);

                // Simulate processing/sending data to your Lead Management System (LMS)
                // In a real application, you would send this to a server endpoint
                await new Promise(resolve => setTimeout(resolve, 1500)); 
                
                // --- END OF LEAD DATA COLLECTION ---

                // Success Feedback for the Customer
                formMessage.textContent = 'Success! We are connecting you with a technician now. Expect a call shortly!';
                formMessage.classList.remove('animate-pulse', 'text-secondary');
                formMessage.classList.add('text-primary');

                // Clear the form after submission
                form.reset();
            });
        });
    </script>
