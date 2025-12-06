<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xteam.in - Official Portal</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Inter font -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        /* Custom background gradient for the header/hero section */
        .hero-bg {
            background: linear-gradient(135deg, #1f2937 0%, #374151 100%);
        }
    </style>
</head>
<body class="selection:bg-indigo-300 selection:text-indigo-900">

    <!-- Header Section -->
    <header class="hero-bg text-white shadow-lg p-4 sm:p-6">
        <div class="max-w-4xl mx-auto flex justify-between items-center">
            <h1 class="text-3xl font-extrabold tracking-tight">Xteam.in</h1>
            <nav>
                <a href="#" class="text-indigo-300 hover:text-white transition duration-200 text-sm sm:text-base">Portal</a>
            </nav>
        </div>
    </header>

    <!-- Main Content / Registration Form -->
    <main class="flex-grow p-4 sm:p-8 flex items-center justify-center">
        <div class="w-full max-w-lg bg-white p-6 sm:p-10 rounded-2xl shadow-2xl transition duration-300 hover:shadow-indigo-400/50 border border-gray-100">

            <div class="text-center mb-8">
                <h2 class="text-4xl font-bold text-gray-900 mb-2">Welcome, Xteam!</h2>
                <p class="text-lg text-gray-600">Official Registration & Access Point.</p>
            </div>

            <!-- Registration Status Message Box (Hidden by default) -->
            <div id="status-message" class="hidden p-6 mb-6 rounded-2xl bg-indigo-50 border border-indigo-400 text-indigo-800 space-y-4" role="alert">
                <!-- Content will be injected by JavaScript -->
            </div>

            <!-- Registration Form -->
            <form id="registration-form" class="space-y-6">

                <div>
                    <label for="team-name" class="block text-sm font-medium text-gray-700 mb-1">Team Name (Pre-registered)</label>
                    <input id="team-name" type="text" value="Xteam" readonly
                           class="w-full p-3 border border-gray-300 rounded-lg bg-gray-50 cursor-not-allowed focus:ring-1 focus:ring-indigo-500 focus:border-indigo-500 transition duration-150">
                </div>

                <div>
                    <label for="contact-name" class="block text-sm font-medium text-gray-700 mb-1">Contact Name</label>
                    <input id="contact-name" type="text" placeholder="Enter team leader's name" required
                           class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 transition duration-150 shadow-sm">
                </div>

                <div>
                    <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Contact Email</label>
                    <input id="email" type="email" placeholder="example@xteam.in" required
                           class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 transition duration-150 shadow-sm">
                </div>

                <button type="submit" id="submit-button"
                        class="w-full flex justify-center py-3 px-4 border border-transparent rounded-lg shadow-lg text-lg font-semibold text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-4 focus:ring-indigo-500 focus:ring-opacity-50 transition duration-300 transform hover:scale-[1.01] active:scale-[0.98]">
                    Submit Registration & Request Approval
                </button>
            </form>

        </div>
    </main>

    <!-- Footer Section -->
    <footer class="p-4 bg-gray-100 text-gray-600 text-center text-sm border-t border-gray-200">
        &copy; 2024 Xteam.in. All rights reserved.
    </footer>

    <script>
        document.getElementById('registration-form').addEventListener('submit', function(event) {
            event.preventDefault();

            const form = document.getElementById('registration-form');
            const statusMessage = document.getElementById('status-message');
            const submitButton = document.getElementById('submit-button');

            const teamName = document.getElementById('team-name').value;
            const contactName = document.getElementById('contact-name').value;
            const email = document.getElementById('email').value;
            // IMPORTANT: The administrator's email is hardcoded here
            const adminEmail = 'azizvabdul3@gmail.com';

            // Simple validation check
            if (!contactName || !email) {
                // Display error 
                statusMessage.classList.remove('hidden', 'bg-indigo-50', 'border-indigo-400', 'text-indigo-800');
                statusMessage.classList.add('bg-red-100', 'border-red-400', 'text-red-800');
                statusMessage.innerHTML = '<p class="font-bold">Error:</p><p>Please fill out all required fields before proceeding.</p>';
                statusMessage.scrollIntoView({ behavior: 'smooth' });
                return;
            }

            // Construct the mailto link content
            const subject = encodeURIComponent(`${teamName} Registration Approval Request - ${contactName}`);
            const body = encodeURIComponent(`Team Name: ${teamName}\nContact Name: ${contactName}\nContact Email: ${email}\n\nI confirm these details are correct and request registration approval.`);

            const mailtoLink = `mailto:${adminEmail}?subject=${subject}&body=${body}`;

            // 1. Hide the form
            form.classList.add('hidden');

            // 2. Generate and display the final step message
            statusMessage.classList.remove('hidden', 'bg-red-100', 'border-red-400', 'text-red-800');
            statusMessage.classList.add('bg-indigo-50', 'border-indigo-400', 'text-indigo-800');

            statusMessage.innerHTML = `
                <p class="text-xl font-bold">Step 2: Send Approval Request</p>
                <p>Thank you for submitting your details. To finalize your **Xteam** registration, please click the button below to send the official approval request to the administrator (${adminEmail}).</p>
                <a href="${mailtoLink}"
                   class="inline-block w-full text-center py-3 px-4 rounded-lg shadow-md text-lg font-semibold text-white bg-green-600 hover:bg-green-700 transition duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 inline-block mr-2" viewBox="0 0 20 20" fill="currentColor">
                        <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
                        <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
                    </svg>
                    Send Approval Email Now
                </a>
                <p class="text-sm mt-2 text-indigo-600">The email subject and body are pre-filled with your registration data.</p>
            `;

            // Optional: Scroll to the message
            statusMessage.scrollIntoView({ behavior: 'smooth' });
        });
    </script>
</body>
</html>

# Xteam 
