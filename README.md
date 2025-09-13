<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineers' Day - DVVPCET Ahilyanagar</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0A0A10;
        }
        .container-card {
            background: rgba(15, 23, 42, 0.8);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(45, 53, 72, 0.6);
        }
        .transition-transform-opacity {
            transition: transform 0.5s ease-in-out, opacity 0.5s ease-in-out;
        }
        .text-neon-cyan {
            color: #00E5FF;
        }
        .text-neon-pink {
            color: #FF10F0;
        }
        .btn {
            background: linear-gradient(90deg, #FF10F0, #00E5FF);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 229, 255, 0.3);
        }
        .event-card {
            background-color: #1a202c;
            border: 1px solid #2d3748;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .event-card:hover {
            transform: scale(1.03);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
        }
    </style>
</head>
<body class="bg-gradient-to-br from-gray-900 to-indigo-900 text-gray-100 min-h-screen flex items-center justify-center p-4">

    <div class="container-card mx-auto max-w-5xl rounded-3xl shadow-2xl p-6 md:p-12 text-center flex flex-col items-center justify-center">
        <!-- Header Section -->
        <header class="mb-8">
            <p class="text-xl md:text-2xl font-semibold text-neon-cyan mb-4">Dr. Vitthalrao Vikhe Patil College of Engineering, Ahilyanagar</p>
            <p class="text-xl md:text-2xl font-semibold text-neon-cyan mb-4">Department of Computer Science & Design Engineering</p>
            <h1 class="text-3xl md:text-5xl font-extrabold text-white mb-2">Happy Engineers' Day!</h1>
            <p class="text-sm md:text-base text-gray-400">Join us in celebrating innovation and talent. Register for our exciting events!</p>
            <p class="text-sm md:text-base text-gray-400">For any inquiry-related issues, please contact our Vice President, Soham Patil, at 9545935140.</p>
        </header>

        <!-- Dropdown & Main Content Container -->
        <div class="mb-8 flex flex-col items-center">
            <label for="event-type" class="block text-lg font-medium text-gray-300 mb-2">Select Event Category</label>
            <div class="relative w-full max-w-sm rounded-lg overflow-hidden border border-gray-600 transition-all duration-500 hover:border-neon-cyan">
                <select id="event-type" class="w-full p-3 md:p-4 rounded-lg bg-gray-800 text-gray-200 cursor-pointer appearance-none pr-8 focus:outline-none focus:ring-2 focus:ring-neon-cyan">
                    <option value="none" disabled selected>Choose an event type</option>
                    <option value="technical">Technical Events</option>
                    <option value="non-technical">Non-Technical Events</option>
                </select>
                <div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none">
                    <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </div>
            </div>
        </div>

        <!-- Event Pages -->
        <div id="content-area">

            <!-- Technical Events Page -->
            <div id="technical-events" class="p-4 md:p-8 opacity-0 hidden">
                <div class="grid grid-cols-1 gap-6">
                    <div class="event-card p-6 rounded-2xl text-center shadow-lg">
                        <h4 class="text-xl font-bold text-neon-pink mb-2">Tech Treasure Hunt</h4>
                        <p class="text-sm text-gray-400 mb-4">A thrilling event for tech enthusiasts!</p>
                        <a href="https://forms.gle/AAYpECJAsRWox9Qh9" target="_blank" class="btn inline-block px-6 py-2 rounded-full font-bold text-white uppercase text-xs tracking-wide shadow-md">
                            Register Now
                        </a>
                    </div>
                </div>
            </div>

            <!-- Non-Technical Events Page -->
            <div id="non-technical-events" class="p-4 md:p-8 opacity-0 hidden">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <!-- Poster Making Card -->
                    <div class="event-card p-6 rounded-2xl text-center shadow-lg">
                        <h4 class="text-xl font-bold text-neon-pink mb-2">Poster Making</h4>
                        <p class="text-sm text-gray-400 mb-4">Unleash your creativity using Canva!</p>
                        <a href="https://forms.gle/cLsyvM6w77h5PGKw5" target="_blank" class="btn inline-block px-6 py-2 rounded-full font-bold text-white uppercase text-xs tracking-wide shadow-md">
                            Register Now
                        </a>
                    </div>
                    <!-- Debate Competition Card -->
                    <div class="event-card p-6 rounded-2xl text-center shadow-lg">
                        <h4 class="text-xl font-bold text-neon-pink mb-2">Debate Competition</h4>
                        <p class="text-sm text-gray-400 mb-4">Put your arguments to the test.</p>
                        <a href="https://forms.gle/b1CH5FMnzQxHRwck7" target="_blank" class="btn inline-block px-6 py-2 rounded-full font-bold text-white uppercase text-xs tracking-wide shadow-md">
                            Register Now
                        </a>
                    </div>
                    <!-- Stand-up Comedy Card -->
                    <div class="event-card p-6 rounded-2xl text-center shadow-lg">
                        <h4 class="text-xl font-bold text-neon-pink mb-2">Stand Up Comedy</h4>
                        <p class="text-sm text-gray-400 mb-4">A stage to tickle some funny bones.</p>
                        <a href="https://forms.gle/e5ocpVrgDUu7Rz3b9" target="_blank" class="btn inline-block px-6 py-2 rounded-full font-bold text-white uppercase text-xs tracking-wide shadow-md">
                            Register Now
                        </a>
                    </div>
                </div>
            </div>

        </div>

        <div id="welcome-message" class="transition-transform-opacity opacity-100 transform-none">
            <p class="text-base text-gray-400 mt-8">Please select an event type from the dropdown to view details.</p>
        </div>
    </div>

    <!-- JavaScript for Dynamic Content Loading -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const eventTypeDropdown = document.getElementById('event-type');
            const technicalEventsSection = document.getElementById('technical-events');
            const nonTechnicalEventsSection = document.getElementById('non-technical-events');
            const welcomeMessage = document.getElementById('welcome-message');

            eventTypeDropdown.addEventListener('change', (event) => {
                const selectedValue = event.target.value;

                // Hide all content and welcome message
                technicalEventsSection.classList.remove('opacity-100');
                technicalEventsSection.classList.add('opacity-0');
                nonTechnicalEventsSection.classList.remove('opacity-100');
                nonTechnicalEventsSection.classList.add('opacity-0');
                welcomeMessage.classList.add('opacity-0', 'transform', 'scale-95');

                // Wait for hide transition to finish, then show new content
                setTimeout(() => {
                    technicalEventsSection.classList.add('hidden');
                    nonTechnicalEventsSection.classList.add('hidden');
                    welcomeMessage.classList.add('hidden');

                    if (selectedValue === 'technical') {
                        technicalEventsSection.classList.remove('hidden');
                        setTimeout(() => {
                            technicalEventsSection.classList.remove('opacity-0');
                            technicalEventsSection.classList.add('opacity-100');
                        }, 50);
                    } else if (selectedValue === 'non-technical') {
                        nonTechnicalEventsSection.classList.remove('hidden');
                        setTimeout(() => {
                            nonTechnicalEventsSection.classList.remove('opacity-0');
                            nonTechnicalEventsSection.classList.add('opacity-100');
                        }, 50);
                    }
                }, 500); // This duration should match the CSS transition duration
            });
        });
    </script>
</body>
</html>
