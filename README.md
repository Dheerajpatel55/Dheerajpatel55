<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dheeraj Patel - Software Development Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub dark theme background */
            color: #c9d1d9; /* GitHub dark theme text color */
            line-height: 1.6;
            margin: 0;
            padding: 0;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        .section-heading {
            color: #5DADE2; /* Blue */
            font-weight: 700;
            margin-bottom: 1.5rem;
            text-align: center;
            font-size: 2.25rem; /* text-4xl */
        }
        .card {
            background-color: #161b22; /* Slightly lighter than body for cards */
            border-radius: 0.75rem; /* rounded-xl */
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border: 1px solid #30363d; /* Subtle border */
        }
        .link-button {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            font-weight: 600;
            transition: all 0.3s ease;
            text-decoration: none;
            color: white;
            margin: 0.5rem;
        }
        .link-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }
        .linkedin-btn { background-color: #0A66C2; }
        .linkedin-btn:hover { background-color: #074b92; }
        .github-btn { background-color: #181717; }
        .github-btn:hover { background-color: #000000; }
        .leetcode-btn { background-color: #FE7F2D; }
        .leetcode-btn:hover { background-color: #d86a20; }
        .hackerrank-btn { background-color: #2EC866; }
        .hackerrank-btn:hover { background-color: #209a4d; }

        /* Custom styling for project list */
        .project-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 1rem;
        }
        .project-item svg {
            margin-right: 0.75rem;
            flex-shrink: 0;
            color: #FF6F61; /* Accent color for icons */
        }
        .project-item p {
            margin: 0;
        }

        /* Responsive adjustments for images */
        .stats-image {
            max-width: 100%;
            height: auto;
            border-radius: 0.5rem;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 1rem;
        }

        /* Responsive grid for stats */
        @media (min-width: 768px) {
            .stats-grid {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
                gap: 1.5rem;
            }
        }

        /* Responsive adjustments for skill icons */
        .skill-icons-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem; /* Space between icons */
        }

        /* Ensure banner scales correctly */
        .banner-img {
            width: 100%;
            height: auto; /* Maintain aspect ratio */
            max-height: 200px; /* Limit max height */
            object-fit: cover; /* Cover the area, crop if necessary */
            border-radius: 0.75rem;
        }
    </style>
</head>
<body class="antialiased">
    <div class="container">

        <section class="text-center mb-12">
            <a href="https://github.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer">
                <img src="https://media.giphy.com/media/3o7aCVzXjNMt3o3cHK/giphy.gif" alt="Banner: Dheeraj Patel's GitHub Profile" class="banner-img mx-auto shadow-lg">
            </a>
        </section>

        <section class="text-center mb-12">
            <h1 class="text-5xl font-extrabold mb-2">
                <span style="color:#F54768;">Hey there 👋, I'm <strong>Dheeraj Patel</strong></span>
            </h1>
            <h3 class="text-2xl font-medium mb-6">
                <span style="color:#5DADE2;">Software Development Engineer | Web Wizard | Tech Visionary</span>
            </h3>
            <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=FF6F61&center=true&vCenter=true&width=600&lines=Engineer+by+Code%2C+Creator+by+Heart.;Crafting+modern+web+solutions.;Innovating+with+every+line+of+code." alt="Typing Animation" class="mx-auto max-w-full h-auto">
        </section>

        <hr class="border-t border-gray-700 my-12">

        <section class="card">
            <h2 class="section-heading">🚀 About Me</h2>
            <ul class="list-disc list-inside space-y-3 text-lg">
                <li>🔭 Currently building <strong class="text-blue-400">high-impact web applications</strong> and <strong class="text-blue-400">security-driven systems</strong>.</li>
                <li>⚙️ Deep diving into <strong class="text-green-400">Blockchain</strong>, <strong class="text-green-400">AI</strong>, and <strong class="text-green-400">Secure Voting Systems</strong>.</li>
                <li>💡 Passionate about <strong class="text-purple-400">defense technology</strong> and the limitless possibilities of <strong class="text-purple-400">generative AI</strong>.</li>
                <li>📜 <a href="#" class="text-blue-500 hover:underline">My Resume (Coming Soon)</a> | <a href="#" class="text-blue-500 hover:underline">My Portfolio (Coming Soon)</a></li>
                <li>📫 Reach me directly at: <strong class="text-yellow-400">dheerajpatel.sde@gmail.com</strong></li>
            </ul>
        </section>

        <section class="card">
            <h2 class="section-heading">🛠 Tech Toolkit & What I Use</h2>
            <div class="skill-icons-container">
                <img src="https://skillicons.dev/icons?i=java,js,html,css,python,c,cpp,react,mysql,mongodb,flask,bootstrap,git,vscode,jupyter,arduino,docker,linux" alt="My Tech Stack" class="w-full h-auto max-w-md md:max-w-xl lg:max-w-2xl">
            </div>
            <p class="text-center text-sm mt-4 text-gray-400"><em>(Adding Docker and Linux to represent broader development environments)</em></p>
        </section>

        <section class="card text-center">
            <h2 class="section-heading">🌐 Let's Connect & Collaborate</h2>
            <div class="flex flex-wrap justify-center">
                <a href="https://www.linkedin.com/in/dheeraj-patel-dev/" target="_blank" rel="noopener noreferrer" class="link-button linkedin-btn">LinkedIn</a>
                <a href="https://github.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer" class="link-button github-btn">GitHub</a>
                <a href="https://leetcode.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer" class="link-button leetcode-btn">LeetCode</a>
                <a href="https://www.hackerrank.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer" class="link-button hackerrank-btn">HackerRank</a>
            </div>
        </section>

        <section class="card">
            <h2 class="section-heading">📈 GitHub Stats & Achievements</h2>
            <div class="stats-grid">
                <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Dheerajpatel55&theme=github_dark" alt="GitHub Profile Details" class="stats-image mx-auto">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dheerajpatel55&theme=highcontrast" alt="GitHub Streak Stats" class="stats-image mx-auto">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dheerajpatel55&layout=compact&theme=radical" alt="Top Languages" class="stats-image mx-auto">
            </div>
            <div class="text-center mt-8">
                <img src="https://github-profile-trophy.vercel.app/?username=Dheerajpatel55&theme=gruvbox&no-bg=true&margin-w=10" alt="GitHub Trophies" class="mx-auto max-w-full h-auto">
            </div>
        </section>

        <section class="card">
            <h2 class="section-heading">✨ Highlighted Projects & Innovations</h2>
            <ul class="space-y-4 text-lg">
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-2 4h4m-7-9h14a5 5 0 010 10H5a5 5 0 010-10z"></path></svg>
                    <p><strong class="text-red-400">Blockchain-based Secure Voting Prototype:</strong> A robust, transparent, and immutable voting system built on blockchain technology to ensure integrity and trust.</p>
                </li>
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"></path></svg>
                    <p><strong class="text-red-400">BERT-powered Healthcare Chatbot:</strong> An intelligent conversational agent utilizing BERT for natural language understanding to provide healthcare information and support.</p>
                </li>
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
                    <p><strong class="text-red-400">Smart Wearable Health Monitoring App:</strong> A mobile application integrated with wearable devices for real-time health data collection, analysis, and alerts.</p>
                </li>
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                    <p><strong class="text-red-400">Full Stack Resume & ATS Score Checker:</strong> A comprehensive web application designed to help job seekers optimize their resumes for Applicant Tracking Systems.</p>
                </li>
            </ul>
        </section>

        <section class="text-center my-12">
            <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="GitHub Quotes" class="mx-auto max-w-full h-auto">
        </section>

        <section class="text-center mt-12 mb-8">
            <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00CED1&center=true&width=450&lines=Actively+Seeking+Internships+and+Collabs!;Let's+Build+the+Future+Together!" alt="Call to Action" class="mx-auto max-w-full h-auto">
        </section>

    </div>
</body>
</html>
