<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:00f5ff,100:22c55e&height=220&section=header&text=Tharindi%20Weerasinghe&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Cybersecurity%20Undergraduate%20%7C%20AI%20Security%20%7C%20Network%20Security&descAlignY=58&descSize=16" />

</div>

```bash
┌──(tharindi㉿cybersec)-[~/profile]
└─$ whoami
Cybersecurity Undergraduate | Security Project Builder | AI + Network Security Learner

> about_me

I am a cybersecurity undergraduate from Sri Lanka, building practical projects in network security, privacy protection, fraud detection, AI-powered security tools, and secure web applications.

I use GitHub to document my learning journey, improve my technical skills, and build a portfolio for future cybersecurity internship opportunities.


> current_focus
[+] Network Security
[+] Packet Analysis
[+] Python Security Tools
[+] AI-Powered Cybersecurity
[+] Secure Web Applications
[+] Machine Learning for Fraud Detection

so this is my giit hub reporitory so we cnt get those packet sniffer, prot scanner things like to project right? cuz there are no website in there or am i wong? or we can get them as just lab?

You’re a little wrong, but in a good way. A GitHub project does not need a website to count as a project.

Cybersecurity tools are often:

Repository	Can it be a project?	Best label
ai-resume-security-analyzer	Yes	Full project/web app
Credit-Card-Fraud-Detection	Yes	Full project/web app
NexMeet-Event-Ticket-Booking	Yes	Full project/web app
Packet-Sniffer	Yes	Cybersecurity lab/project
Network-Scanner	Yes	Cybersecurity lab/project
port-scanner	Yes, but simple	Mini project/lab
password-strength-checker	Yes, but simple	Mini project/lab

For things like packet sniffer, network scanner, port scanner, they usually run in terminal/Kali/Linux. They don’t need a website because they are security tools, not normal user apps.

But to make them look professional, add:

A good README.md
Screenshots of terminal output
Features list
Tools used: Python, Scapy, sockets, Kali Linux
Ethical note: “For educational use and authorized networks only”

Example command:

sudo python3 packet_sniffer.py
Example output screenshot

So yes, you can absolutely keep them as cybersecurity lab projects on GitHub. For LinkedIn/portfolio, I would show your strongest projects like this:

Featured Projects

AI Resume Security Analyzer
Credit Card Fraud Detection Dashboard
Packet Sniffer & Traffic Analyzer
Network Scanner

Mini Labs

Port Scanner
Password Strength Checker

The only thing I’d improve is the older simple repos. Add better README files and screenshots, then they will look much more serious. These projects are actually good for a cybersecurity undergraduate because they show practical hands-on skills, not just theory.

but i dont have any portfolio website ... like beautiful tech cyber theme website i dont have one hiw to amke real website i mean protfolio site for me

Yes, you can absolutely make a real portfolio website. And honestly, for you, this is a very good next step because you already have GitHub projects. Now you need one beautiful place to show them properly.

Your portfolio website can be like your “cybersecurity profile page”:

Example sections:

Home
Your name, title, short intro:
“Cybersecurity Undergraduate | Python | Network Security | AI Security Projects”
About Me
Short paragraph about you, your degree, skills, and career goal.
Skills
Python, Flask, MySQL, Java, Linux, Kali Linux, Networking, Machine Learning, Git/GitHub.
Projects
Show your best projects with screenshots and GitHub buttons:
AI Resume Security Analyzer
Credit Card Fraud Detection
Packet Sniffer
Network Scanner
Event Ticket Booking
Password Strength Checker
Certifications
Cisco Introduction to Cybersecurity, and any future certificates.
Contact
GitHub, LinkedIn, email.

Best way for you: build a static portfolio website using:

HTML + CSS + JavaScript

Then host it free using:

GitHub Pages

No backend needed. No database needed. It will still be a real website.

Your website link can look like:

https://yourgithubusername.github.io

or:

https://yourgithubusername.github.io/portfolio

For the design, I recommend a dark cyber theme:

Black / navy background
Neon blue or green highlights
Clean project cards
Small animations
Professional but not too childish

You can create a new GitHub repo called:

portfolio

Inside it:

portfolio/
├── index.html
├── style.css
├── script.js
├── images/
│   ├── ai-resume.png
│   ├── fraud-dashboard.png
│   ├── packet-sniffer.png
│   └── network-scanner.png
└── README.md

Then in GitHub:

Open the portfolio repository.
Go to Settings.
Go to Pages.
Under Source, choose Deploy from a branch.
Select main.
Select /root.
Click Save.
Wait 1–3 minutes.
GitHub will give your live website link.

Your portfolio website is where recruiters can understand you quickly. GitHub shows code, but your portfolio tells the story: who you are, what you built, what skills you used, and why those projects matter.

I can make the full cyber-themed portfolio code for you next: index.html, style.css, and script.js, with your current projects already added.

yes lets make , step bys tep tell me how to do
Worked for 29s

Yes, let’s make it. We’ll build a real cyber-themed portfolio website and publish it free using GitHub Pages. GitHub Pages supports static websites, and GitHub looks for an index.html file as the main page.

Step 1: Create A New Portfolio Folder
Open File Explorer and go to:

C:\Users\Malee\OneDrive\Desktop\CyberProjects

Create a new folder called:

portfolio

So it becomes:

CyberProjects/portfolio

Step 2: Open It In VS Code
Right-click the portfolio folder and choose:

Open with Code

Or open VS Code, then:

File > Open Folder > portfolio

Step 3: Create These Files
Inside VS Code, create:

portfolio/
├── index.html
├── style.css
├── script.js
└── images/

To create the images folder: right-click in VS Code Explorer → New Folder → name it images.

Step 4: What We Will Put Inside
Your website will have:

Home
About Me
Skills
Projects
Certifications
Contact

Your project cards will include:

AI Resume Security Analyzer
Credit Card Fraud Detection
NexMeet Event Ticket Booking
Packet Sniffer
Network Scanner
Port Scanner
Password Strength Checker

Step 5: After Website Is Ready
We will push it to GitHub:

git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin YOUR_REPOSITORY_LINK
git push -u origin main

Then in GitHub:

Repository > Settings > Pages > Source: Deploy from a branch > main > /root > Save

After a few minutes, your website will be live.

Now do only Step 1 to Step 3 first. Create the folder and the three files. Then tell me done, and I’ll give you the full beautiful cyber portfolio code for index.html, style.css, and script.js.

ok done i create those file what next

Perfect. Next we add the actual website code.

Open each file in VS Code and put the matching code inside.

1. index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maleesha Tharindi | Cybersecurity Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <nav class="navbar">
      <h2 class="logo">Maleesha<span>.</span></h2>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <section class="hero">
      <div class="hero-content">
        <p class="tag">Cybersecurity Undergraduate</p>
        <h1>Hi, I'm <span>Maleesha Tharindi</span></h1>
        <p class="hero-text">
          I build cybersecurity, AI, and web-based projects focused on network security,
          privacy, fraud detection, and practical security analysis.
        </p>
        <div class="hero-buttons">
          <a href="#projects" class="btn primary">View Projects</a>
          <a href="#contact" class="btn secondary">Contact Me</a>
        </div>
      </div>

      <div class="hero-card">
        <p class="terminal-line">$ whoami</p>
        <p>Cybersecurity Student</p>
        <p>Python | Flask | Linux | Networking</p>
        <p>AI Security | Threat Analysis</p>
      </div>
    </section>
  </header>

  <main>
    <section id="about" class="section">
      <h2>About Me</h2>
      <p>
        I am a cybersecurity undergraduate from Sri Lanka with hands-on experience in
        Python, Flask, Linux, network scanning, packet analysis, machine learning, and
        secure web application development. I enjoy building practical projects that
        connect cybersecurity theory with real-world tools.
      </p>
    </section>

    <section id="skills" class="section">
      <h2>Technical Skills</h2>
      <div class="skills-grid">
        <span>Python</span>
        <span>Flask</span>
        <span>Java</span>
        <span>MySQL</span>
        <span>Linux</span>
        <span>Kali Linux</span>
        <span>Networking</span>
        <span>Git & GitHub</span>
        <span>Machine Learning</span>
        <span>Cybersecurity</span>
      </div>
    </section>

    <section id="projects" class="section">
      <h2>Featured Projects</h2>

      <div class="projects-grid">
        <div class="project-card">
          <h3>AI Resume Security Analyzer</h3>
          <p>
            A Flask-based tool that analyzes resumes for privacy risks, PII exposure,
            suspicious URLs, and security recommendations.
          </p>
          <div class="tech">Python • Flask • Security Analysis</div>
          <a href="https://github.com/Tharindi-Weerasinghe/ai-resume-security-analyzer" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Credit Card Fraud Detection</h3>
          <p>
            A machine learning dashboard for detecting fraudulent transactions using
            trained models and visual analytics.
          </p>
          <div class="tech">Python • Flask • Machine Learning</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Credit-Card-Fraud-Detection" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>NexMeet Event Ticket Booking</h3>
          <p>
            A web-based event ticket booking system with event browsing, booking forms,
            and database connectivity.
          </p>
          <div class="tech">Spring Boot • MySQL • HTML/CSS</div>
          <a href="https://github.com/Tharindi-Weerasinghe/NexMeet-Event-Ticket-Booking" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Packet Sniffer</h3>
          <p>
            A cybersecurity lab project that captures and analyzes network packets to
            understand traffic behavior and protocols.
          </p>
          <div class="tech">Python • Scapy • Network Security</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Packet-Sniffer" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Network Scanner</h3>
          <p>
            A Python-based scanner for discovering devices and open ports on authorized
            networks.
          </p>
          <div class="tech">Python • Networking • Kali Linux</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Network-Scanner" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Password Strength Checker</h3>
          <p>
            A simple security tool that checks password strength and gives improvement
            suggestions.
          </p>
          <div class="tech">Python • Security Basics</div>
          <a href="https://github.com/Tharindi-Weerasinghe/password-strength-checker" target="_blank">View on GitHub</a>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>Certifications</h2>
      <div class="cert-card">
        <h3>Cisco Introduction to Cybersecurity</h3>
        <p>Completed foundational cybersecurity training covering threats, attacks, and security basics.</p>
      </div>
    </section>

    <section id="contact" class="section contact">
      <h2>Contact</h2>
      <p>Let's connect and collaborate on cybersecurity, AI, and software projects.</p>

      <div class="contact-links">
        <a href="https://github.com/Tharindi-Weerasinghe" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        <a href="mailto:your-email@example.com">Email</a>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2026 Maleesha Tharindi. Built with HTML, CSS, and JavaScript.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

2. style.css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #050814;
  color: #e8f1ff;
  line-height: 1.6;
}

.header {
  min-height: 100vh;
  background:
    radial-gradient(circle at top right, rgba(0, 255, 170, 0.15), transparent 35%),
    radial-gradient(circle at bottom left, rgba(0, 119, 255, 0.18), transparent 35%),
    #050814;
}

.navbar {
  width: 90%;
  max-width: 1150px;
  margin: auto;
  padding: 24px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 26px;
  color: #ffffff;
}

.logo span {
  color: #00f5c8;
}

.nav-links a {
  color: #b8c7dd;
  text-decoration: none;
  margin-left: 22px;
  font-size: 15px;
}

.nav-links a:hover {
  color: #00f5c8;
}

.hero {
  width: 90%;
  max-width: 1150px;
  margin: auto;
  min-height: calc(100vh - 90px);
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 40px;
  align-items: center;
}

.tag {
  color: #00f5c8;
  letter-spacing: 2px;
  text-transform: uppercase;
  font-size: 14px;
  margin-bottom: 12px;
}

.hero h1 {
  font-size: 54px;
  line-height: 1.1;
  margin-bottom: 20px;
}

.hero h1 span {
  color: #00f5c8;
}

.hero-text {
  max-width: 620px;
  color: #b8c7dd;
  font-size: 18px;
  margin-bottom: 28px;
}

.hero-buttons {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
}

.btn {
  text-decoration: none;
  padding: 12px 20px;
  border-radius: 6px;
  font-weight: bold;
}

.primary {
  background: #00f5c8;
  color: #031018;
}

.secondary {
  border: 1px solid #00f5c8;
  color: #00f5c8;
}

.hero-card {
  border: 1px solid rgba(0, 245, 200, 0.35);
  background: rgba(8, 18, 35, 0.85);
  padding: 28px;
  border-radius: 8px;
  box-shadow: 0 0 35px rgba(0, 245, 200, 0.12);
}

.hero-card p {
  margin-bottom: 12px;
  color: #cfe7ff;
}

.terminal-line {
  color: #00f5c8;
  font-family: Consolas, monospace;
}

.section {
  width: 90%;
  max-width: 1150px;
  margin: auto;
  padding: 80px 0;
}

.section h2 {
  font-size: 32px;
  margin-bottom: 24px;
  color: #ffffff;
}

.section > p {
  color: #b8c7dd;
  max-width: 850px;
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.skills-grid span {
  border: 1px solid rgba(0, 245, 200, 0.3);
  background: #081223;
  color: #d9f8ff;
  padding: 10px 14px;
  border-radius: 6px;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}

.project-card,
.cert-card {
  background: #081223;
  border: 1px solid rgba(0, 119, 255, 0.25);
  border-radius: 8px;
  padding: 22px;
  transition: transform 0.25s ease, border 0.25s ease;
}

.project-card:hover {
  transform: translateY(-6px);
  border-color: #00f5c8;
}

.project-card h3,
.cert-card h3 {
  color: #ffffff;
  margin-bottom: 12px;
}

.project-card p,
.cert-card p {
  color: #b8c7dd;
  margin-bottom: 14px;
}

.tech {
  color: #00f5c8;
  font-size: 14px;
  margin-bottom: 16px;
}

.project-card a,
.contact-links a {
  color: #00f5c8;
  text-decoration: none;
  font-weight: bold;
}

.contact-links {
  display: flex;
  gap: 18px;
  flex-wrap: wrap;
  margin-top: 20px;
}

footer {
  text-align: center;
  padding: 24px;
  color: #8796aa;
  border-top: 1px solid rgba(255, 255, 255, 0.08);
}

@media (max-width: 900px) {
  .hero {
    grid-template-columns: 1fr;
    padding: 50px 0;
  }

  .hero h1 {
    font-size: 40px;
  }

  .projects-grid {
    grid-template-columns: 1fr;
  }

  .navbar {
    flex-direction: column;
    gap: 18px;
  }

  .nav-links a {
    margin: 0 8px;
  }
}

3. script.js

const cards = document.querySelectorAll(".project-card");

cards.forEach((card) => {
  card.addEventListener("mousemove", (event) => {
    const rect = card.getBoundingClientRect();
    const x = event.clientX - rect.left;
    const y = event.clientY - rect.top;

    card.style.background = `radial-gradient(circle at ${x}px ${y}px, rgba(0, 245, 200, 0.12), #081223 38%)`;
  });

  card.addEventListener("mouseleave", () => {
    card.style.background = "#081223";
  });
});

After that, open index.html in your browser. You can double-click it from the folder.

Important: in index.html, replace these later:

<a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
<a href="mailto:your-email@example.com">Email</a>

Use your real LinkedIn and email. For now it is okay.

Next step after you check the website: tell me “it opened” or send me a screenshot, and then we’ll push it to GitHub and make it live.

ok so i little bit change the things can we more improve like beautiful cyber just find everywhere the new themes in the internet now we hav elotn of themes and replace this with them <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tharindi Weerasinghe | Cybersecurity Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="header">
    <nav class="navbar">
      <h2 class="logo">Tharindi<span>.</span></h2>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <section class="hero">
      <div class="hero-content">
        <p class="tag">Cybersecurity Undergraduate</p>
        <h1>Hi, I'm <span>Tharindi Weerasinghe</span></h1>
        <p class="hero-text">
          I build cybersecurity, AI, and web-based projects focused on network security,
          privacy, fraud detection, and practical security analysis.
        </p>
        <div class="hero-buttons">
          <a href="#projects" class="btn primary">View Projects</a>
          <a href="#contact" class="btn secondary">Contact Me</a>
        </div>
      </div>

      <div class="hero-card">
        <p class="terminal-line">$ whoami</p>
        <p>Cybersecurity Student</p>
        <p>Python | Flask | Linux | Networking</p>
        <p>AI Security | Threat Analysis</p>
      </div>
    </section>
  </header>

  <main>
    <section id="about" class="section">
      <h2>About Me</h2>
      <p>
        I am a cybersecurity undergraduate from Sri Lanka with hands-on experience in
        Python, Flask, Linux, network scanning, packet analysis, machine learning, and
        secure web application development. I enjoy building practical projects that
        connect cybersecurity theory with real-world tools.
      </p>
    </section>

    <section id="skills" class="section">
      <h2>Technical Skills</h2>
      <div class="skills-grid">
        <span>Python</span>
        <span>Flask</span>
        <span>Java</span>
        <span>MySQL</span>
        <span>Linux</span>
        <span>Kali Linux</span>
        <span>Networking</span>
        <span>Git & GitHub</span>
        <span>Machine Learning</span>
        <span>Cybersecurity</span>
      </div>
    </section>

    <section id="projects" class="section">
      <h2>Featured Projects</h2>

      <div class="projects-grid">
        <div class="project-card">
          <h3>AI Resume Security Analyzer</h3>
          <p>
            A Flask-based tool that analyzes resumes for privacy risks, PII exposure,
            suspicious URLs, and security recommendations.
          </p>
          <div class="tech">Python • Flask • Security Analysis</div>
          <a href="https://github.com/Tharindi-Weerasinghe/ai-resume-security-analyzer" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Credit Card Fraud Detection</h3>
          <p>
            A machine learning dashboard for detecting fraudulent transactions using
            trained models and visual analytics.
          </p>
          <div class="tech">Python • Flask • Machine Learning</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Credit-Card-Fraud-Detection" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>NexMeet Event Ticket Booking</h3>
          <p>
            A web-based event ticket booking system with event browsing, booking forms,
            and database connectivity.
          </p>
          <div class="tech">Spring Boot • MySQL • HTML/CSS</div>
          <a href="https://github.com/Tharindi-Weerasinghe/NexMeet-Event-Ticket-Booking" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Packet Sniffer</h3>
          <p>
            A cybersecurity lab project that captures and analyzes network packets to
            understand traffic behavior and protocols.
          </p>
          <div class="tech">Python • Scapy • Network Security</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Packet-Sniffer" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Network Scanner</h3>
          <p>
            A Python-based scanner for discovering devices and open ports on authorized
            networks.
          </p>
          <div class="tech">Python • Networking • Kali Linux</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Network-Scanner" target="_blank">View on GitHub</a>
        </div>

        <div class="project-card">
          <h3>Password Strength Checker</h3>
          <p>
            A simple security tool that checks password strength and gives improvement
            suggestions.
          </p>
          <div class="tech">Python • Security Basics</div>
          <a href="https://github.com/Tharindi-Weerasinghe/password-strength-checker" target="_blank">View on GitHub</a>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>Certifications</h2>
      <div class="cert-card">
        <h3>Cisco Introduction to Cybersecurity</h3>
        <p>Completed foundational cybersecurity training covering threats, attacks, and security basics.</p>
      </div>
    </section>

    <section id="contact" class="section contact">
      <h2>Contact</h2>
      <p>Let's connect and collaborate on cybersecurity, AI, and software projects.</p>

      <div class="contact-links">
        <a href="https://github.com/Tharindi-Weerasinghe" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        <a href="mailto:tharindimaleesha0@gmail.com">Email</a>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2026 Tharindi Weerasinghe. Built with HTML, CSS, and JavaScript.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
Worked for 26s

Yes. We can improve it a lot. I checked current portfolio/UI style ideas: modern sites are using dark mode, bento grids, glassmorphism, bold typography, and small animations. For cyber portfolios, terminal panels and neon dashboard-style cards also look good.

We’ll make an original design, not copy a template.

Do this now:

Replace your full index.html with this.
Then tell me done.
After that I’ll give you the matching style.css and script.js.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tharindi Weerasinghe | Cybersecurity Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <canvas id="cyber-canvas"></canvas>

  <header class="site-header">
    <nav class="navbar">
      <a href="#" class="logo">TW<span>_</span></a>

      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <section class="hero">
      <div class="hero-content">
        <div class="status-pill">
          <span class="pulse"></span>
          Available for internship opportunities
        </div>

        <p class="eyebrow">Cybersecurity Undergraduate</p>

        <h1>
          Hi, I'm <span>Tharindi Weerasinghe</span>
        </h1>

        <p class="hero-text">
          I build cybersecurity, AI, and software projects focused on network security,
          privacy protection, fraud detection, and practical threat analysis.
        </p>

        <div class="hero-actions">
          <a href="#projects" class="btn btn-primary">Explore Projects</a>
          <a href="#contact" class="btn btn-outline">Contact Me</a>
        </div>

        <div class="quick-stats">
          <div>
            <strong>7+</strong>
            <span>Projects</span>
          </div>
          <div>
            <strong>Cyber</strong>
            <span>Specialization</span>
          </div>
          <div>
            <strong>AI + Security</strong>
            <span>Focus Area</span>
          </div>
        </div>
      </div>

      <div class="hero-terminal">
        <div class="terminal-top">
          <span></span>
          <span></span>
          <span></span>
        </div>

        <div class="terminal-body">
          <p><span>$</span> whoami</p>
          <p class="output">Tharindi Weerasinghe</p>

          <p><span>$</span> cat focus.txt</p>
          <p class="output">Cybersecurity • Python • Linux • AI Security</p>

          <p><span>$</span> scan --skills</p>
          <ul>
            <li>Network Security</li>
            <li>Packet Analysis</li>
            <li>Fraud Detection</li>
            <li>Secure Web Apps</li>
          </ul>
        </div>
      </div>
    </section>
  </header>

  <main>
    <section id="about" class="section about-grid">
      <div>
        <p class="section-label">About Me</p>
        <h2>Building practical security skills through real projects.</h2>
      </div>

      <div class="glass-card">
        <p>
          I am a cybersecurity undergraduate from Sri Lanka with hands-on experience in
          Python, Flask, Linux, network scanning, packet analysis, machine learning,
          and secure web application development.
        </p>
        <p>
          My goal is to grow into a skilled cybersecurity professional who can understand
          systems, identify risks, and build tools that solve real security problems.
        </p>
      </div>
    </section>

    <section id="skills" class="section">
      <p class="section-label">Technical Stack</p>
      <h2>Skills I Use In My Projects</h2>

      <div class="skills-grid">
        <span>Python</span>
        <span>Flask</span>
        <span>Java</span>
        <span>Spring Boot</span>
        <span>MySQL</span>
        <span>Linux</span>
        <span>Kali Linux</span>
        <span>Networking</span>
        <span>Git & GitHub</span>
        <span>Machine Learning</span>
        <span>Packet Analysis</span>
        <span>Cybersecurity</span>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="section-heading">
        <div>
          <p class="section-label">Portfolio</p>
          <h2>Featured Projects</h2>
        </div>
        <p>
          A mix of cybersecurity labs, AI-powered tools, and full-stack web applications.
        </p>
      </div>

      <div class="projects-grid">
        <article class="project-card featured">
          <div class="project-tag">AI Security</div>
          <h3>AI Resume Security Analyzer</h3>
          <p>
            A Flask-based tool that analyzes resumes for privacy risks, PII exposure,
            suspicious URLs, and security recommendations.
          </p>
          <div class="tech">Python • Flask • Privacy • Security Analysis</div>
          <a href="https://github.com/Tharindi-Weerasinghe/ai-resume-security-analyzer" target="_blank">View Repository</a>
        </article>

        <article class="project-card featured">
          <div class="project-tag">Machine Learning</div>
          <h3>Credit Card Fraud Detection</h3>
          <p>
            A fraud detection dashboard using machine learning models and visual analytics
            to identify suspicious transactions.
          </p>
          <div class="tech">Python • Flask • ML • Cyber Analytics</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Credit-Card-Fraud-Detection" target="_blank">View Repository</a>
        </article>

        <article class="project-card">
          <div class="project-tag">Full Stack</div>
          <h3>NexMeet Event Ticket Booking</h3>
          <p>
            A web-based event ticket booking system with event browsing, booking forms,
            and database connectivity.
          </p>
          <div class="tech">Spring Boot • MySQL • HTML • CSS</div>
          <a href="https://github.com/Tharindi-Weerasinghe/NexMeet-Event-Ticket-Booking" target="_blank">View Repository</a>
        </article>

        <article class="project-card">
          <div class="project-tag">Network Security</div>
          <h3>Packet Sniffer</h3>
          <p>
            A cybersecurity lab project that captures and analyzes network packets to
            understand protocols and traffic behavior.
          </p>
          <div class="tech">Python • Scapy • Packet Analysis</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Packet-Sniffer" target="_blank">View Repository</a>
        </article>

        <article class="project-card">
          <div class="project-tag">Reconnaissance</div>
          <h3>Network Scanner</h3>
          <p>
            A Python-based scanner for discovering devices and open ports on authorized
            networks.
          </p>
          <div class="tech">Python • Networking • Kali Linux</div>
          <a href="https://github.com/Tharindi-Weerasinghe/Network-Scanner" target="_blank">View Repository</a>
        </article>

        <article class="project-card">
          <div class="project-tag">Security Basics</div>
          <h3>Password Strength Checker</h3>
          <p>
            A simple security tool that checks password strength and provides improvement
            suggestions.
          </p>
          <div class="tech">Python • Password Security</div>
          <a href="https://github.com/Tharindi-Weerasinghe/password-strength-checker" target="_blank">View Repository</a>
        </article>
      </div>
    </section>

    <section id="certifications" class="section">
      <p class="section-label">Learning</p>
      <h2>Certifications</h2>

      <div class="cert-card">
        <h3>Cisco Introduction to Cybersecurity</h3>
        <p>
          Completed foundational cybersecurity training covering threats, attacks,
          online safety, and security basics.
        </p>
      </div>
    </section>

    <section id="contact" class="section contact-section">
      <div>
        <p class="section-label">Contact</p>
        <h2>Let’s connect.</h2>
        <p>
          I’m open to internship opportunities, cybersecurity projects, and learning-focused
          collaborations.
        </p>
      </div>

      <div class="contact-links">
        <a href="https://github.com/Tharindi-Weerasinghe" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        <a href="mailto:tharindimaleesha0@gmail.com">Email</a>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2026 Tharindi Weerasinghe. Built with HTML, CSS, and JavaScript.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

After you replace it and save, tell me done. Then I’ll send the beautiful cyber style.css.

done

In your index.html, find this line:

<a href="mailto:tharindimaleesha0@gmail.com">Email</a>

Replace it with:

<a href="mailto:maleesha123@gmail.com">Email</a>

That’s it. Save the file, then refresh your website in the browser.

That is usually okay. mailto: only works if your computer/browser has an email app connected, like Outlook, Gmail handler, or Windows Mail. If there is no default email app, clicking it may look like nothing happens.

For portfolio websites, better option: show the email clearly and also keep the click link.

Replace this:

<a href="mailto:maleesha123@gmail.com">Email</a>

with this:

<a href="mailto:maleesha123@gmail.com">maleesha123@gmail.com</a>

Then visitors can see your email even if clicking does not open anything.

You can also test by right-clicking the email link and checking if it shows something like:

Copy email address

or

Copy link address

If yes, the code is correct. The issue is just your computer email app setting.

no no i want to when iclcik that email it goes to the email dierectly like wise
Worked for 11s

Ahh okay, you want it to open Gmail compose directly.

Replace your email link with this:

<a href="https://mail.google.com/mail/?view=cm&fs=1&to=maleesha123@gmail.com" target="_blank">Email</a>

So your contact section should look like this:

<div class="contact-links">
  <a href="https://github.com/Tharindi-Weerasinghe" target="_blank">GitHub</a>
  <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=maleesha123@gmail.com" target="_blank">Email</a>
</div>

Now when someone clicks Email, it opens Gmail with your email already in the To field.

Small note: it works best if the visitor is already logged into Gmail. If they use Outlook/Yahoo, the normal mailto: version is more universal. But for your case, Gmail-direct is fine.

can i know what is this tw 

TW means your initials:

Tharindi Weerasinghe = T W

It is used like a small personal logo in the navbar.

The underscore _ is just for cyber/terminal style, like:

TW_

It gives the feeling of a command line cursor.

If you don’t like it, you can change it. In your index.html, find this line:

<a href="#" class="logo">TW<span>_</span></a>

You can replace it with:

<a href="#" class="logo">Tharindi<span>_</span></a>

or:

<a href="#" class="logo">Tharindi<span>.</span></a>

or:

<a href="#" class="logo">T<span>W</span></a>

I personally think TW_ looks professional and cyber-themed, but Tharindi_ is clearer if you want recruiters to immediately know it is your name.

ah ok done, so i have that certificate that cisco can we add? how to add

Yes, we can add your Cisco certificate beautifully.

Step 1: Create Certificate Folder
Inside your portfolio folder, create this folder:

certificates

Your structure becomes:

portfolio/
├── index.html
├── style.css
├── script.js
├── images/
└── certificates/

Step 2: Add Your Cisco Certificate
Put your Cisco certificate file inside certificates.

Example name:

cisco-introduction-to-cybersecurity.pdf

or if it is an image:

cisco-introduction-to-cybersecurity.png

Use a simple filename, no spaces.

Step 3: Update index.html
Find your certifications section:

<section id="certifications" class="section">
  <p class="section-label">Learning</p>
  <h2>Certifications</h2>

  <div class="cert-card">
    <h3>Cisco Introduction to Cybersecurity</h3>
    <p>
      Completed foundational cybersecurity training covering threats, attacks,
      online safety, and security basics.
    </p>
  </div>
</section>

Replace it with this if your certificate is a PDF:

<section id="certifications" class="section">
  <p class="section-label">Learning</p>
  <h2>Certifications</h2>

  <div class="cert-card">
    <h3>Cisco Introduction to Cybersecurity</h3>
    <p>
      Completed foundational cybersecurity training covering threats, attacks,
      online safety, and security basics.
    </p>
    <a class="cert-link" href="certificates/cisco-introduction-to-cybersecurity.pdf" target="_blank">
      View Certificate
    </a>
  </div>
</section>

If your certificate is an image, use this instead:

<a class="cert-link" href="certificates/cisco-introduction-to-cybersecurity.png" target="_blank">
  View Certificate
</a>

Step 4: Add CSS
At the bottom of your style.css, add:

.cert-link {
  display: inline-flex;
  margin-top: 18px;
  padding: 11px 16px;
  border-radius: 8px;
  background: rgba(0, 245, 255, 0.08);
  border: 1px solid rgba(0, 245, 255, 0.28);
  color: var(--green);
  text-decoration: none;
  font-weight: 700;
  transition: 0.25s ease;
}

.cert-link:hover {
  background: linear-gradient(135deg, var(--cyan), var(--green));
  color: #001018;
}

Then save and refresh your website. When you click View Certificate, it should open your Cisco certificate.

it shows an error 

That error usually means the website cannot find/open the PDF file path correctly.

Do this carefully:

1. Check your folder
Your file must be exactly here:

portfolio/certificates/cisco-introduction-to-cybersecurity.pdf

So inside portfolio, you should have:

index.html
style.css
script.js
certificates/
  cisco-introduction-to-cybersecurity.pdf

2. In index.html, do NOT use full Windows path
Use only this:

<a class="cert-link" href="certificates/cisco-introduction-to-cybersecurity.pdf" target="_blank">
  View Certificate
</a>

Do not use something like:

C:\Users\Malee\OneDrive\Desktop\CyberProjects\portfolio\certificates\...

3. Check filename spelling
Your PDF name and your code name must match 100%.

For example, if your actual file is named:

Introduction_to_Cybersecurity_certificate.pdf

Then your code must be:

<a class="cert-link" href="certificates/Introduction_to_Cybersecurity_certificate.pdf" target="_blank">
  View Certificate
</a>

Best simple fix: rename the certificate file to exactly:

cisco-introduction-to-cybersecurity.pdf

Then use this exact code:

<a class="cert-link" href="certificates/cisco-introduction-to-cybersecurity.pdf" target="_blank">
  View Certificate
</a>

Save index.html, refresh your portfolio, and click again.

ok done what next 

Perfect. Next step is to put this portfolio website on GitHub and make it live.

First, test these 3 things in your browser:

Website opens properly.
Buttons work: About, Skills, Projects, Contact.
View Certificate opens your Cisco certificate.

If all okay, now do this.

Step 1: Create GitHub Repository
Go to GitHub → click New.

Repository name:

portfolio

Set it to:

Public

Do not tick README because you already have local files.

Click Create repository.

Step 2: Open Terminal In VS Code
In VS Code, open your portfolio folder.

Then click:

Terminal > New Terminal

Make sure terminal path looks like:

C:\Users\Malee\OneDrive\Desktop\CyberProjects\portfolio

Step 3: Push To GitHub
Run these commands one by one:

git init
git add .
git commit -m "Initial cybersecurity portfolio website"

Now add your GitHub repo link. It will look like this:

git remote add origin https://github.com/Tharindi-Weerasinghe/portfolio.git

Then:

git branch -M main
git push -u origin main

Step 4: Make It Live
After pushing:

Open your portfolio repository on GitHub.
Go to Settings.
Click Pages from the left side.
Under Source, choose:
Deploy from a branch
Under Branch, choose:
main
Folder:
/root
Click Save.

Wait 2-5 minutes. Your website link should become:

https://tharindi-weerasinghe.github.io/portfolio/

Do Step 1 to Step 3 first. If you get any error in terminal, paste it here before doing the next command.

i cant see like that

That message means GitHub did not receive your website files yet. So Pages cannot find index.html, that’s why branch shows None.

Do this first:

Step 1: Check Repository
Go to your portfolio repository → click Code tab.

If you do not see these files:

index.html
style.css
script.js
certificates/

then the files are still only on your laptop, not pushed to GitHub.

Step 2: Push Files From VS Code
Open VS Code terminal inside your portfolio folder. Run:

git status

Then run:

git add .
git commit -m "Add portfolio website"
git branch -M main

If you already added remote before, run:

git push -u origin main

If it says remote not found, run this first:

git remote add origin https://github.com/Tharindi-Weerasinghe/portfolio.git

Then:

git push -u origin main

Step 3: Go Back To GitHub Pages
After push is successful:

Refresh GitHub.
Go to your repo Code tab and confirm files are visible.
Go to Settings > Pages.
Source: Deploy from a branch.
Branch dropdown should now show:
main
Select:
main
/root
Click Save.

So don’t worry, you are in the correct place. The missing part is just pushing the website files to GitHub first.

 cannot save

That’s okay, you don’t need to click Save now. It is already saved.

See this line in your screenshot:

Your GitHub Pages site is currently being built from the main branch

That means you selected:

main / root

successfully. The Save button is grey because there is nothing new to save.

Now wait 2-5 minutes, then scroll a little higher on the same Pages page. GitHub should show a message like:

Your site is live at ...

Your link should be:

https://tharindi-weerasinghe.github.io/portfolio/

Try opening that link in a new tab.

If it shows 404, wait a few more minutes and refresh. GitHub Pages sometimes takes up to 10 minutes after the first deployment.

cant see Your site is live at ...

That’s okay. Sometimes GitHub doesn’t show it immediately.

Do this now:

Go to your repository.
Click Actions tab at the top.
Look for something like:
pages build and deployment

Now check the color:

Yellow/orange = still building, wait
Green tick = website is live
Red cross = build failed

If it is green, open this link manually:

https://tharindi-weerasinghe.github.io/portfolio/

If it shows 404, wait 5-10 minutes and refresh.

Also check this important thing: in your repo Code tab, index.html must be directly visible like this:

portfolio/
├── index.html
├── style.css
├── script.js
├── certificates/

Not like this:

portfolio/
└── portfolio/
    ├── index.html

If you see a red cross in Actions, click it and send me a screenshot. Then I’ll tell you exactly what error it is.

is this one

No, not this one. Don’t click Configure there. That page is showing GitHub Actions templates like AWS/GKE, not your portfolio deployment.

Do this:

At the top of GitHub, click Code.
Check if you can see these files directly:
index.html
style.css
script.js
certificates
Then click Settings > Pages again.
Refresh the page after 1-2 minutes.
Try opening this link manually:
https://tharindi-weerasinghe.github.io/portfolio/

If it still does not open, send me a screenshot of your repository Code page where the files are shown. I need to check whether index.html is in the correct place.

 not working4

Your settings are correct. The important line is here:

Your GitHub Pages site is currently being built from the main branch.

So GitHub Pages is enabled. The 404 means the build is not finished yet or the deployment failed.

Do this now:

Step 1: Check The Real Build
Click the Actions tab at the top of your repository.

Not the AWS/GKE page. Just click this top tab:

Actions

You should see something like:

pages build and deployment

Check the icon:

Yellow = still building
Green tick = done
Red cross = failed

Step 2: If You See Green Tick
Open:

https://tharindi-weerasinghe.github.io/portfolio/

If still 404, wait 5 minutes and refresh.

Step 3: If You See Red Cross
Click the red failed build and send me a screenshot.

Step 4: If Nothing Shows In Actions
Open VS Code terminal inside your portfolio folder and run:

git commit --allow-empty -m "Trigger GitHub Pages deployment"

Then:

git push

After that, wait 2-5 minutes and check the link again.

Also check one important thing in your GitHub Code tab: index.html must be directly visible in the repo,, not inside another folder.

these are the things i can see

You are on the GitHub Actions template page. Don’t click any Configure button there.

This means GitHub did not start the Pages deployment properly yet. Let’s trigger it manually.

Do This In VS Code Terminal

Open your portfolio folder in VS Code, then open terminal and run:

git status

Then run these:

git add .
git commit --allow-empty -m "Trigger portfolio deployment"
git push

After that:

Go back to GitHub.
Click Actions tab again.
Now you should see a run like:
pages build and deployment

Wait until it becomes a green tick.

Then open:

https://tharindi-weerasinghe.github.io/portfolio/

Also one very important check: go to your repo Code tab and see if index.html is directly visible. If you don’t see index.html on the first page of the repo, send me that Code page screenshot. That will tell us the exact problem.

its working now what should i do next

Yesss good, your portfolio is live now.

Next do these small but important finishing steps:

Copy your portfolio link

https://tharindi-weerasinghe.github.io/portfolio/
Add it to your GitHub profile
Go to your GitHub profile.
Click Edit profile.
In Website, paste your portfolio link.
Save.
Add it to LinkedIn
Open LinkedIn profile.
Click the pencil/edit icon on your intro section.
Find Website or Contact info.
Add your portfolio link.
Save.
Pin your best repos on GitHub
Pin these:
ai-resume-security-analyzer
Credit-Card-Fraud-Detection
Packet-Sniffer
Network-Scanner
portfolio
NexMeet-Event-Ticket-Booking
Check your portfolio on phone
Open the website on your phone and check:
Text is readable
Project cards look okay
GitHub links open
Certificate opens
Email button opens Gmail

After that, we can improve your portfolio more by adding project screenshots to each project card. That will make it look much more professional.

first of all my it hub acc is empy like can we make this like cyber theme idk like ebutiful not like someone else copy right quniquw e oen 

Yes, we can make your GitHub profile look much better. GitHub profile itself cannot fully change theme like CSS, but we can make it look cyber/professional using:

Profile details
Pinned repositories
Special GitHub profile README.md

First Fill These Fields
On the page you are showing, add:

Name

Tharindi Weerasinghe

Bio

Cybersecurity undergraduate building practical projects in network security, AI security, fraud detection, and secure web applications.

Company

SLIIT | Faculty of Computing

Location

Sri Lanka

Website

https://tharindi-weerasinghe.github.io/portfolio/

Social account 1
Add your LinkedIn link.

Then click Save.

Next: Create Cyber Profile README
This is the special part. Create a new GitHub repository with the exact same name as your username:

Tharindi-Weerasinghe

Important:

Make it Public
Tick Add a README file
Click Create repository

Then open the README.md, click edit, and paste this:

<h1 align="center">Hi, I'm Tharindi Weerasinghe</h1>

<p align="center">
  <b>Cybersecurity Undergraduate | Python | Linux | Network Security | AI Security</b>
</p>

<p align="center">
  <a href="https://tharindi-weerasinghe.github.io/portfolio/">Portfolio</a> •
  <a href="https://github.com/Tharindi-Weerasinghe">GitHub</a> •
  <a href="mailto:maleesha123@gmail.com">Email</a>
</p>

---

### About Me

I am a cybersecurity undergraduate from Sri Lanka, focused on building practical security projects that connect theory with real-world tools.

My current work includes network scanning, packet analysis, privacy risk detection, fraud detection, secure web applications, and AI-powered cybersecurity tools.

---

### Technical Focus

```text
> whoami
Cybersecurity Undergraduate

> current_focus
Network Security | AI Security | Secure Web Applications

> tools
Python | Flask | Linux | Kali Linux | MySQL | Java | Git | GitHub
Featured Projects
Project	Description	Tech
AI Resume Security Analyzer	Detects privacy risks, PII exposure, suspicious URLs, and resume security issues	Python, Flask
Credit Card Fraud Detection	ML dashboard for detecting suspicious financial transactions	Python, Flask, ML
Packet Sniffer	Captures and analyzes network packets for traffic understanding	Python, Scapy
Network Scanner	Scans authorized networks for devices and open ports	Python, Networking
NexMeet Event Ticket Booking	Event ticket booking system with database support	Spring Boot, MySQL
Password Strength Checker	Checks password strength and gives improvement suggestions	Python
Skills
Cybersecurity    Network Security    Packet Analysis
Python           Flask               Linux
Kali Linux       MySQL               Java
Machine Learning Git & GitHub        Web Development
Certification
Cisco Introduction to Cybersecurity
Current Goal

I am currently improving my cybersecurity fundamentals, practical project experience, and professional portfolio to prepare for internship opportunities.

<p align="center"> <b>Building, learning, improving, and growing one project at a time.</b> </p> ```

After pasting it:

Click Commit changes
Go back to your GitHub profile
Refresh the page

Then your GitHub profile will show this beautiful cyber-style intro automatically.

that bio looks weired can we make another one just eaerch how others are do that
Worked for 19s

Yes, you’re right. GitHub bios are usually short, with keywords, not a full sentence paragraph. Many profile guides suggest keeping it simple and focused on what you study/do.

Use one of these instead:

Best Option

Cybersecurity Undergraduate | Python • Linux • Network Security • AI Security

More Natural

Cybersecurity undergraduate exploring network security, AI security, and secure web development.

More Professional

Cybersecurity Undergraduate | Building projects in network security, privacy, and AI-powered security tools

Short And Clean

Cybersecurity Undergraduate | Python | Linux | Security Projects

Internship-Focused

Cybersecurity undergraduate preparing for internships through hands-on security and AI projects.

My recommendation for your GitHub bio:

Cybersecurity Undergraduate | Python • Linux • Network Security • AI Security

It’s clean, modern, and not weird. Put that in the Bio box, then save.

no not like this for examplpe like this , i dont want exactly copy right but more than like that beautiful cybertheme 

Ahh I understand now. You don’t mean only the small Bio text. You mean your GitHub profile page should look cyber-themed and beautiful, like a custom profile README.

Also, the image you sent looks almost blank on my side, but I get the idea.

Important: GitHub profile cannot use full CSS like a website. But we can make it look cyber-style using Markdown, HTML, badges, terminal blocks, banners, and project tables.

Use this for your small Bio box:

Cybersecurity Undergraduate | Building security tools, AI projects, and network labs

Then create the special README.

Step 1
Create a repository with the exact same name as your username:

Tharindi-Weerasinghe

Make it Public and tick Add README.

Step 2
Open README.md, click edit, delete everything, and paste this:

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:00f5ff,100:22c55e&height=220&section=header&text=Tharindi%20Weerasinghe&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Cybersecurity%20Undergraduate%20%7C%20AI%20Security%20%7C%20Network%20Security&descAlignY=58&descSize=16" />

</div>

```bash
┌──(tharindi㉿cybersec)-[~/profile]
└─$ whoami
Cybersecurity Undergraduate | Security Project Builder | AI + Network Security Learner
> about_me

I am a cybersecurity undergraduate from Sri Lanka, building practical projects in network security, privacy protection, fraud detection, AI-powered security tools, and secure web applications.

I use GitHub to document my learning journey, improve my technical skills, and build a portfolio for future cybersecurity internship opportunities.

> current_focus
[+] Network Security
[+] Packet Analysis
[+] Python Security Tools
[+] AI-Powered Cybersecurity
[+] Secure Web Applications
[+] Machine Learning for Fraud Detection
> tech_stack
<p align="left"> <img src="https://img.shields.io/badge/Python-0f172a?style=for-the-badge&logo=python&logoColor=22c55e" /> <img src="https://img.shields.io/badge/Flask-0f172a?style=for-the-badge&logo=flask&logoColor=00f5ff" /> <img src="https://img.shields.io/badge/Linux-0f172a?style=for-the-badge&logo=linux&logoColor=ffffff" /> <img src="https://img.shields.io/badge/Kali_Linux-0f172a?style=for-the-badge&logo=kalilinux&logoColor=00f5ff" /> <img src="https://img.shields.io/badge/MySQL-0f172a?style=for-the-badge&logo=mysql&logoColor=22c55e" /> <img src="https://img.shields.io/badge/Java-0f172a?style=for-the-badge&logo=openjdk&logoColor=ffffff" /> <img src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=00f5ff" /> </p>

> featured_projects
Project	Type	Description
AI Resume Security Analyzer	AI Security	Detects PII exposure, privacy risks, suspicious URLs, and resume security issues
Credit Card Fraud Detection	Machine Learning	Fraud detection dashboard using ML models and visual analytics
Packet Sniffer	Network Security Lab	Captures and analyzes network packets using Python and Scapy
Network Scanner	Recon Lab	Discovers devices and open ports on authorized networks
NexMeet Event Ticket Booking	Web App	Event ticket booking system using Spring Boot and MySQL
Password Strength Checker	Security Tool	Checks password strength and provides improvement suggestions

> certification
Cisco Introduction to Cybersecurity
> github_activity
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=Tharindi-Weerasinghe&show_icons=true&theme=tokyonight&hide_border=true&bg_color=020617&title_color=00f5ff&icon_color=22c55e&text_color=e5e7eb" /> </p> <p align="center"> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tharindi-Weerasinghe&layout=compact&theme=tokyonight&hide_border=true&bg_color=020617&title_color=00f5ff&text_color=e5e7eb" /> </p>
> connect
<p align="left"> <a href="https://tharindi-weerasinghe.github.io/portfolio/"> <img src="https://img.shields.io/badge/Portfolio-00f5ff?style=for-the-badge&logo=vercel&logoColor=020617" /> </a> <a href="mailto:maleesha123@gmail.com"> <img src="https://img.shields.io/badge/Email-22c55e?style=for-the-badge&logo=gmail&logoColor=020617" /> </a> <a href="https://www.linkedin.com/"> <img src="https://img.shields.io/badge/LinkedIn-0ea5e9?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> </p>
┌──(learning㉿progress)-[~/cybersecurity]
└─$ status
Building skills. Improving daily. Preparing for internship opportunities.
<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22c55e,50:00f5ff,100:020617&height=120&section=footer" /> </div> ```
