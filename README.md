<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarun's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #e0e0e0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1f1f1f;
            color: #e0e0e0;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            width: 80%;
            margin: 2rem auto;
            padding-bottom: 4rem; /* Added space at the bottom */
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            background-color: #333;
            color: #fff;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border-radius: 8px;
        }
        .projects, .certifications, .skills {
            display: flex;
            flex-wrap: wrap;
        }
        .projects div, .certifications div, .skills div {
            flex: 1 1 calc(33% - 1rem);
            background-color: #1f1f1f;
            margin: 0.5rem;
            padding: 1rem;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        footer {
            background-color: #1f1f1f;
            color: #e0e0e0;
            text-align: center;
            padding: 0.5rem 0;
            font-size: 0.8rem;
        }
        a {
            color: #64ffda;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .contact-links a {
            color: #64ffda;
            margin: 0 0.5rem;
        }
        .contact-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tarun's Portfolio</h1>
        <p>📞 +91 87787 38627 | 📧 <a href="mailto:iamtarun2003@gmail.com">iamtarun2003@gmail.com</a> | 🌍 Salem</p>
        <p class="contact-links"><a href="https://www.linkedin.com">LinkedIn</a> | <a href="https://www.github.com">GitHub</a></p>
    </header>
    <div class="container">
        <div class="section">
            <h2>About Me</h2>
            <p>🎓 I am a Computer Science B.Tech student with strong cybersecurity and programming skills in Python, Java, and C++. Experienced in secure software development, network security, ethical hacking, and cryptography. Skilled in problem-solving, teamwork, and communication. Passionate about innovative solutions and enhancing cybersecurity, I am eager to contribute to dynamic projects and expand my technical expertise.</p>
        </div>
        <div class="section">
            <h2>Projects</h2>
            <div class="projects">
                <div>
                    <h3>🛡️ Malware Analysis Using Sandbox</h3>
                    <p>Developed a malware analysis project using a sandbox to examine malicious software.</p>
                    <p>Automated dynamic behavior analysis of malware to strengthen cybersecurity defenses.</p>
                    <a href="#">[CLICK HERE]</a>
                </div>
                <div>
                    <h3>🧠 Smart Tobacco Detection</h3>
                    <p>Created an AI system for real-time tobacco product detection, aiding in control efforts.</p>
                    <p>Implemented ML algorithms for accurate identification of tobacco products.</p>
                </div>
            </div>
        </div>
        <div class="section">
            <h2>Certifications</h2>
            <div class="certifications">
                <div>🏆 Foundation of Cyber Security - Google</div>
                <div>🏅 Cyber Security Job Analyst - TCS</div>
                <div>🥇 Getting Started with Threat Intelligence and Hunting - IBM</div>
                <div>🥈 Network Security - CISCO</div>
                <div>🥉 Enterprise Security - IBM</div>
                <div>🎖️ Penetration Testing, Incident Response, Forensics Science - IBM</div>
            </div>
        </div>
        <div class="section">
            <h2>Skills</h2>
            <div class="skills">
                <div>
                    <h3>Programming Skills</h3>
                    <p>HTML, CSS, PHP, SQL, Python, Java, DSA, C and C++</p>
                </div>
                <div>
                    <h3>Specialization Skills</h3>
                    <p>Digital Forensics, Ethical Hacking, Penetration Testing, Network Security, Threat Intelligence, Application Security, Vulnerability Assessment</p>
                </div>
                <div>
                    <h3>Communication Skills</h3>
                    <p>English, Tamil</p>
                </div>
                <div>
                    <h3>Interpersonal Skills</h3>
                    <p>Problem Solving, Leadership, Communicative, Team worker</p>
                </div>
            </div>
        </div>
        <div class="section">
            <h2>Work Experience</h2>
            <p><strong>Ethical Hacker - Intern</strong> at Edunexa | Dec 2023 - Jan 2024</p>
            <ul>
                <li>Conducted ethical hacking activities to identify and address security vulnerabilities within the organization's systems and networks.</li>
                <li>Collaborated with the cybersecurity team to develop strategies for improving network security posture.</li>
            </ul>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Tarun's Portfolio. All Rights Reserved.</p>
    </footer>
</body>
</html>
