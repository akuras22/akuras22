<h1 align="center">Hi 👋, I'm Jon</h1>
<h3 align="center">A passionate developer from Germany</h3>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> </p>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jon's Animated README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
            overflow-x: hidden;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 60px 40px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            position: relative;
            overflow: hidden;
        }

        .container::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(102, 126, 234, 0.1) 0%, transparent 70%);
            animation: rotate 20s linear infinite;
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        .content {
            position: relative;
            z-index: 1;
        }

        h1 {
            text-align: center;
            font-size: 3.5em;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 10px;
            animation: fadeInDown 1s ease;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .wave {
            animation: wave 2s ease-in-out infinite;
            display: inline-block;
            transform-origin: 70% 70%;
        }

        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            10%, 30% { transform: rotate(14deg); }
            20% { transform: rotate(-8deg); }
            40% { transform: rotate(-4deg); }
            50% { transform: rotate(10deg); }
        }

        h3 {
            text-align: center;
            color: #555;
            font-size: 1.5em;
            margin-bottom: 40px;
            animation: fadeIn 1.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .typing-container {
            text-align: center;
            margin-bottom: 50px;
        }

        .typing-text {
            display: inline-block;
            color: #764ba2;
            font-size: 1.3em;
            font-weight: 600;
            border-right: 3px solid #764ba2;
            padding-right: 5px;
            animation: typing 4s steps(40) infinite, blink 0.75s step-end infinite;
            overflow: hidden;
            white-space: nowrap;
        }

        @keyframes typing {
            0%, 100% { width: 0; }
            50% { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }

        .section-title {
            font-size: 2em;
            color: #333;
            margin-bottom: 30px;
            text-align: center;
            position: relative;
            animation: slideInLeft 1s ease;
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .section-title::after {
            content: '';
            display: block;
            width: 100px;
            height: 4px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            margin: 15px auto 0;
            border-radius: 2px;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            animation: fadeInUp 1s ease backwards;
        }

        .tech-item:nth-child(1) { animation-delay: 0.1s; }
        .tech-item:nth-child(2) { animation-delay: 0.2s; }
        .tech-item:nth-child(3) { animation-delay: 0.3s; }
        .tech-item:nth-child(4) { animation-delay: 0.4s; }
        .tech-item:nth-child(5) { animation-delay: 0.5s; }
        .tech-item:nth-child(6) { animation-delay: 0.6s; }
        .tech-item:nth-child(7) { animation-delay: 0.7s; }
        .tech-item:nth-child(8) { animation-delay: 0.8s; }
        .tech-item:nth-child(9) { animation-delay: 0.9s; }
        .tech-item:nth-child(10) { animation-delay: 1s; }
        .tech-item:nth-child(11) { animation-delay: 1.1s; }
        .tech-item:nth-child(12) { animation-delay: 1.2s; }
        .tech-item:nth-child(13) { animation-delay: 1.3s; }
        .tech-item:nth-child(14) { animation-delay: 1.4s; }
        .tech-item:nth-child(15) { animation-delay: 1.5s; }

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

        .tech-item:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 15px 30px rgba(102, 126, 234, 0.3);
        }

        .tech-item img {
            width: 50px;
            height: 50px;
            margin-bottom: 10px;
            filter: grayscale(50%);
            transition: filter 0.3s ease;
        }

        .tech-item:hover img {
            filter: grayscale(0%);
            animation: bounce 0.6s ease;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .tech-item span {
            font-size: 0.9em;
            color: #666;
            font-weight: 600;
            text-align: center;
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 50px;
        }

        .stat-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            color: white;
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.3);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.02); }
        }

        .stat-card h4 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .stat-card p {
            font-size: 1em;
            opacity: 0.9;
        }

        @media (max-width: 768px) {
            h1 { font-size: 2.5em; }
            h3 { font-size: 1.2em; }
            .container { padding: 40px 20px; }
            .tech-grid { grid-template-columns: repeat(auto-fit, minmax(80px, 1fr)); gap: 15px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="content">
            <h1>Hi <span class="wave">👋</span>, I'm Jon</h1>
            <h3>A passionate developer from Germany</h3>
            
            <div class="typing-container">
                <div class="typing-text">💻 Building amazing things with code...</div>
            </div>

            <div class="stats-container">
                <div class="stat-card">
                    <h4>15+</h4>
                    <p>Technologies</p>
                </div>
                <div class="stat-card">
                    <h4>∞</h4>
                    <p>Lines of Code</p>
                </div>
                <div class="stat-card">
                    <h4>🚀</h4>
                    <p>Always Learning</p>
                </div>
            </div>

            <h2 class="section-title">🛠️ Languages and Tools</h2>

            <div class="tech-grid">
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="Android">
                    <span>Android</span>
                </div>
                <div class="tech-item">
                    <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino">
                    <span>Arduino</span>
                </div>
                <div class="tech-item">
                    <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash">
                    <span>Bash</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3">
                    <span>CSS3</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker">
                    <span>Docker</span>
                </div>
                <div class="tech-item">
                    <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="Flask">
                    <span>Flask</span>
                </div>
                <div class="tech-item">
                    <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter">
                    <span>Flutter</span>
                </div>
                <div class="tech-item">
                    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git">
                    <span>Git</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5">
                    <span>HTML5</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux">
                    <span>Linux</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB">
                    <span>MongoDB</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL">
                    <span>MySQL</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx">
                    <span>Nginx</span>
                </div>
                <div class="tech-item">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
                    <span>Python</span>
                </div>
                <div class="tech-item">
                    <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="SQLite">
                    <span>SQLite</span>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
