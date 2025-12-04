<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marivic Solares - Developer Profile</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Inter font -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        /* Keyframes for the typewriter effect */
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }

        /* Keyframes for the blinking cursor */
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #3b82f6; } /* Tailwind blue-500 */
        }

        /* Keyframes for the moving letters effect (subtle float) */
        @keyframes float {
            0% { transform: translateY(0px) }
            50% { transform: translateY(-5px) }
            100% { transform: translateY(0px) }
        }

        .typewriter h1 {
            overflow: hidden; /* Ensures the content is not revealed until the animation */
            border-right: .15em solid #3b82f6; /* The simulated cursor */
            white-space: nowrap; /* Keeps the content on a single line */
            margin: 0 auto; /* Gives that scrolling effect as the typing happens */
            letter-spacing: .15em; /* Adjust as needed */
            animation: 
                typing 3.5s steps(30, end),
                blink-caret .75s step-end infinite;
            width: 30ch; /* Text length */
        }
        
        .animated-skill-item {
            animation: float 4s ease-in-out infinite;
        }

        /* Apply different delays to skill items for staggered floating */
        .animated-skill-item:nth-child(2) { animation-delay: 0.5s; }
        .animated-skill-item:nth-child(3) { animation-delay: 1.0s; }
        .animated-skill-item:nth-child(4) { animation-delay: 1.5s; }
        .animated-skill-item:nth-child(5) { animation-delay: 2.0s; }
        .animated-skill-item:nth-child(6) { animation-delay: 2.5s; }
        .animated-skill-item:nth-child(7) { animation-delay: 3.0s; }

    </style>
</head>
<body>

<div class="max-w-4xl w-full mx-auto p-6 md:p-10 bg-white shadow-xl rounded-2xl">
    
    <!-- Header and Animated Title -->
    <div class="text-center mb-10 border-b pb-6 border-gray-100">
        <div class="typewriter mx-auto text-xl md:text-3xl font-extrabold text-gray-800">
            <h1 class="mx-auto">👋 Hi, I'm MARIVIC C. SOLARES!</h1>
        </div>
        <p class="mt-4 text-sm md:text-lg text-blue-600 font-medium">Front-End Focused IT Student | Eager Intern</p>
    </div>

    <!-- Profile Summary -->
    <div class="mb-8">
        <h2 class="text-2xl font-semibold text-gray-700 border-l-4 border-blue-500 pl-3 mb-4">Profile</h2>
        <p class="text-gray-600 leading-relaxed bg-blue-50 p-4 rounded-lg">
            Motivated 4th-year BS in Information Technology student with a strong passion for **web development**, 
            particularly in front-end technologies. Highly proficient in computer literacy and adaptable to various 
            technical tasks. Eager to contribute as a front-end developer intern or in an IT support role.
        </p>
    </div>

    <!-- Skills & Expertise (Animated Floating Items) -->
    <div class="mb-8">
        <h2 class="text-2xl font-semibold text-gray-700 border-l-4 border-blue-500 pl-3 mb-6">🛠️ Skills & Expertise</h2>
        <div class="flex flex-wrap justify-center gap-4">
            <!-- Animated Skill Items -->
            <span class="animated-skill-item bg-blue-500 text-white px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">ReactJS</span>
            <span class="animated-skill-item bg-green-500 text-white px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">Javascript</span>
            <span class="animated-skill-item bg-red-500 text-white px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">HTML5 / CSS</span>
            <span class="animated-skill-item bg-yellow-500 text-gray-800 px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">Git / GitHub</span>
            <span class="animated-skill-item bg-purple-500 text-white px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">Figma / Canva</span>
            <span class="animated-skill-item bg-teal-500 text-white px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">Bootstrap</span>
            <span class="animated-skill-item bg-pink-500 text-white px-4 py-2 rounded-full shadow-lg hover:shadow-xl transition duration-300">Problem-Solving</span>
        </div>
    </div>

    <!-- Featured Project -->
    <div class="mb-8">
        <h2 class="text-2xl font-semibold text-gray-700 border-l-4 border-blue-500 pl-3 mb-4">🚀 Featured Project: Capstone</h2>
        <div class="bg-white border border-gray-200 p-5 rounded-xl shadow-md">
            <h3 class="text-xl font-bold text-gray-800 mb-2">AI-Powered Recipe Recommender for Native Kapampangan Dishes</h3>
            <p class="text-sm font-semibold text-blue-600 mb-3">Status: Ongoing (Mar 2025 - Present)</p>
            <ul class="list-disc list-inside space-y-1 text-gray-600">
                <li>**Role:** Led a development team.</li>
                <li>**Key Contribution:** Designed and implemented responsive front-end interfaces using HTML, CSS, and JavaScript.</li>
                <li>**Outcome:** Coordinated tasks, ensured milestones were met, and conducted system testing.</li>
            </ul>
        </div>
    </div>

    <!-- Certifications Section -->
    <div class="mb-8">
        <h2 class="text-2xl font-semibold text-gray-700 border-l-4 border-blue-500 pl-3 mb-4">🌱 Certifications</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <!-- React Basics Card -->
            <div class="p-4 border border-blue-300 bg-blue-50 rounded-lg shadow-sm">
                <h4 class="font-bold text-blue-800">React Basics</h4>
                <p class="text-sm text-gray-600">Meta (Coursera) | Focus: Building responsive web applications with React.js.</p>
            </div>
            <!-- Version Control Card -->
            <div class="p-4 border border-blue-300 bg-blue-50 rounded-lg shadow-sm">
                <h4 class="font-bold text-blue-800">Version Control</h4>
                <p class="text-sm text-gray-600">Meta (Coursera) | Focus: Practical skills using Git, GitHub, and CLI.</p>
            </div>
            <!-- Other certifications can follow this pattern -->
        </div>
    </div>
    
    <!-- Connect Section -->
    <div class="pt-6 border-t mt-6 text-center">
        <h2 class="text-2xl font-semibold text-gray-700 mb-4">🤝 Let's Connect!</h2>
        <p class="text-lg text-gray-700">marivic.c.solares@gmail.com</p>
        <p class="text-sm text-gray-500 mt-2">Floridablanca, Pampanga, Philippines</p>
    </div>

</div>

</body>
</html>
