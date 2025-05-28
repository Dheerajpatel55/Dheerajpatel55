<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dheeraj Patel - Software Development Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto+Mono:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto Mono', monospace;
            background: linear-gradient(180deg, #000000 0%, #1a1a1a 100%);
            color: #e0e0e0;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
        }
        .section-heading {
            font-family: 'Orbitron', sans-serif;
            color: #00f7ff;
            font-weight: 700;
            font-size: 2.5rem;
            text-align: center;
            margin-bottom: 2rem;
            text-shadow: 0 0 10px rgba(0, 247, 255, 0.5);
        }
        .card {
            background: #0d0d0d;
            border: 1px solid #333;
            border-radius: 1rem;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 8px 24px rgba(0, 247, 255, 0.1), 0 0 20px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 32px rgba(0, 247, 255, 0.2);
        }
        .link-button {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            font-family: 'Orbitron', sans-serif;
            font-weight: 600;
            text-transform: uppercase;
            text-decoration: none;
            color: #000;
            background: linear-gradient(45deg, #00f7ff, #ff00ff);
            border: 2px solid transparent;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
            margin: 0.5rem;
        }
        .link-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            transition: 0.5s;
        }
        .link-button:hover::before {
            left: 100%;
        }
        .link-button:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px rgba(0, 247, 255, 0.7);
            border-color: #ff00ff;
        }
        .linkedin-btn { background: linear-gradient(45deg, #0077b5, #00f7ff); }
        .github-btn { background: linear-gradient(45deg, #181717, #00f7ff); }
        .leetcode-btn { background: linear-gradient(45deg, #f5a623, #ff00ff); }
        .hackerrank-btn { background: linear-gradient(45deg, #2ec866, #00f7ff); }
        .project-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 1.5rem;
        }
        .project-item svg {
            margin-right: 1rem;
            flex-shrink: 0;
            color: #ff00ff;
            filter: drop-shadow(0 0 5px rgba(255, 0, 255, 0.5));
        }
        .project-item p {
            margin: 0;
            color: #d0d0d0;
        }
        .stats-image {
            max-width: 100%;
            height: auto;
            border-radius: 0.5rem;
            border: 1px solid #333;
            margin-bottom: 1rem;
        }
        .banner-img {
            width: 100%;
            max-height: 250px;
            object-fit: cover;
            border-radius: 1rem;
            border: 2px solid #00f7ff;
            box-shadow: 0 0 20px rgba(0, 247, 255, 0.3);
        }
        .skill-icons-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1.5rem;
        }
        .skill-icons-container img {
            transition: transform 0.3s ease, filter 0.3s ease;
        }
        .skill-icons-container img:hover {
            transform: scale(1.1);
            filter: drop-shadow(0 0 10px rgba(0, 247, 255, 0.7));
        }
        @media (min-width: 768px) {
            .stats-grid {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
                gap: 1.5rem;
            }
        }
    </style>
</head>
<body class="antialiased">
    <div class="container">

        <section class="text-center mb-12">
            <h1 class="text-5xl font-extrabold mb-2">
                <span style="color: #ff00ff;">Hey there 👾, I'm <strong>Dheeraj Patel</strong></span>
            </h1>
            <h3 class="text-2xl font-medium mb-6">
                <span style="color: #00f7ff;">Software Dev | Cyber Alchemist | Tech Trailblazer</span>
            </h3>
            <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=600&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Coding+the+Future.;Building+Secure+Web+Realms.;Innovating+with+AI+and+Blockchain." alt="Typing Animation" class="mx-auto max-w-full h-auto">
        </section>

        <hr class="border-t border-gray-800 my-12">

        <section class="card">
            <h2 class="section-heading">🌌 About Me</h2>
            <ul class="list-disc list-inside space-y-3 text-lg">
                <li>🚀 Crafting <strong class="text-cyan-400">scalable web applications</strong> and <strong class="text-cyan-400">secure systems</strong>.</li>
                <li>🔍 Exploring <strong class="text-pink-400">Blockchain</strong>, <strong class="text-pink-400">AI</strong>, and <strong class="text-pink-400">Secure Voting Systems</strong>.</li>
                <li>💾 Enthusiast of <strong class="text-purple-400">defense tech</strong> and <strong class="text-purple-400">generative AI</strong> innovations.</li>
                <li>📜 <a href="#" class="text-cyan-400 hover:underline">My Resume (Coming Soon)</a> | <a href="#" class="text-cyan-400 hover:underline">My Portfolio (Coming Soon)</a></li>
                <li>📧 Reach me at: <strong class="text-yellow-400">dheerajpatel.sde@gmail.com</strong></li>
            </ul>
        </section>

        <section class="card">
            <h2 class="section-heading">🛠 Tech Arsenal</h2>
            <div class="skill-icons-container">
                <img src="https://skillicons.dev/icons?i=java,js,html,css,python,c,cpp,react,mysql,mongodb,flask,bootstrap,git,vscode,jupyter,arduino,docker,linux" alt="My Tech Stack" class="w-full h-auto max-w-2xl">
            </div>
            <p class="text-center text-sm mt-4 text-gray-500"><em>(Mastering tools for modern development)</em></p>
        </section>

        <section class="card text-center">
            <h2 class="section-heading">🔗 Connect & Collaborate</h2>
            <div class="flex flex-wrap justify-center">
                <a href="https://www.linkedin.com/in/dheeraj-patel-dev/" target="_blank" rel="noopener noreferrer" class="link-button linkedin-btn">LinkedIn</a>
                <a href="https://github.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer" class="link-button github-btn">GitHub</a>
                <a href="https://leetcode.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer" class="link-button leetcode-btn">LeetCode</a>
                <a href="https://www.hackerrank.com/Dheerajpatel55" target="_blank" rel="noopener noreferrer" class="link-button hackerrank-btn">HackerRank</a>
            </div>
        </section>

        <section class="card">
            <h2 class="section-heading">📊 GitHub Metrics</h2>
            <div class="stats-grid">
                <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Dheerajpatel55&theme=monokai" alt="GitHub Profile Details" class="stats-image mx-auto">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dheerajpatel55&theme=dark" alt="GitHub Streak Stats" class="stats-image mx-auto">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dheerajpatel55&layout=compact&theme=monokai" alt="Top Languages" class="stats-image mx-auto">
            </div>
            <div class="text-center mt-8">
                <img src="https://github-profile-trophy.vercel.app/?username=Dheerajpatel55&theme=monokai&no-bg=true&margin-w=10" alt="GitHub Trophies" class="mx-auto max-w-full h-auto">
            </div>
        </section>

        <section class="card">
            <h2 class="section-heading">✨ Key Projects</h2>
            <ul class="space-y-4 text-lg">
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-2 4h4m-7-9h14a5 5 0 010 10H5a5 5 0 010-10z"></path></svg>
                    <p><strong class="text-pink-400">Blockchain Voting System:</strong> A secure, transparent voting platform leveraging blockchain for trust and immutability.</p>
                </li>
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"></path></svg>
                    <p><strong class="text-pink-400">BERT Healthcare Chatbot:</strong> An AI-powered chatbot using BERT for natural language processing in healthcare support.</p>
                </li>
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
                    <p><strong class="text-pink-400">Wearable Health App:</strong> A mobile app for real-time health monitoring with wearable device integration.</p>
                </li>
                <li class="project-item">
                    <svg class="w-6 h-6 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                    <p><strong class="text-pink-400">Resume & ATS Optimizer:</strong> A web app to optimize resumes for Applicant Tracking Systems.</p>
                </li>
            </ul>
        </section>

        <section class="text-center my-12">
            <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=monokai" alt="GitHub Quotes" class="mx-auto max-w-full h-auto">
        </section>

        <section class="text-center mt-12 mb-8">
            <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=600&size=24&pause=1000&color=FF00FF&center=true&width=450&lines=Open+to+Internships+&+Collabs!;Let's+Shape+the+Future!" alt="Call to Action" class="mx-auto max-w-full h-auto">
        </section>
    </div>
</body>
</html>
