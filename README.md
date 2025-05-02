
<!Doctype hmtl>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* Apply Inter font globally */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Smooth scrolling behavior */
        html {
            scroll-behavior: smooth;
        }
        /* Simple animation for section loading (optional) */
        .section-fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .section-visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <header class="bg-gradient-to-r from-blue-600 to-indigo-700 text-white py-12 md:py-20 shadow-lg">
        <div class="container mx-auto px-6 text-center">
            <img src="https://placehold.co/150x150/e2e8f0/6366f1?text=You" alt="Your Profile Picture" class="w-32 h-32 md:w-40 md:h-40 rounded-full mx-auto mb-6 border-4 border-white shadow-md object-cover" onerror="this.onerror=null; this.src='https://placehold.co/150x150/e2e8f0/333?text=Image+Error';">
            <h1 class="text-3xl md:text-5xl font-bold mb-2">Your Name</h1>
            <p class="text-lg md:text-xl text-indigo-200 mb-4">Web Developer | Designer | Lifelong Learner</p>
            <p class="max-w-2xl mx-auto text-indigo-100">
                Passionate about creating beautiful and functional web experiences. Currently exploring new technologies in front-end development.
            </p>
            <nav class="mt-8 space-x-4">
                <a href="#about" class="text-white hover:text-indigo-200 transition duration-300 px-3 py-1 rounded hover:bg-white/10">About</a>
                <a href="#skills" class="text-white hover:text-indigo-200 transition duration-300 px-3 py-1 rounded hover:bg-white/10">Skills</a>
                <a href="#projects" class="text-white hover:text-indigo-200 transition duration-300 px-3 py-1 rounded hover:bg-white/10">Projects</a>
                <a href="#contact" class="text-white hover:text-indigo-200 transition duration-300 px-3 py-1 rounded hover:bg-white/10">Contact</a>
            </nav>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">

        <section id="about" class="mb-16 p-6 md:p-8 bg-white rounded-lg shadow-md section-fade-in">
            <h2 class="text-2xl md:text-3xl font-bold text-center text-indigo-700 mb-6">About Me</h2>
            <p class="text-gray-700 leading-relaxed text-center max-w-3xl mx-auto">
                Hello! I'm [Your Name], a [Your Title/Profession] based in [Your Location, e.g., Phnom Penh]. I have a passion for [mention your passion, e.g., building intuitive user interfaces, solving complex problems].
                My journey into [your field] started when [briefly mention how you started]. Since then, I've worked on various projects, honing my skills in [mention 1-2 key skills].
                I'm always eager to learn and adapt to new challenges in the ever-evolving tech landscape. When I'm not coding, you can find me [mention a hobby or interest].
            </p>
        </section>

        <section id="skills" class="mb-16 p-6 md:p-8 bg-white rounded-lg shadow-md section-fade-in">
            <h2 class="text-2xl md:text-3xl font-bold text-center text-indigo-700 mb-8">Skills</h2>
            <div class="flex flex-wrap justify-center gap-3 md:gap-4">
                <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">HTML5</span>
                <span class="bg-blue-100 text-blue-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">CSS3</span>
                <span class="bg-yellow-100 text-yellow-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">JavaScript (ES6+)</span>
                <span class="bg-sky-100 text-sky-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">Tailwind CSS</span>
                <span class="bg-green-100 text-green-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">React</span>
                <span class="bg-gray-100 text-gray-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">Git & GitHub</span>
                <span class="bg-purple-100 text-purple-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">Responsive Design</span>
                <span class="bg-red-100 text-red-800 text-sm font-medium px-4 py-2 rounded-full shadow-sm">Problem Solving</span>
                </div>
        </section>

        <section id="projects" class="mb-16 p-6 md:p-8 bg-white rounded-lg shadow-md section-fade-in">
            <h2 class="text-2xl md:text-3xl font-bold text-center text-indigo-700 mb-8">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <article class="bg-gray-50 p-6 rounded-lg border border-gray-200 shadow-sm hover:shadow-lg transition-shadow duration-300">
                    <h3 class="text-xl font-semibold text-indigo-800 mb-3">Project Title One</h3>
                    <p class="text-gray-600 mb-4 text-sm leading-relaxed">
                        A brief description of the project. What problem did it solve? What technologies were used (e.g., React, Tailwind)? Highlight your key contributions.
                    </p>
                    <a href="#" target="_blank" class="inline-block text-indigo-600 hover:text-indigo-800 font-medium transition duration-300 text-sm">
                        View Project &rarr;
                    </a>
                     </article>

                <article class="bg-gray-50 p-6 rounded-lg border border-gray-200 shadow-sm hover:shadow-lg transition-shadow duration-300">
                    <h3 class="text-xl font-semibold text-indigo-800 mb-3">Project Title Two</h3>
                    <p class="text-gray-600 mb-4 text-sm leading-relaxed">
                        Describe another significant project. Focus on the impact or unique features. Mention the tech stack (e.g., Vanilla JS, API integration).
                    </p>
                    <a href="#" target="_blank" class="inline-block text-indigo-600 hover:text-indigo-800 font-medium transition duration-300 text-sm">
                        View Project &rarr;
                    </a>
                </article>

                <article class="bg-gray-50 p-6 rounded-lg border border-gray-200 shadow-sm hover:shadow-lg transition-shadow duration-300">
                    <h3 class="text-xl font-semibold text-indigo-800 mb-3">Project Title Three</h3>
                    <p class="text-gray-600 mb-4 text-sm leading-relaxed">
                        Showcase a different type of project or skill. Maybe a design project, a backend service, or a contribution to open source.
                    </p>
                    <a href="#" target="_blank" class="inline-block text-indigo-600 hover:text-indigo-800 font-medium transition duration-300 text-sm">
                        View Project &rarr;
                    </a>
                </article>
            </div>
        </section>

        <section id="contact" class="p-6 md:p-8 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-lg shadow-md section-fade-in">
            <h2 class="text-2xl md:text-3xl font-bold text-center text-indigo-700 mb-6">Get In Touch</h2>
            <p class="text-center text-gray-700 mb-8 max-w-xl mx-auto">
                I'm always open to discussing new projects, creative ideas, or opportunities to be part of your visions. Feel free to reach out!
            </p>
            <div class="flex justify-center items-center space-x-6 md:space-x-8">
                <a href="mailto:your.email@example.com" class="text-gray-600 hover:text-indigo-600 transition duration-300 flex flex-col items-center space-y-1">
                    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-mail"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
                    <span class="text-xs md:text-sm">Email</span>
                </a>
                <a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener noreferrer" class="text-gray-600 hover:text-indigo-600 transition duration-300 flex flex-col items-center space-y-1">
                     <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
                     <span class="text-xs md:text-sm">LinkedIn</span>
                </a>
                <a href="https://github.com/yourusername" target="_blank" rel="noopener noreferrer" class="text-gray-600 hover:text-indigo-600 transition duration-300 flex flex-col items-center space-y-1">
                    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-github"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
                    <span class="text-xs md:text-sm">GitHub</span>
                </a>
                 </div>
        </section>

    </main>

    <footer class="bg-gray-800 text-gray-400 text-center py-6 mt-16">
        <div class="container mx-auto px-6">
            <p class="text-sm">&copy; <span id="current-year"></span> Your Name. All rights reserved.</p>
            <p class="text-xs mt-2">Current Time in Phnom Penh: <span id="current-time">Loading...</span></p>
        </div>
    </footer>

    <script>
        // --- Simple JavaScript for dynamic elements ---

        // 1. Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // 2. Display current time in Phnom Penh and update every second
        function displayPhnomPenhTime() {
            const now = new Date();
            const options = {
                timeZone: 'Asia/Phnom_Penh', // Correct IANA time zone identifier
                hour: '2-digit',
                minute: '2-digit',
                second: '2-digit',
                hour12: true // Use AM/PM format
            };
            try {
                const formattedTime = now.toLocaleTimeString('en-US', options);
                 const timeElement = document.getElementById('current-time');
                 if(timeElement) {
                    timeElement.textContent = formattedTime;
                 }
            } catch (error) {
                console.error("Error formatting time:", error);
                 const timeElement = document.getElementById('current-time');
                 if(timeElement) {
                    timeElement.textContent = "Time unavailable";
                 }
            }
        }

        // Initial call
        displayPhnomPenhTime();
        // Update every second
        setInterval(displayPhnomPenhTime, 1000);

        // 3. Simple fade-in effect for sections on scroll (optional)
        const sections = document.querySelectorAll('.section-fade-in');

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('section-visible');
                    // Optional: Stop observing once visible to save resources
                    // observer.unobserve(entry.target);
                }
                // Optional: fade out when scrolling away
                // else {
                //     entry.target.classList.remove('section-visible');
                // }
            });
        }, {
            rootMargin: '0px', // can adjust trigger point
            threshold: 0.1  // Trigger when 10% of the element is visible
        });

        sections.forEach(section => {
            observer.observe(section);
        });

        // Note: Smooth scrolling is handled by CSS `scroll-behavior: smooth;`

    </script>

</body>
</html>
