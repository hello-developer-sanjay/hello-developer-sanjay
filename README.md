<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanjay Patidar's GitHub Profile</title>
    <style>
        body {
            font-family: 'Fira Code', monospace;
            background: linear-gradient(135deg, #1A1A1A, #0E75B6);
            color: #FFFFFF;
            margin: 0;
            padding: 20px;
            overflow-x: hidden;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .header, .section {
            background: linear-gradient(135deg, rgba(14, 117, 182, 0.8), rgba(26, 26, 26, 0.8));
            border-radius: 15px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 0 20px rgba(14, 117, 182, 0.7);
            animation: fadeIn 1s ease-in;
        }
        h1, h2, h3 {
            font-weight: bold;
            text-shadow: 0 0 10px #0E75B6, 0 0 20px #764ABC;
            color: #FFFFFF;
            margin: 10px 0;
        }
        h1 {
            font-size: 36px;
            background: linear-gradient(to right, #0E75B6, #764ABC);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-align: center;
        }
        h2 {
            font-size: 28px;
            border-bottom: 2px solid #0E75B6;
            padding-bottom: 10px;
        }
        p, li {
            font-size: 18px;
            line-height: 1.6;
            color: #E0E0E0;
            text-shadow: 0 0 5px rgba(255, 255, 255, 0.5);
        }
        .badge-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin: 10px 0;
        }
        .badge-container a img {
            transition: transform 0.3s, box-shadow 0.3s;
            border-radius: 8px;
        }
        .badge-container a img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 15px #0E75B6, 0 0 25px #764ABC;
        }
        .stats img {
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(14, 117, 182, 0.7);
            transition: transform 0.3s;
        }
        .stats img:hover {
            transform: scale(1.05);
        }
        .pulse {
            animation: pulse 2s infinite;
        }
        a {
            color: #61DAFB;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #764ABC;
            text-shadow: 0 0 10px #764ABC;
        }
        .project-card, .experience-card {
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            padding: 15px;
            margin: 10px 0;
            box-shadow: 0 0 10px rgba(14, 117, 182, 0.5);
            animation: slideIn 0.5s ease-in;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 10px 0;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 8px;
        }
        th, td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #0E75B6;
            color: #E0E0E0;
        }
        th {
            background: linear-gradient(to right, #0E75B6, #764ABC);
            color: #FFFFFF;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-20px); }
            to { opacity: 1; transform: translateX(0); }
        }
        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(14, 117, 182, 0.7); }
            70% { transform: scale(1.05); box-shadow: 0 0 0 10px rgba(14, 117, 182, 0); }
            100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(14, 117, 182, 0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header" style="text-align: center;">
            <img src="https://capsule-render.vercel.app/api?type=waving&color=0E75B6&height=120&section=header&text=Sanjay%20Patidar&fontSize=40&fontColor=FFFFFF&animation=fadeIn" alt="Header" style="width: 100%; border-radius: 10px;" />
            <h1>👨‍💻 Sanjay Patidar | Full-Stack Developer & Zedemy Founder</h1>
            <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=600&color=0E75B6&center=true&vCenter=true&width=800&lines=Full-Stack+Engineer+Crafting+Scalable+Web+Apps;Founder+of+Zedemy+Learning+Platform;Expert+in+React.js,+Node.js,+AWS;Driving+500K%2B+Impressions+Across+120%2B+Countries;Passionate+About+Innovative+Web+Development;Building+the+Future+of+Learning+with+Zedemy" alt="Typing SVG" style="margin: 20px 0;" />
            <div class="badge-container">
                <a href="https://sanjay-patidar.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0E75B6?style=for-the-badge&logo=vercel&logoColor=white&labelColor=000000" alt="Portfolio" /></a>
                <a href="https://linkedin.com/in/sanjay-patidar"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000" alt="LinkedIn" /></a>
                <a href="mailto:sanjaypatidar.engineer@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000" alt="Email" /></a>
                <img src="https://komarev.com/ghpvc/?username=hello-developer-sanjay&color=0e75b6&style=for-the-badge&label=Profile+Views&animation=grow" alt="Profile views" class="pulse" />
            </div>
        </div>

        <div class="section">
            <h2>🌟 About Me</h2>
            <p>I'm a <strong>Software Development Engineer</strong> and the <strong>Founder & Lead Developer</strong> at <a href="https://zedemy.vercel.app">Zedemy</a>, passionate about building scalable, user-centric web applications. With <strong>12+ full-stack solutions</strong> deployed, my work has generated <strong>500K+ impressions</strong> and <strong>$100K+ engagements</strong> across <strong>120+ countries</strong>. I specialize in <strong>React.js</strong>, <strong>Node.js</strong>, <strong>AWS serverless architectures</strong>, and <strong>Agile methodologies</strong>, delivering production-ready code for seamless growth.</p>
            <h3>Key Achievements</h3>
            <ul>
                <li>🥇 Secured <strong>#1 Google ranking</strong> for EduXcel via SEO and MongoDB optimization, driving <strong>89K+ impressions</strong> and <strong>9K+ clicks</strong> across 127 countries.</li>
                <li>📈 Improved <strong>20% search rankings</strong> for LIC DO website, boosting <strong>4.7K+ clicks</strong> with enhanced UX and content hierarchy.</li>
                <li>🚀 Founded <strong>Zedemy</strong>, a learning platform with serverless AWS backend, cutting costs by <strong>40%</strong> and automating certificate issuance.</li>
            </ul>
            <h3>Details</h3>
            <ul>
                <li>📍 <strong>Based in</strong>: Neemuch, India</li>
                <li>📚 <strong>Education</strong>: B.Tech in Computer Science, Chandigarh University (2020–2024)</li>
                <li>🏆 <strong>Certification</strong>: AWS Cloud Solutions Architect, Coursera (Feb 2024) <a href="https://coursera.org/verify/aws-cloud-solutions-architect">View</a></li>
            </ul>
        </div>

        <div class="section">
            <h2>🛠️ Tech Stack</h2>
            <p>Explore my expertise with animated, glowing badges in a dynamic carousel:</p>
            <h3>Frontend</h3>
            <div class="badge-container">
                <a href="https://developer.mozilla.org/en-US/docs/Web/HTML"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=000000&glow=true" alt="HTML5" /></a>
                <a href="https://developer.mozilla.org/en-US/docs/Web/CSS"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=000000&glow=true" alt="CSS3" /></a>
                <a href="Lambdafrom https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white&labelColor=000000&glow=true" alt="Tailwind CSS" /></a>
                <a href="https://javascript.info"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=000000&glow=true" alt="JavaScript" /></a>
                <a href="https://reactjs.org"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=000000&glow=true" alt="React" /></a>
                <a href="https://redux.js.org"><img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white&labelColor=000000&glow=true" alt="Redux" /></a>
                <a href="https://vitejs.dev"><img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white&labelColor=000000&glow=true" alt="Vite" /></a>
            </div>
            <h3>Backend</h3>
            <div class="badge-container">
                <a href="https://nodejs.org"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=000000&glow=true" alt="Node.js" /></a>
                <a href="https://expressjs.com"><img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white&labelColor=000000&glow=true" alt="Express.js" /></a>
                <a href="https://www.mongodb.com"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=000000&glow=true" alt="MongoDB" /></a>
                <a href="https://aws.amazon.com/dynamodb"><img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white&labelColor=000000&glow=true" alt="DynamoDB" /></a>
                <a href="https://redis.io"><img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white&labelColor=000000&glow=true" alt="Redis" /></a>
                <a href="https://socket.io"><img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white&labelColor=000000&glow=true" alt="Socket.io" /></a>
            </div>
            <h3>Cloud & DevOps</h3>
            <div class="badge-container">
                <a href="https://aws.amazon.com/lambda"><img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white&labelColor=000000&glow=true" alt="AWS Lambda" /></a>
                <a href="https://aws.amazon.com/s3"><img src="https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white&labelColor=000000&glow=true" alt="AWS S3" /></a>
                <a href="https://aws.amazon.com/cloudfront"><img src="https://img.shields.io/badge/CloudFront-D05C3B?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=000000&glow=true" alt="CloudFront" /></a>
                <a href="https://aws.amazon.com/api-gateway"><img src="https://img.shields.io/badge/API_Gateway-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=000000&glow=true" alt="API Gateway" /></a>
                <a href="https://git-scm.com"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=000000&glow=true" alt="Git" /></a>
                <a href="https://github.com/features/actions"><img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=000000&glow=true" alt="GitHub Actions" /></a>
            </div>
            <h3>Methodologies</h3>
            <div class="badge-container">
                <a href="https://agilemanifesto.org"><img src="https://img.shields.io/badge/Agile-009688?style=for-the-badge&logo=agile&logoColor=white&labelColor=000000&glow=true" alt="Agile" /></a>
                <a href="https://jestjs.io"><img src="https://img.shields.io/badge/Unit_Testing-323330?style=for-the-badge&logo=jest&logoColor=white&labelColor=000000&glow=true" alt="Unit Testing" /></a>
                <a href="https://en.wikipedia.org/wiki/Design_Patterns"><img src="https://img.shields.io/badge/Design_Patterns-6DB33F?style=for-the-badge&logo=pattern&logoColor=white&labelColor=000000&glow=true" alt="Design Patterns" /></a>
            </div>
        </div>

        <div class="section">
            <h2>🌟 Featured Projects</h2>
            <div class="project-card">
                <div style="font-family: 'Fira Code', monospace; text-align: center; padding: 20px; background: linear-gradient(135deg, #0E75B6, #1A1A1A); border-radius: 10px; box-shadow: 0 0 15px rgba(14, 117, 182, 0.7); color: #FFFFFF;">
                    <h3 style="font-weight: bold; font-size: 24px; margin: 10px 0; text-shadow: 0 0 10px #0E75B6;">
                        Zedemy | Learning Platform
                    </h3>
                    <p style="font-weight: bold; font-size: 18px; margin: 5px 0; text-shadow: 0 0 5px #0E75B6;">
                        Founder & Lead Developer | Jan 2024 – Oct 2024
                    </p>
                </div>
                <p><strong>Tech Stack</strong>: React.js, Redux, AWS Lambda, DynamoDB, S3, Tailwind CSS, GitHub Actions</p>
                <p><strong>Achievements</strong>:</p>
                <ul>
                    <li>⦿ Launched a platform for category-based posts, enabling collaborative learning and automated certificate issuance.</li>
                    <li>⦿ Reduced infrastructure costs by 40% with serverless AWS architecture.</li>
                    <li>⦿ Achieved 90%+ test coverage using Jest and Supertest for APIs.</li>
                </ul>
                <p><strong>Links</strong>: <a href="https://zedemy.vercel.app">Live</a> | <a href="https://github.com/hello-developer-sanjay/Zedemy">GitHub</a></p>
                <p><strong>Stats</strong>: <img src="https://img.shields.io/github/stars/hello-developer-sanjay/Zedemy?style=social&labelColor=000000&glow=true" /> <img src="https://img.shields.io/github/forks/hello-developer-sanjay/Zedemy?style=social&labelColor=000000&glow=true" /></p>
            </div>
            <div class="project-card">
                <h3>EventPoa | Event Management System</h3>
                <p><strong>Lead Full Stack Developer</strong> | Jan 2024 – Oct 2024</p>
                <p><strong>Tech Stack</strong>: MERN Stack, Google Calendar API, Context API, RESTful APIs</p>
                <p><strong>Achievements</strong>:</p>
                <ul>
                    <li>⦿ Built a dashboard with Redux and Google Calendar API for schedule management.</li>
                    <li>⦿ Reduced page load latency by 25% with async data fetching.</li>
                    <li>⦿ Streamlined Agile collaboration across 3 teams, speeding decisions by 40%.</li>
                </ul>
                <p><strong>Links</strong>: <a href="https://eventpro.vercel.app">Live</a> | <a href="https://github.com/hello-developer-sanjay/EventPro-Frontend">GitHub</a></p>
                <p><strong>Stats</strong>: <img src="https://img.shields.io/github/stars/hello-developer-sanjay/EventPro-Frontend?style=social&labelColor=000000&glow=true" /> <img src="https://img.shields.io/github/forks/hello-developer-sanjay/EventPro-Frontend?style=social&labelColor=000000&glow=true" /></p>
            </div>
            <div class="project-card">
                <h3>ConnectNow | Video Chat App</h3>
                <p><strong>Lead Full Stack Developer</strong> | Jan 2024 – Oct 2024</p>
                <p><strong>Tech Stack</strong>: WebRTC, React.js, Node.js, MongoDB, Socket.io</p>
                <p><strong>Achievements</strong>:</p>
                <ul>
                    <li>⦿ Delivered peer-to-peer video calls with WebRTC and custom signaling logic.</li>
                    <li>⦿ Reduced call drops by 35% under unreliable networks.</li>
                    <li>⦿ Secured API requests with Node.js proxy middleware, resolving CORS issues.</li>
                </ul>
                <p><strong>Links</strong>: <a href="https://connectnow.vercel.app">Live</a> | <a href="https://github.com/hello-developer-sanjay/ConnectNow-frontend">GitHub</a></p>
                <p><strong>Stats</strong>: <img src="https://img.shields.io/github/stars/hello-developer-sanjay/ConnectNow-frontend?style=social&labelColor=000000&glow=true" /> <img src="https://img.shields.io/github/forks/hello-developer-sanjay/ConnectNow-frontend?style=social&labelColor=000000&glow=true" /></p>
            </div>
            <p><strong>Explore More</strong>: <a href="https://sanjay-patidar.vercel.app">sanjay-patidar.vercel.app</a></p>
        </div>

        <div class="section">
            <h2>💼 Work Experience</h2>
            <div class="experience-card">
                <h3>SmartServe DO | Freelance Frontend Developer</h3>
                <p><strong>Nov 2024 – Feb 2025</strong></p>
                <p><strong>Tech Stack</strong>: React.js, Gemini API, Tailwind CSS, Vite</p>
                <p><strong>Achievements</strong>:</p>
                <ul>
                    <li>⦿ Developed a multilingual AI chatbot for LIC officers, increasing session duration by 30%.</li>
                    <li>⦿ Reduced initial load time by 40% using Vite and lazy loading.</li>
                </ul>
                <p><strong>Link</strong>: <a href="https://smartservedo.vercel.app">Live</a></p>
            </div>
        </div>

        <div class="section">
            <h2>📊 GitHub Stats & Contributions</h2>
            <div class="stats">
                <img src="https://github-readme-stats.vercel.app/api?username=hello-developer-sanjay&show_icons=true&theme=radical&count_private=true&border_color=0E75B6&border_radius=10" alt="GitHub Stats" width="400" />
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=hello-developer-sanjay&theme=radical&border=0E75B6&border_radius=10" alt="GitHub Streak" width="400" />
                <img src="https://github-readme-stats.vercel.app/api/top-langs?username=hello-developer-sanjay&show_icons=true&locale=en&layout=compact&theme=radical&border_color=0E75B6&border_radius=10" alt="Top Languages" width="400" />
                <img src="https://github-profile-trophy.vercel.app/?username=hello-developer-sanjay&theme=radical&no-frame=true&margin-w=10&border_color=0E75B6" alt="GitHub Trophies" />
            </div>
        </div>

        <div class="section">
            <h2>🏆 Certifications & Badges</h2>
            <table>
                <tr>
                    <th>Certification</th>
                    <th>Issuer</th>
                    <th>Date</th>
                    <th>Link</th>
                </tr>
                <tr>
                    <td>AWS Cloud Solutions Architect</td>
                    <td>Coursera</td>
                    <td>Feb 2024</td>
                    <td><a href="https://coursera.org/verify/aws-cloud-solutions-architect">View</a></td>
                </tr>
            </table>
            <div class="badge-container">
                <img src="https://img.shields.io/badge/React.js-Expert-61DAFB?logo=react&style=for-the-badge&labelColor=000000&glow=true" alt="React.js" />
                <img src="https://img.shields.io/badge/Node.js-Advanced-339933?logo=nodedotjs&style=for-the-badge&labelColor=000000&glow=true" alt="Node.js" />
                <img src="https://img.shields.io/badge/AWS-Certified-FF9900?logo=amazonaws&style=for-the-badge&labelColor=000000&glow=true" alt="AWS" />
                <img src="https://img.shields.io/badge/MERN_Stack-Proficient-000000?logo=javascript&style=for-the-badge&labelColor=000000&glow=true" alt="MERN Stack" />
            </div>
        </div>

        <div class="section">
            <h2>📝 Blogs & Articles</h2>
            <p>I share cutting-edge insights on web development and cloud technologies:</p>
            <ul>
                <li><strong>Topics</strong>: React.js optimizations, AWS serverless patterns, Node.js performance, SEO strategies</li>
                <li><strong>Recent Post</strong>: "What’s New in VS Code (Visual Studio Code) v1.99 – March 2025 Highlights"</li>
                <li>👉 <a href="https://zedemy.vercel.app/explore">Read my blogs</a></li>
            </ul>
        </div>

        <div class="section">
            <h2>💬 Let’s Connect!</h2>
            <p>I’m excited to collaborate and share my expertise in building innovative solutions. Reach out to discuss:</p>
            <ul>
                <li>🛠️ <strong>React.js</strong>: Creating dynamic, high-performance UIs with custom hooks, Redux, or Vite.</li>
                <li>⚙️ <strong>Node.js</strong>: Developing scalable APIs, real-time apps with Socket.io, or event-driven systems.</li>
                <li>☁️ <strong>AWS</strong>: Architecting serverless solutions, optimizing costs, or automating CI/CD pipelines.</li>
                <li>🚀 <strong>Zedemy</strong>: Transforming education with collaborative learning and automated certifications.</li>
                <li>💡 <strong>Open Source</strong>: Contributing to projects or launching new initiatives to drive impact.</li>
            </ul>
            <p>
                📧 <strong>Email</strong>: <a href="mailto:sanjaypatidar.engineer@gmail.com">sanjaypatidar.engineer@gmail.com</a><br>
                📄 <strong>Resume</strong>: <a href="https://sanjay-patidar.vercel.app/resume">sanjay-patidar.vercel.app/resume</a><br>
                🌐 <strong>Portfolio</strong>: <a href="https://sanjay-patidar.vercel.app">sanjay-patidar.vercel.app</a>
            </p>
        </div>

        <div class="section" style="text-align: center;">
            <a href="https://github.com/hello-developer-sanjay"><img src="https://img.shields.io/github/followers/hello-developer-sanjay?label=Follow&style=social&labelColor=000000&glow=true" alt="Follow" class="pulse" /></a>
            <img src="https://capsule-render.vercel.app/api?type=waving&color=0E75B6&height=120&section=footer&animation=fadeIn" alt="Footer" style="width: 100%; border-radius: 10px; margin-top: 20px;" />
        </div>
    </div>
</body>
</html>
