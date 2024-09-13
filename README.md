# MrBearsHorseRacingTips
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MrBearsRacingTips</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.js"></script>
    <style>
        body {
            background-color: #121212;
            color: #e0e0e0;
        }
        .bg-race {
            background-image: url('/api/placeholder/1920/1080');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col">
    <header class="bg-gray-900 p-4">
        <nav class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">MrBearsRacingTips</h1>
            <ul class="flex space-x-4">
                <li><a href="#home" class="hover:text-yellow-400">Home</a></li>
                <li><a href="#about" class="hover:text-yellow-400">About Us</a></li>
                <li><a href="#contact" class="hover:text-yellow-400">Contact</a></li>
                <li><a href="#feedback" class="hover:text-yellow-400">Feedback</a></li>
                <li><a href="#tips" class="hover:text-yellow-400">Free Tips</a></li>
                <li><a href="#history" class="hover:text-yellow-400">Tip History</a></li>
            </ul>
        </nav>
    </header>

    <main class="flex-grow">
        <section id="home" class="bg-race h-96 flex items-center justify-center">
            <div class="bg-black bg-opacity-50 p-8 rounded-lg">
                <h2 class="text-4xl font-bold mb-4">Welcome to MrBearsRacingTips</h2>
                <p class="text-xl">Your go-to source for expert horse racing tips!</p>
            </div>
        </section>

        <section id="about" class="py-12 bg-gray-800">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold mb-6">About Us</h2>
                <p>MrBearsRacingTips is your trusted source for expert horse racing analysis and predictions. With years of experience and a passion for the sport, we provide valuable insights to help you make informed betting decisions.</p>
            </div>
        </section>

        <section id="contact" class="py-12 bg-gray-900">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold mb-6">Contact Us</h2>
                <form class="max-w-lg mx-auto">
                    <div class="mb-4">
                        <label for="name" class="block mb-2">Name</label>
                        <input type="text" id="name" class="w-full p-2 bg-gray-700 rounded" required>
                    </div>
                    <div class="mb-4">
                        <label for="email" class="block mb-2">Email</label>
                        <input type="email" id="email" class="w-full p-2 bg-gray-700 rounded" required>
                    </div>
                    <div class="mb-4">
                        <label for="message" class="block mb-2">Message</label>
                        <textarea id="message" class="w-full p-2 bg-gray-700 rounded" rows="4" required></textarea>
                    </div>
                    <button type="submit" class="bg-yellow-600 text-white px-4 py-2 rounded hover:bg-yellow-700">Send</button>
                </form>
            </div>
        </section>

        <section id="feedback" class="py-12 bg-gray-800">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold mb-6">Feedback</h2>
                <form class="max-w-lg mx-auto">
                    <div class="mb-4">
                        <label for="rating" class="block mb-2">Rating</label>
                        <select id="rating" class="w-full p-2 bg-gray-700 rounded" required>
                            <option value="">Select a rating</option>
                            <option value="5">5 Stars</option>
                            <option value="4">4 Stars</option>
                            <option value="3">3 Stars</option>
                            <option value="2">2 Stars</option>
                            <option value="1">1 Star</option>
                        </select>
                    </div>
                    <div class="mb-4">
                        <label for="feedback-text" class="block mb-2">Your Feedback</label>
                        <textarea id="feedback-text" class="w-full p-2 bg-gray-700 rounded" rows="4" required></textarea>
                    </div>
                    <button type="submit" class="bg-yellow-600 text-white px-4 py-2 rounded hover:bg-yellow-700">Submit Feedback</button>
                </form>
            </div>
        </section>

        <section id="tips" class="py-12 bg-gray-900">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold mb-6">Free Tips Today</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="bg-gray-800 p-4 rounded">
                        <h3 class="text-xl font-bold mb-2">Tip #1</h3>
                        <p>Horse: Thunderbolt</p>
                        <p>Race: Ascot 3:30 PM</p>
                        <p>Odds: 5/1</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded">
                        <h3 class="text-xl font-bold mb-2">Tip #2</h3>
                        <p>Horse: Silver Streak</p>
                        <p>Race: Cheltenham 2:15 PM</p>
                        <p>Odds: 7/2</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded">
                        <h3 class="text-xl font-bold mb-2">Tip #3</h3>
                        <p>Horse: Golden Arrow</p>
                        <p>Race: Newmarket 4:00 PM</p>
                        <p>Odds: 6/1</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded">
                        <h3 class="text-xl font-bold mb-2">Tip #4</h3>
                        <p>Horse: Midnight Runner</p>
                        <p>Race: Goodwood 3:45 PM</p>
                        <p>Odds: 4/1</p>
                    </div>
                    <div class="bg-gray-800 p-4 rounded">
                        <h3 class="text-xl font-bold mb-2">Tip #5</h3>
                        <p>Horse: Lucky Charm</p>
                        <p>Race: York 2:30 PM</p>
                        <p>Odds: 8/1</p>
                    </div>
                </div>
                <div class="mt-8 text-center">
                    <p class="mb-4">Want more tips? Register for free to access our full range of expert predictions!</p>
                    <button class="bg-yellow-600 text-white px-6 py-3 rounded-lg text-lg font-bold hover:bg-yellow-700">Register Now</button>
                </div>
            </div>
        </section>

        <section id="history" class="py-12 bg-gray-800">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl font-bold mb-6">Tip History</h2>
                <table class="w-full bg-gray-900">
                    <thead>
                        <tr>
                            <th class="p-2 text-left">Date</th>
                            <th class="p-2 text-left">Horse</th>
                            <th class="p-2 text-left">Race</th>
                            <th class="p-2 text-left">Result</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="p-2">2024-09-12</td>
                            <td class="p-2">Fast Lane</td>
                            <td class="p-2">Ascot 2:00 PM</td>
                            <td class="p-2 text-green-500">Won</td>
                        </tr>
                        <tr>
                            <td class="p-2">2024-09-11</td>
                            <td class="p-2">River Dance</td>
                            <td class="p-2">Newmarket 3:15 PM</td>
                            <td class="p-2 text-red-500">Lost</td>
                        </tr>
                        <tr>
                            <td class="p-2">2024-09-10</td>
                            <td class="p-2">Storm Chaser</td>
                            <td class="p-2">Cheltenham 4:30 PM</td>
                            <td class="p-2 text-green-500">Won</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>
    </main>

    <footer class="bg-gray-900 py-6">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2024 MrBearsRacingTips. All rights reserved.</p>
            <p class="mt-2">Disclaimer: Please gamble responsibly. Our tips are for entertainment purposes only.</p>
        </div>
    </footer>

    <script>
        // Add interactivity here
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Registration modal functionality
        const registerButton = document.querySelector('button');
        registerButton.addEventListener('click', () => {
            alert('Registration feature coming soon!');
        });
    </script>
</body>
</html>
