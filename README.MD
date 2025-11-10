<body>
  <style>
    /* Base styles */
    :root {
      --primary-color: #81a1c0;
      --secondary-color: #79ff97;
      --text-color: #d5dbe6;
      --bg-color: #2e3440;
      --accent-color: #81a1c0;
      --highlight-color: #79ff97;
      --card-bg: #3b4252;
      --border-color: #4c566a;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      padding: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .container {
      background-color: var(--card-bg);
      border-radius: 15px;
      padding: 30px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      margin-bottom: 30px;
      border: 1px solid var(--border-color);
    }
    .header {
      text-align: center;
      padding: 20px 0;
      margin-bottom: 30px;
      border-bottom: 2px solid var(--accent-color);
    }
    .header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: var(--highlight-color);
    }
    .header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }
    .section-title {
      font-size: 1.8rem;
      margin: 30px 0 20px 0;
      color: var(--highlight-color);
      text-align: center;
      position: relative;
    }
    .section-title::after {
      content: "";
      display: block;
      width: 100px;
      height: 3px;
      background: var(--accent-color);
      margin: 10px auto;
      border-radius: 2px;
    }
    .about-content {
      text-align: center;
      padding: 20px;
      font-size: 1.1rem;
      line-height: 1.8;
    }
    .stats-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin: 30px 0;
    }
    .stat-card {
      background: var(--bg-color);
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      min-width: 250px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }
    .stat-card:hover {
      transform: translateY(-5px);
    }
    .stat-card h3 {
      color: var(--highlight-color);
      margin-bottom: 10px;
    }
    .skills-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin: 30px 0;
    }
    .skill-category {
      background: var(--bg-color);
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
      transition: all 0.3s ease;
    }
    .skill-category:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
    }
    .skill-category h3 {
      color: var(--highlight-color);
      margin-bottom: 15px;
      text-align: center;
      font-size: 1.4rem;
    }
    .skill-icons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin-top: 10px;
    }
    .skill-icon {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      min-width: 60px;
    }
    .skill-icon img {
      width: 50px;
      height: 50px;
      margin-bottom: 5px;
    }
    .skill-icon span {
      font-size: 0.8rem;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }
    .contact-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 30px 0;
    }
    .contact-link {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 12px 20px;
      background: var(--bg-color);
      border-radius: 25px;
      text-decoration: none;
      color: var(--text-color);
      font-weight: bold;
      transition: all 0.3s ease;
      border: 1px solid var(--border-color);
    }
    .contact-link:hover {
      background: var(--accent-color);
      color: #000;
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }
    .footer {
      text-align: center;
      padding: 20px;
      margin-top: 30px;
      border-top: 2px solid var(--accent-color);
      font-size: 0.9rem;
      opacity: 0.8;
    }
    .highlight {
      color: var(--highlight-color);
      font-weight: bold;
    }
    /* Responsive design */
    @media (max-width: 768px) {
      body {
        padding: 10px;
      }
      .container {
        padding: 20px;
      }
      .header h1 {
        font-size: 2rem;
      }
      .section-title {
        font-size: 1.5rem;
      }
      .stats-container {
        flex-direction: column;
        align-items: center;
      }
      .stat-card {
        width: 100%;
        max-width: 300px;
      }
    }
  </style>
  <div class="container">
    <div class="header">
      <h1>Willy Samuel Paz Colque</h1>
      <p>
        🚀 Passionate Developer | 🧠 AI Engineer | 🚀 Full-Stack Developer
      </p>
    </div>
    <div class="section-title">🎯 About Me</div>
    <div class="about-content">
      <p>
          I am a <span class="highlight">Full‑Stack & AI Engineer</span> who focuses on building
          <span class="highlight">web services and LLM‑based solutions</span>—chatbots, virtual assistants,
          and agents—designed for high performance and scalability.
      </p>
      <p>
          My journey into programming started with the <em>World Editor</em> of Warcraft III.
          That first taste of what a computer could do sparked an obsession that has
          driven me ever since. I love studying software, experimenting, solving complex
          problems, and watching my creations work—especially when they make someone’s
          life easier.
      </p>
      <p>
          Quality and efficiency are at the core of my approach. I prioritize clean code,
          solid best‑practice habits, and thorough testing. I’m comfortable not only
          writing code but also designing system architectures and deploying applications
          to production.
      </p>
      <p>
          Currently I’m deepening my expertise in <span class="highlight">artificial intelligence,
          software architecture, and micro‑services</span>, while exploring the DevOps
          world with Docker, Kubernetes, and Linux system administration.
      </p>
      <p>
          When I’m not coding, you’ll find me scouting new technologies, keeping up with
          industry news, or simply relaxing with a series, hanging out with friends, or
          enjoying a quiet day—because not everything has to be tech‑focused.
      </p>
      <p>
          Got an idea you’d like to bring to life? I’m always open to collaborating on new
          projects. Let me know how I can help!
      </p>
    </div>
    <div class="section-title">📊 GitHub Statistics</div>
    <div class="stats-container">
      <div class="stat-card">
        <h3>Top Languages</h3>
        <img
          src="https://github-readme-stats.vercel.app/api/top-langs/?username=willypaz243&layout=compact&show_icons=true&title_color=81a1c0&icon_color=79ff97&text_color=d5dbe6&bg_color=2e3440&cache_seconds=86400"
          alt="Top Languages"
        />
      </div>
      <div class="stat-card">
        <h3>GitHub Stats</h3>
        <img
          src="https://github-readme-stats.vercel.app/api?username=willypaz243&show_icons=true&hide=contribs&cache_seconds=86400&theme=nord"
          alt="GitHub Stats"
        />
      </div>
    </div>
    <div class="section-title">🚀 Technical Skills</div>
    <div class="skills-container">
      <div class="skill-category">
        <h3>🧠 Artificial Intelligence & Machine Learning</h3>
        <div class="skill-icons">
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=python" alt="Python" />
            <span>Python</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=pytorch" alt="PyTorch" />
            <span>PyTorch</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=tensorflow"
              alt="TensorFlow"
            />
            <span>TensorFlow</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=scikitlearn"
              alt="Scikit-learn"
            />
            <span>Scikit-learn</span>
          </div>
        </div>
      </div>
      <div class="skill-category">
        <h3>🖥️ Programming Languages</h3>
        <div class="skill-icons">
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=python" alt="Python" />
            <span>Python</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=javascript"
              alt="JavaScript"
            />
            <span>JavaScript</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=typescript"
              alt="TypeScript"
            />
            <span>TypeScript</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=java" alt="Java" />
            <span>Java</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=html" alt="HTML" />
            <span>HTML</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=css" alt="CSS" />
            <span>CSS</span>
          </div>
        </div>
      </div>
      <div class="skill-category">
        <h3>🧰 Backend & Frameworks</h3>
        <div class="skill-icons">
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" />
            <span>Node.js</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=nestjs" alt="Nest.js" />
            <span>Nest.js</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=fastapi" alt="FastAPI" />
            <span>FastAPI</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=flask" alt="Flask" />
            <span>Flask</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=django" alt="Django" />
            <span>Django</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=expressjs"
              alt="Express.js"
            />
            <span>Express.js</span>
          </div>
        </div>
      </div>
      <div class="skill-category">
        <h3>🗄️ Databases & Tools</h3>
        <div class="skill-icons">
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" />
            <span>MySQL</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=postgresql"
              alt="PostgreSQL"
            />
            <span>PostgreSQL</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=sqlite" alt="SQLite" />
            <span>SQLite</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB" />
            <span>MongoDB</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=git" alt="Git" />
            <span>Git</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=docker" alt="Docker" />
            <span>Docker</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=aws" alt="AWS" />
            <span>AWS</span>
          </div>
        </div>
      </div>
      <div class="skill-category">
        <h3>🌐 Frontend Development</h3>
        <div class="skill-icons">
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=react" alt="React" />
            <span>React</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=vite" alt="Vite" />
            <span>Vite</span>
          </div>
          <div class="skill-icon">
            <img src="https://skillicons.dev/icons?i=angular" alt="Angular" />
            <span>Angular</span>
          </div>
          <div class="skill-icon">
            <img
              src="https://skillicons.dev/icons?i=bootstrap"
              alt="Bootstrap"
            />
            <span>Bootstrap</span>
          </div>
        </div>
      </div>
    </div>
    <div class="section-title">🌐 Connect with Me</div>
    <div class="contact-links">
      <a
        href="https://www.linkedin.com/in/willy-samuel-paz-colque-701007230/"
        target="_blank"
        class="contact-link"
      >
        <img
          src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"
          alt="LinkedIn"
        />
        LinkedIn
      </a>
      <a
        href="https://github.com/willypaz243"
        target="_blank"
        class="contact-link"
      >
        <img
          src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"
          alt="GitHub"
        />
        GitHub
      </a>
      <a
        href="mailto:willypazcolque@gmail.com"
        target="_blank"
        class="contact-link"
      >
        <img
          src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"
          alt="Email"
        />
        Email
      </a>
    </div>
    <div class="section-title">🚀 Let's Build the Future Together!</div>
    <div class="about-content">
      <p>
        I'm always excited to collaborate on innovative projects that push the
        boundaries of what's possible with technology and AI. Let's create
        something amazing together!
      </p>
    </div>
    <div class="footer">
      <p>
        This profile was created with ❤️ and a passion for technology and AI
      </p>
    </div>
  </div>
</body>