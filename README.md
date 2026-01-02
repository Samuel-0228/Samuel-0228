<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samuel Y. - Profile</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .profile-container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            padding: 40px;
            max-width: 600px;
            width: 100%;
            text-align: center;
            animation: fadeInUp 1s ease-out;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Header */
        h1 {
            font-size: 3em;
            font-weight: bold;
            color: #4a5568;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .divider {
            width: 100px;
            height: 4px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            margin: 0 auto 30px;
            border-radius: 2px;
        }

        /* Intro Section */
        .intro {
            margin-bottom: 40px;
            padding: 20px;
            background: rgba(102, 126, 234, 0.1);
            border-radius: 15px;
            border-left: 5px solid #667eea;
        }

        .intro p {
            font-size: 1.1em;
            margin-bottom: 15px;
        }

        .intro strong {
            color: #4a5568;
        }

        /* Reach Out Section */
        .reach-out {
            margin-bottom: 30px;
        }

        .reach-out h2 {
            font-size: 1.5em;
            color: #4a5568;
            margin-bottom: 15px;
        }

        /* Footer */
        .footer {
            font-size: 0.9em;
            color: #718096;
            border-top: 1px solid rgba(102, 126, 234, 0.2);
            padding-top: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .profile-container {
                padding: 30px 20px;
            }

            h1 {
                font-size: 2.5em;
            }
        }

        /* GitHub Streaks Placeholder - Embed actual GitHub contribution graph if needed */
        /* For streaks to work, replace with: <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical" alt="Samuel Y. GitHub Stats" /> */
        /* Or use GitHub's contribution graph: <img src="https://ghchart.rshah.org/YOUR_USERNAME" /> */
        .streaks-placeholder {
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            font-style: italic;
            color: #718096;
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <header>
            <h1># Samuel Y.</h1>
            <div class="divider"></div>
        </header>

        <section class="intro">
            <h2>Quick Intro</h2>
            <p>Hey! I'm <strong>Samuel Y.</strong>, a passionate tech student majoring in <strong>Information Systems</strong> at <strong>Addis Ababa University</strong> (Class of 2024). I'm all about exploring code, data, and systems that make life easier – one line at a time. Let's connect and build something cool! 🚀</p>
        </section>

        <section class="reach-out">
            <h2>📫 Reach Out</h2>
            <!-- Add your contact links here without new content, e.g., <a href="mailto:samuel@example.com">Email</a> -->
        </section>

        <footer class="footer">
            <p>Made with ❤️ | © 2025 Samuel Y.</p>
        </footer>

        <!-- Streaks Section - This will work if you replace with actual GitHub embed -->
        <div class="streaks-placeholder">
            <!-- Embed your GitHub contribution streaks here for dynamic functionality -->
            <!-- Example: <script src="https://github-readme-stats.vercel.app/api?username=samuelY&show_icons=true"></script> -->
            <p>Contribution streaks and other dynamic elements go here – fully functional with GitHub integration!</p>
        </div>
    </div>
</body>
</html>
