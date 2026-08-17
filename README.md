<!-- ========================= HERO ========================= -->

<div align="center">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;700&display=swap');

    .hero {
      position: relative;
      background: linear-gradient(-45deg, #0f0c29, #302b63, #24243e, #06b6d4);
      background-size: 400% 400%;
      animation: gradientMove 12s ease infinite;
      padding: 3rem 1rem 4rem;
      border-radius: 2rem;
      margin: 0 0 2rem;
      box-shadow: 0 20px 60px rgba(6, 182, 212, 0.2);
      overflow: hidden;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .hero::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle at 30% 50%, rgba(6, 182, 212, 0.08) 0%, transparent 60%);
      animation: pulseGlow 8s ease-in-out infinite alternate;
    }

    @keyframes pulseGlow {
      0% { transform: scale(1) rotate(0deg); opacity: 0.5; }
      100% { transform: scale(1.2) rotate(10deg); opacity: 1; }
    }

    .hero h1 {
      font-family: 'Space Grotesk', sans-serif;
      font-size: 4.5rem;
      font-weight: 700;
      background: linear-gradient(135deg, #ffffff 0%, #a5f3fc 50%, #06b6d4 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-size: 200% 200%;
      animation: shimmer 5s ease-in-out infinite;
      position: relative;
      z-index: 2;
    }

    @keyframes shimmer {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .hero .subtitle {
      font-family: 'Space Grotesk', sans-serif;
      font-size: 1.2rem;
      color: #cbd5e1;
      letter-spacing: 2px;
      margin-top: 0.5rem;
      position: relative;
      z-index: 2;
      animation: fadeUp 1.5s ease-out both;
    }

    @keyframes fadeUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    .floating-particle {
      position: absolute;
      width: 6px;
      height: 6px;
      background: #06b6d4;
      border-radius: 50%;
      filter: blur(1px);
      animation: floatParticle 15s infinite linear;
      z-index: 1;
    }

    @keyframes floatParticle {
      0% { transform: translate(0, 0) scale(1); opacity: 0.3; }
      50% { opacity: 0.9; }
      100% { transform: translate(calc(100vw - 200px), -200px) scale(0); opacity: 0; }
    }
  </style>

  <div class="hero">
    <div class="floating-particle" style="top:20%;left:10%;animation-duration:18s;"></div>
    <div class="floating-particle" style="top:60%;left:80%;animation-duration:22s;width:10px;height:10px;background:#7c3aed;"></div>
    <div class="floating-particle" style="top:40%;left:50%;animation-duration:14s;width:4px;height:4px;background:#facc15;"></div>
    <div class="floating-particle" style="top:80%;left:20%;animation-duration:20s;width:8px;height:8px;background:#ec4899;"></div>

    <h1>DHANUSH M</h1>
    <div class="subtitle">FULL STACK DEVELOPER &nbsp;|&nbsp; UI/UX ENTHUSIAST &nbsp;|&nbsp; AI EXPLORER</div>

    <br>

    <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&size=22&duration=3000&pause=700&color=06B6D4&center=true&vCenter=true&width=700&lines=Building+Digital+Experiences+%F0%9F%9A%80;Crafting+Modern+UI%2FUX+%F0%9F%8E%A8;Developing+Full+Stack+Applications+%E2%9A%A1;Exploring+AI+%2B+Web+Development+%F0%9F%A4%96;Turning+Ideas+Into+Products+%F0%9F%92%A1" alt="Typing Animation" style="position:relative;z-index:2;"/>

    <br>

    <img src="https://komarev.com/ghpvc/?username=dhanush1374949&label=PROFILE%20VIEWS&color=06B6D4&style=for-the-badge" style="position:relative;z-index:2;margin-top:0.5rem;"/>
  </div>
</div>

---

<!-- ========================= SOCIAL ========================= -->

<div align="center">
  <style>
    .social-links a {
      display: inline-block;
      margin: 0 0.5rem;
      transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
      text-decoration: none;
    }
    .social-links a:hover {
      transform: translateY(-5px) scale(1.05);
      filter: drop-shadow(0 8px 20px rgba(6, 182, 212, 0.4));
    }
  </style>
  <div class="social-links">
    <a href="https://dhanush1374949.github.io/Morden-portfolio/"><img src="https://img.shields.io/badge/🌐%20PORTFOLIO-00D9FF?style=for-the-badge&logoColor=white"/></a>
    <a href="https://www.linkedin.com/in/dhanush-m-970136325/"><img src="https://img.shields.io/badge/LINKEDIN-111827?style=for-the-badge&logo=linkedin&logoColor=00D9FF"/></a>
    <a href="https://www.behance.net/dhanushmurugan2596"><img src="https://img.shields.io/badge/BEHANCE-111827?style=for-the-badge&logo=behance&logoColor=00D9FF"/></a>
    <a href="mailto:dhanushmurugan3075@gmail.com"><img src="https://img.shields.io/badge/EMAIL-111827?style=for-the-badge&logo=gmail&logoColor=00D9FF"/></a>
  </div>
</div>

<br>

---

<!-- ========================= INTRO ========================= -->

<h2 align="center">⚡ ABOUT ME</h2>

<style>
  .about-box {
    background: linear-gradient(145deg, #0d1117, #161b22);
    border: 1px solid #30363d;
    border-radius: 1.5rem;
    padding: 2rem;
    margin: 1rem auto;
    max-width: 600px;
    box-shadow: 0 8px 32px rgba(0,0,0,0.4);
    transition: all 0.4s ease;
    animation: glowPulse 4s ease-in-out infinite alternate;
  }
  .about-box:hover {
    transform: scale(1.01);
    border-color: #06b6d4;
  }
  @keyframes glowPulse {
    0% { box-shadow: 0 0 20px rgba(6,182,212,0.1); }
    100% { box-shadow: 0 0 40px rgba(6,182,212,0.25); }
  }
  .about-box pre {
    color: #e6edf3;
    font-family: 'Fira Code', monospace;
    font-size: 0.95rem;
    line-height: 1.6;
    text-align: left;
  }
  .about-box pre .highlight {
    color: #06b6d4;
    font-weight: bold;
  }
</style>

<div align="center">
  <div class="about-box">
    <pre>
╭──────────────────────────────────────────────────────────╮
│                                                          │
│   👋 Hi, I'm <span class="highlight">Dhanush</span>                                    │
│                                                          │
│   🎓 BCA Graduate                                       │
│   ⚛️  Full Stack Developer                              │
│   🎨 UI/UX Enthusiast                                   │
│   🤖 AI Explorer                                        │
│   🚀 Product Builder                                    │
│                                                          │
│   I transform ideas → interfaces → products.             │
│                                                          │
╰──────────────────────────────────────────────────────────╯
    </pre>
  </div>
</div>

<br>

<div align="center">
  <style>
    .mindset-card {
      display: inline-block;
      background: #0d1117;
      border-radius: 1.2rem;
      padding: 1.8rem 2.5rem;
      border-left: 4px solid #06b6d4;
      box-shadow: 0 4px 16px rgba(0,0,0,0.3);
      animation: slideInLeft 1s ease-out both;
    }
    @keyframes slideInLeft {
      0% { opacity: 0; transform: translateX(-30px); }
      100% { opacity: 1; transform: translateX(0); }
    }
    .mindset-card pre {
      color: #c9d1d9;
      font-family: 'Fira Code', monospace;
      font-size: 0.95rem;
      line-height: 1.8;
      text-align: left;
    }
    .mindset-card pre .tag {
      color: #f0883e;
    }
    .mindset-card pre .value {
      color: #06b6d4;
    }
  </style>

  <img align="right" width="360" src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWg0aDdmNDg0d2lyNDc0YXM0MjQwaGZhOTN0ZTB4bXl4M3FmdDcybSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/78XCFBGOlS6keY1Bil/giphy.gif" style="border-radius:1rem;box-shadow:0 8px 30px rgba(0,0,0,0.5);"/>

  <div class="mindset-card">
    <pre>
<span class="tag">Design</span>       → <span class="value">Think visually</span>
<span class="tag">Code</span>         → <span class="value">Build efficiently</span>
<span class="tag">AI</span>           → <span class="value">Explore intelligently</span>
<span class="tag">UX</span>           → <span class="value">Keep it simple</span>
<span class="tag">Performance</span>  → <span class="value">Keep it fast</span>
<span class="tag">Learning</span>     → <span class="value">Never stop</span>
    </pre>
  </div>

  <br clear="right"/>
</div>

---

<!-- ========================= TECH STACK ========================= -->

<h2 align="center">🧩 TECH STACK</h2>

<style>
  .tech-icons img {
    transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
    margin: 0.3rem;
  }
  .tech-icons img:hover {
    transform: scale(1.15) rotate(2deg);
    filter: drop-shadow(0 0 20px rgba(6, 182, 212, 0.5));
  }
  .tech-section {
    margin: 1.5rem 0;
  }
  .tech-section h4 {
    color: #8b949e;
    letter-spacing: 2px;
    font-weight: 400;
    margin-bottom: 0.8rem;
    border-bottom: 1px solid #21262d;
    display: inline-block;
    padding-bottom: 0.3rem;
  }
</style>

<div align="center" class="tech-icons">

<div class="tech-section">
  <h4>⚛️ FRONTEND</h4><br>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap&theme=dark&perline=6"/>
</div>

<div class="tech-section">
  <h4>⚙️ BACKEND</h4><br>
  <img src="https://skillicons.dev/icons?i=nodejs,express,python&theme=dark&perline=6"/>
</div>

<div class="tech-section">
  <h4>🗄️ DATABASE</h4><br>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql&theme=dark&perline=6"/>
</div>

<div class="tech-section">
  <h4>🎨 DESIGN</h4><br>
  <img src="https://skillicons.dev/icons?i=figma,photoshop,ai&theme=dark&perline=6"/>
</div>

<div class="tech-section">
  <h4>🛠️ TOOLS</h4><br>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman&theme=dark&perline=6"/>
</div>

</div>

---

<!-- ========================= CURRENTLY BUILDING ========================= -->

<h2 align="center">🚧 CURRENTLY BUILDING</h2>

<style>
  .building-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 0.8rem;
    max-width: 700px;
    margin: 0 auto;
    padding: 0 1rem;
  }
  .building-item {
    background: #0d1117;
    border-radius: 1rem;
    padding: 1rem 0.8rem;
    border: 1px solid #21262d;
    transition: all 0.3s ease;
    text-align: center;
    animation: fadeInScale 0.6s ease both;
    animation-delay: calc(var(--i, 0) * 0.1s);
  }
  .building-item:hover {
    border-color: #06b6d4;
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(6,182,212,0.15);
  }
  @keyframes fadeInScale {
    0% { opacity: 0; transform: scale(0.9); }
    100% { opacity: 1; transform: scale(1); }
  }
  .building-item .area {
    font-weight: 700;
    color: #06b6d4;
    font-size: 1.1rem;
  }
  .building-item .focus {
    color: #8b949e;
    font-size: 0.85rem;
    margin-top: 0.2rem;
  }
</style>

<div align="center">
  <div class="building-grid">
    <div class="building-item" style="--i:1;"><div class="area">⚛️ Frontend</div><div class="focus">React • Modern UI</div></div>
    <div class="building-item" style="--i:2;"><div class="area">🌐 Backend</div><div class="focus">Node.js • REST APIs</div></div>
    <div class="building-item" style="--i:3;"><div class="area">🤖 AI</div><div class="focus">AI-powered Web Apps</div></div>
    <div class="building-item" style="--i:4;"><div class="area">🎨 Design</div><div class="focus">UI Systems • UX</div></div>
    <div class="building-item" style="--i:5;"><div class="area">⚡ Performance</div><div class="focus">Fast • Responsive</div></div>
    <div class="building-item" style="--i:6;"><div class="area">🧠 Learning</div><div class="focus">Full Stack + AI</div></div>
  </div>
</div>

---

<!-- ========================= PROJECT FLOW ========================= -->

<h2 align="center">💡 HOW I BUILD</h2>

<style>
  .flow-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 1.5rem 0;
  }
  .flow-step {
    background: #0d1117;
    border-radius: 2rem;
    padding: 0.5rem 2rem;
    margin: 0.25rem 0;
    border: 1px solid #21262d;
    font-size: 1.1rem;
    font-weight: 500;
    color: #e6edf3;
    transition: all 0.3s ease;
    width: fit-content;
    animation: flowIn 0.8s ease both;
    animation-delay: calc(var(--i, 0) * 0.12s);
  }
  .flow-step:hover {
    background: #161b22;
    border-color: #06b6d4;
    transform: scale(1.03) translateY(-2px);
    box-shadow: 0 4px 20px rgba(6,182,212,0.15);
  }
  @keyframes flowIn {
    0% { opacity: 0; transform: translateX(-20px); }
    100% { opacity: 1; transform: translateX(0); }
  }
  .flow-arrow {
    color: #06b6d4;
    font-size: 1.5rem;
    margin: -0.3rem 0;
    animation: bounceArrow 1.2s infinite alternate ease-in-out;
  }
  @keyframes bounceArrow {
    0% { transform: translateY(0); opacity: 0.7; }
    100% { transform: translateY(6px); opacity: 1; }
  }
</style>

<div align="center">
  <div class="flow-container">
    <div class="flow-step" style="--i:0;">💡 IDEA</div>
    <div class="flow-arrow">⬇</div>
    <div class="flow-step" style="--i:1;">📋 RESEARCH</div>
    <div class="flow-arrow">⬇</div>
    <div class="flow-step" style="--i:2;">🎨 UI / UX</div>
    <div class="flow-arrow">⬇</div>
    <div class="flow-step" style="--i:3;">⚙️ DEVELOP</div>
    <div class="flow-arrow">⬇</div>
    <div class="flow-step" style="--i:4;">🧪 TEST</div>
    <div class="flow-arrow">⬇</div>
    <div class="flow-step" style="--i:5; background: linear-gradient(135deg, #06b6d4, #7c3aed); color: #fff; border: none;">🚀 DEPLOY</div>
  </div>
</div>

---

<!-- ========================= GITHUB ANALYTICS ========================= -->

<h2 align="center">📊 GITHUB ANALYTICS</h2>

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=dhanush1374949&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF" style="border-radius:1rem;box-shadow:0 4px 20px rgba(0,0,0,0.3);"/>
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhanush1374949&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF" style="border-radius:1rem;box-shadow:0 4px 20px rgba(0,0,0,0.3);"/>
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dhanush1374949&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=7C3AED&currStreakLabel=00D9FF" style="border-radius:1rem;box-shadow:0 4px 20px rgba(0,0,0,0.3);"/>
</div>

---

<!-- ========================= TROPHIES ========================= -->

<h2 align="center">🏆 ACHIEVEMENTS</h2>

<style>
  .trophy-wrapper img {
    transition: all 0.3s ease;
    filter: drop-shadow(0 2px 8px rgba(0,0,0,0.4));
  }
  .trophy-wrapper img:hover {
    transform: scale(1.05) rotate(-1deg);
    filter: drop-shadow(0 0 20px rgba(6,182,212,0.3));
  }
</style>

<div align="center" class="trophy-wrapper">
  <img src="https://github-profile-trophy.vercel.app/?username=dhanush1374949&theme=algolia&no-frame=true&no-bg=true&margin-w=8&row=2&column=4"/>
</div>

---

<!-- ========================= CONTRIBUTION ========================= -->

<h2 align="center">🐍 CONTRIBUTION ACTIVITY</h2>

<div align="center">
  <img src="https://raw.githubusercontent.com/dhanush1374949/dhanush1374949/output/github-contribution-grid-snake-dark.svg" width="100%" style="border-radius:1rem;"/>
</div>

---

<!-- ========================= DEVELOPER TERMINAL ========================= -->

<h2 align="center">💻 TERMINAL</h2>

<style>
  .terminal-box {
    background: #0d1117;
    border-radius: 1.2rem;
    padding: 1.5rem 2rem;
    max-width: 600px;
    margin: 0 auto;
    border: 1px solid #30363d;
    box-shadow: 0 8px 30px rgba(0,0,0,0.5);
    font-family: 'Fira Code', monospace;
    text-align: left;
    color: #e6edf3;
  }
  .terminal-box .prompt {
    color: #06b6d4;
  }
  .terminal-box .cmd {
    color: #f0883e;
  }
  .terminal-box .output {
    color: #8b949e;
    margin-left: 1.5rem;
  }
  .terminal-box .cursor {
    display: inline-block;
    width: 8px;
    height: 18px;
    background: #06b6d4;
    vertical-align: middle;
    margin-left: 4px;
    animation: blink 1s step-end infinite;
  }
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }
</style>

<div align="center">
  <div class="terminal-box">
    <span class="prompt">dhanush@developer:~$</span> <span class="cmd">whoami</span><br>
    <span class="output">> Dhanush M</span><br>
    <span class="output">> Full Stack Developer</span><br>
    <span class="output">> UI/UX Enthusiast</span><br>
    <span class="output">> AI Explorer</span><br>
    <br>
    <span class="prompt">dhanush@developer:~$</span> <span class="cmd">status</span><br>
    <span class="output">[████████████████████████████████████████] 100%</span><br>
    <span class="output">✓ Learning</span><br>
    <span class="output">✓ Building</span><br>
    <span class="output">✓ Experimenting</span><br>
    <span class="output">✓ Creating</span><br>
    <br>
    <span class="prompt">dhanush@developer:~$</span> <span class="cmd">npm run build-future</span> <span style="color:#facc15;">🚀</span><span class="cursor"></span>
  </div>
</div>

---

<!-- ========================= QUOTE ========================= -->

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" style="border-radius:1rem;"/>
</div>

---

<!-- ========================= CONNECT ========================= -->

<h2 align="center">🌐 LET'S CONNECT</h2>

<div align="center" class="social-links">
  <a href="https://dhanush1374949.github.io/Morden-portfolio/"><img src="https://img.shields.io/badge/PORTFOLIO-00D9FF?style=for-the-badge&logo=firefox&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/dhanush-m-970136325/"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.behance.net/dhanushmurugan2596"><img src="https://img.shields.io/badge/BEHANCE-1769FF?style=for-the-badge&logo=behance&logoColor=white"/></a>
  <a href="mailto:dhanushmurugan3075@gmail.com"><img src="https://img.shields.io/badge/GMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</div>

<br>

<div align="center">
  <h3>✨ BUILDING THE FUTURE, ONE LINE OF CODE AT A TIME.</h3>
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&size=18&duration=3000&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Code+%E2%9A%A1+Design+%F0%9F%8E%A8+AI+%F0%9F%A4%96+Innovation+%F0%9F%9A%80;Think+Different.;Build+Better.;Keep+Learning."/>
</div>

<!-- ========================= END ========================= -->
