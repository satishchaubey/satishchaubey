<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: Arial, sans-serif; background: transparent; color: #111; }
  .container { max-width: 900px; margin: 0 auto; padding: 1.5rem 1rem; }

  .hero { text-align: center; padding: 2rem 1rem; }
  .hero h1 { font-size: 30px; margin-bottom: 0.5rem; }
  .hero h2 { font-size: 16px; color: #555; margin-bottom: 1rem; }

  .tags { display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; margin-top: 10px; }
  .tag { padding: 5px 12px; border-radius: 20px; font-size: 12px; border: 1px solid #ddd; }

  .section { margin: 2rem 0; }
  .section h3 { margin-bottom: 1rem; font-size: 14px; text-transform: uppercase; color: #666; }

  .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px,1fr)); gap: 12px; }

  .card { border: 1px solid #eee; border-radius: 10px; padding: 1rem; }
  .card h4 { margin-bottom: 6px; }
  .card p { font-size: 13px; color: #555; }

  .flow { background: #f7f7f7; padding: 1rem; border-radius: 10px; font-size: 13px; }

  .stack { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px,1fr)); gap: 10px; }
  .stack div { border: 1px solid #eee; padding: 8px; border-radius: 8px; font-size: 13px; }

  .connect a { margin-right: 10px; text-decoration: none; font-size: 13px; }
</style>

<div class="container">

  <!-- HERO -->
  <div class="hero">
    <h1>Hi 👋, I'm Satish Kumar Chaubey</h1>
    <h2>🚀 AI Engineer | Full Stack Developer | Real-Time Systems Builder</h2>

    <div class="tags">
      <span class="tag">LLMs + Agents</span>
      <span class="tag">Voice AI</span>
      <span class="tag">WebRTC</span>
      <span class="tag">Next.js</span>
      <span class="tag">NestJS</span>
      <span class="tag">FastAPI</span>
      <span class="tag">Redis</span>
      <span class="tag">PostgreSQL</span>
      <span class="tag">Shopify</span>
      <span class="tag">WordPress</span>
    </div>
  </div>

  <!-- ABOUT -->
  <div class="section">
    <h3>About Me</h3>
    <p>
      I build <b>production-grade AI systems</b>, real-time applications, and scalable backend architectures.
      Currently focused on LLM pipelines, voice AI, and high-performance systems using FastAPI and NestJS.
    </p>
  </div>

  <!-- PROJECTS -->
  <div class="section">
    <h3>Featured Projects</h3>

    <div class="grid">
      <div class="card">
        <h4>🎙 AI Voice Assistant</h4>
        <p>Real-time conversational AI with streaming STT → LLM → TTS pipeline using FastAPI, WebRTC, and Twilio.</p>
      </div>

      <div class="card">
        <h4>✉️ LLM Email Automation</h4>
        <p>Automation engine with prompt chaining, decision routing, and context-aware responses.</p>
      </div>

      <div class="card">
        <h4>🏗 Scalable Backend Systems</h4>
        <p>Microservices architecture using NestJS, Redis queues, and multi-database systems.</p>
      </div>
    </div>
  </div>

  <!-- SYSTEM DESIGN -->
  <div class="section">
    <h3>LLM Pipeline</h3>
    <div class="flow">
      User → API (FastAPI/NestJS) → Preprocessing → LLM → Post-processing → Response
    </div>
  </div>

  <div class="section">
    <h3>Voice AI Flow</h3>
    <div class="flow">
      User Speech → Twilio/WebRTC → STT → LLM → TTS → Audio Response
    </div>
  </div>

  <!-- TECH STACK -->
  <div class="section">
    <h3>Tech Stack</h3>

    <div class="stack">
      <div>Frontend: React, Next.js, Tailwind</div>
      <div>Backend: Node.js, NestJS, FastAPI</div>
      <div>AI: Gemini, GPT, Claude</div>
      <div>Infra: Docker, Redis, BullMQ</div>
      <div>DB: PostgreSQL, MongoDB</div>
    </div>
  </div>

  <!-- CMS -->
  <div class="section">
    <h3>E-commerce & CMS</h3>

    <div class="stack">
      <div>Shopify (Store + Customization)</div>
      <div>WordPress (Themes + Plugins)</div>
    </div>
  </div>

  <!-- IMPACT -->
  <div class="section">
    <h3>Impact</h3>
    <ul>
      <li>Built low-latency real-time AI systems</li>
      <li>Designed scalable backend architectures</li>
      <li>Developed LLM-powered automation workflows</li>
    </ul>
  </div>

  <!-- CONNECT -->
  <div class="section connect">
    <h3>Connect</h3>
    <a href="https://linkedin.com/in/satish-chaubey/">LinkedIn</a>
    <a href="https://github.com/satishchaubey">GitHub</a>
    <a href="mailto:satishchaubey02@gmail.com">Email</a>
  </div>

</div>
