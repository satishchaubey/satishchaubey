<div align="center">

  <!-- Visual Hero Banner (Native Vector SVG) -->
  <a href="https://satishchaubey.vercel.app" target="_blank">
    <img src="./banner.svg" alt="Satish Kumar Chaubey - AI & ML Engineer" width="100%" />
  </a>

  <br/><br/>

  <!-- Dynamic Typing Subtitle -->
  <a href="https://satishchaubey.vercel.app" target="_blank">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=650&height=45&lines=AI+%26+ML+Engineer+%E2%9A%A1+LLM+Specialist;Building+Real-Time+Voice+AI+(WebRTC+%2B+Twilio);Full-Stack+%26+Microservices+Architect;High-Performance+Scalable+Architectures" alt="Typing SVG" />
  </a>

  <p align="center">
    <strong>Production-grade AI systems • Real-time voice intelligence • High-throughput fintech microservices</strong>
  </p>

  <!-- Quick Action Badges -->
  <p align="center">
    <a href="https://satishchaubey.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-satishchaubey.vercel.app-00D2FF?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
    </a>
    &nbsp;
    <a href="https://linkedin.com/in/satish-chaubey" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Satish_Chaubey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;
    <a href="mailto:satishchaubey02@gmail.com">
      <img src="https://img.shields.io/badge/Email-satishchaubey02@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    &nbsp;
    <a href="https://github.com/satishchaubey">
      <img src="https://img.shields.io/badge/GitHub-satishchaubey-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Status-Open_for_Opportunities-success?style=flat-square&logo=github" alt="Status" />
    &nbsp;
    <img src="https://img.shields.io/badge/Experience-3%2B_Years-blue?style=flat-square" alt="Experience" />
    &nbsp;
    <img src="https://img.shields.io/badge/Location-Ghaziabad_%2F_Noida%2C_India-orange?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  </p>

</div>

<div align="center">
  <!-- Animated Developer with Floating Tech Stack -->
  <img src="./developer.svg" alt="Satish Kumar Chaubey - AI & Systems Developer" width="100%" />
</div>

---

### 👨‍💻 Executive Summary

I am an **AI & ML Engineer and Full Stack Architect** with **3+ years of production experience** delivering enterprise web applications, real-time voice workflows, and high-throughput backend services.

- 🔭 **Current Position**: Software Engineer at **Plutos One Pvt. Ltd.** (Feb 2024 – Present).
- 🧠 **AI & LLM Workflows**: Designing multi-agent pipelines, prompt chaining, automated call monitoring, and intelligent conversational agents (*Visa Chatbot*, *CSC Chatbot*).
- 🎙️ **Real-Time Voice Systems**: Engineering low-latency voice pipelines with **FastAPI, WebRTC, Twilio, Whisper (STT), and TTS**.
- ⚡ **Scale & Performance**: Architected high-availability services for the CSC Bill Payment Platform with substantial throughput optimizations via Redis caching and microservices tuning.
- 💳 **Fintech & Banking**: Hands-on with **Central Bank of India (Saarthi)**, **SVC Bill Pay Platform**, and secure payment integrations (**PayU, Razorpay**).
- 🌐 **Frontend Excellence**: Architected 30+ responsive, production-ready enterprise pages using **Next.js (App & Page Router)**, **React.js**, **TypeScript**, and **Tailwind CSS**.

---

### 📐 Production System Architecture & Project Charts

Detailed architectural flow diagrams for production AI systems and scalable enterprise platforms directly from my portfolio ([satishchaubey.vercel.app](https://satishchaubey.vercel.app)):

<details open>
<summary><strong>🎙️ 1. Gemini Live API — Real-Time Multimodal Voice, Video &amp; Audio Streaming Engine</strong></summary>
<br/>
<blockquote>Architected low-latency streaming pipeline enabling continuous bi-directional voice, video, and text interaction with Multimodal AI models. Features real-time PCM audio processing, dynamic interruption handling, function calling, and live audio synthesis.</blockquote>

```mermaid
graph TD
    subgraph ClientLayer["1. Multimodal Client Layer"]
        A1["Text Prompts & User Interrupts"]
        A2["Live Audio Input (PCM Stream)"]
        A3["Live Video Input"]
    end

    subgraph TransportLayer["2. Real-Time Communication Layer"]
        B1["Secure Session Authentication"]
        B2["Bi-directional WebSockets"]
        B3["Low-Latency Interruption Handler"]
    end

    subgraph CoreEngine["3. Multimodal AI Orchestration"]
        C1["Real-Time Multimodal AI (Gemini Live)"]
        C2["Context & Conversation Engine"]
        C3["Tool & Function Calling Engine"]
        C4["External Information Retrieval"]
    end

    subgraph ResponseSynthesis["4. Client Output & Audio Stream"]
        D1["Dynamic Tool Result Display"]
        D2["Real-Time Audio Synthesis (TTS)"]
        D3["Instant Interruption Flushing"]
    end

    A1 --> B1
    A2 --> B2
    A3 --> B2
    B1 --> C1
    B2 <--> C1
    B3 --> C1
    C1 <--> C2
    C1 <--> C3
    C3 <--> C4
    C1 --> D1
    C1 --> D2
```

</details>

<details>
<summary><strong>🚨 2. AI Incident Monitoring, Call Analysis &amp; RCA Platform</strong></summary>
<br/>
<blockquote>Distributed event processing and RAG pipeline for monitoring telecommunication metrics, analyzing call logs with LLMs, and triggering automated omnichannel incident escalations.</blockquote>

```mermaid
graph TD
    subgraph IngestionLayer["1. Data Ingestion"]
        M1["Alert Webhooks"]
        M2["Metrics & Monitoring Data"]
        M3["Application & Call Logs"]
    end

    subgraph MessagingLayer["2. Event Processing"]
        K1["Distributed Event Stream (Kafka / RabbitMQ)"]
        K2["Queue & Worker Processing (BullMQ)"]
    end

    subgraph Microservices["3. Backend & AI Platform"]
        G1["API Gateway"]
        I1["Incident Management Service"]
        R1["AI / RAG Service"]
        V1["Vector Database"]
        C1["Redis Caching Layer"]
        L1["LLM Reasoning Service"]
    end

    subgraph EscalationLayer["4. Notification Layer"]
        N1["Voice Notifications (Twilio)"]
        N2["Messaging Notifications (WhatsApp)"]
        N3["Email Notifications (SMTP)"]
        N4["Team Collaboration Alerts (Slack)"]
    end

    M1 --> K1
    M2 --> K1
    M3 --> K1
    K1 --> K2
    K2 --> G1
    G1 --> I1
    I1 <--> R1
    R1 <--> V1
    R1 <--> C1
    R1 <--> L1
    I1 --> N1
    I1 --> N2
    I1 --> N3
    I1 --> N4
```

</details>

<details>
<summary><strong>🛡️ 3. Enterprise Microservices Core &amp; High-Throughput API Gateway</strong></summary>
<br/>
<blockquote>High-performance API Gateway routing requests with security headers, RBAC auth guards, rate limiting, and real-time load balancing to downstream services.</blockquote>

```mermaid
graph TD
    subgraph Clients["1. Client Access Layer"]
        C1["Client Applications & Monitoring Webhooks"]
    end

    subgraph GatewayCore["2. API Gateway"]
        G1["Security & Header Sanitizer"]
        G2["Auth Guard & RBAC"]
        G3["Rate Limiter & Throttler"]
        G4["Real-Time Event Hub"]
        G5["Path Router & Load Balancer"]
    end

    subgraph Downstream["3. Microservices Core"]
        D1["Incident Management Service"]
        D2["AI Analysis Service"]
        D3["Knowledge Base Service"]
        D4["Service Health Verification"]
    end

    C1 --> G1
    G1 --> G2
    G2 --> G3
    G3 --> G5
    G2 <--> G4
    G5 --> D1
    G5 --> D2
    G5 --> D3
    G5 --> D4
```

</details>

<details>
<summary><strong>📄 4. Document Ingestion &amp; Asynchronous RAG Root Cause Analysis (RCA) Pipeline</strong></summary>
<br/>
<blockquote>End-to-end multimodal document ingestion and vector search workflow for extracting structured insights, text chunks, and root cause resolution steps.</blockquote>

```mermaid
graph TD
    subgraph Extraction["1. Document Ingestion"]
        D1["PDF / Word / Text Documents"]
        D2["Images & Screenshots"]
        D3["Event-Based Task Processing"]
    end

    subgraph RAGWorker["2. RAG Processing Pipeline"]
        W1["Asynchronous Document Processing"]
        W2["Text Extraction & Chunking"]
        W3["Redis Caching Layer"]
        W4["Vector Database (Chroma / Pinecone)"]
    end

    subgraph GeminiRCA["3. AI Analysis & RCA"]
        G1["Multimodal LLM (Gemini / GPT)"]
        G2["Context-Aware Prompting"]
        G3["Root Cause Analysis & Resolution Steps"]
    end

    D1 --> D3
    D2 --> D3
    D3 --> W1
    W1 --> W2
    W2 <--> W3
    W2 <--> W4
    W4 <--> G1
    G1 --> G2
    G2 --> G3
```

</details>

<details>
<summary><strong>💬 5. Multi-Country WhatsApp Cloud API &amp; Conversational AI Bot</strong></summary>
<br/>
<blockquote>Production WhatsApp bot architecture with HMAC signature verification, Redis queue buffering, NLP intent classification, and automated customer query resolution.</blockquote>

```mermaid
graph TD
    subgraph WhatsAppClient["1. WhatsApp User Interface"]
        U1["WhatsApp Mobile & Web App"]
        U2["Interactive Quick-Reply Buttons"]
    end

    subgraph WebhookGateway["2. Webhook Ingestion & Auth"]
        W1["Express Webhook Handler"]
        W2["HMAC Signature Verification"]
        W3["Redis Message Queue"]
    end

    subgraph BotEngine["3. Conversational Router & NLP"]
        R1["Message Intent Classifier"]
        R2["Session State & Context Manager"]
        R3["Catalog & FAQ Resolution Search"]
    end

    subgraph ServiceIntegration["4. Backend & Fulfillment"]
        D1["Order Fulfillment Service"]
        D2["Customer CRM Database"]
        D3["Live Support Agent Handover"]
    end

    U1 --> W1
    U2 --> W1
    W1 --> W2
    W2 --> W3
    W3 --> R1
    R1 <--> R2
    R1 --> R3
    R3 <--> D1
    R3 <--> D2
    R1 --> D3
```

</details>

---

### 🛠️ Tech Stack & Ecosystem

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **🤖 AI / ML & Real-Time Voice** | `LLM Integration (Gemini, GPT, Claude)` • `LangChain` • `Prompt Engineering` • `Whisper (STT)` • `ElevenLabs (TTS)` • `WebRTC` • `Twilio` • `AI Call Analysis` |
| **⚡ Frontend Engineering** | `Next.js (App & Page Router)` • `React.js` • `TypeScript` • `JavaScript (ES6+)` • `Redux Toolkit` • `Tailwind CSS` • `ShadCN UI` • `Radix UI` • `SCSS` • `Vite` |
| **🏗️ Backend & Microservices** | `FastAPI` • `Node.js` • `Express.js` • `NestJS` • `RESTful API Architecture` • `Microservices` • `WebSockets` • `BullMQ` |
| **🗄️ Databases & Caching** | `MongoDB` • `MySQL` • `PostgreSQL` • `Redis (Caching & Queue Management)` |
| **☁️ Cloud & DevOps** | `Google Cloud Platform (GCP)` • `AWS (EC2, S3)` • `Docker` • `Git` • `GitHub Actions` • `Postman` • `VS Code` |
| **💳 Fintech & Integrations** | `PayU` • `Razorpay` • `Web3 / BSC Smart Contract Integration` • `Decentralized Wallet Workflows` |

<br/>

<!-- Modern Icon Grid -->
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,nodejs,express,nestjs,fastapi,redis&perline=10" alt="Tech Stack Line 1" /><br/>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,tailwind,redux,gcp,aws,docker,git,postman&perline=10" alt="Tech Stack Line 2" />
</p>

</div>

---

### 🚀 Key Production & AI Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>✉️ SheetSync — Interactive Lead &amp; Bulk Mailer Suite</h3>
      <p>Production email outreach and lead automation suite built for high deliverability and multi-account campaign management.</p>
      <ul>
        <li>Batch raw email parsing, <strong>Fresh Outreach vs Follow-Up modes</strong>, and live SMTP delivery logging.</li>
        <li>Automated Gmail drafts sync and personalized PDF attachments pipeline.</li>
        <li>Built with high-responsiveness using <strong>Next.js 16, React 19, and Nodemailer</strong>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js%2016-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black" />
        <img src="https://img.shields.io/badge/SMTP-EA4335?style=flat-square&logo=gmail&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>💳 Enterprise BBPS Payment SaaS Platform</h3>
      <p>High-scale AI SaaS and BBPS bill payments engine integrated with payment gateways, analytics, and campaign dashboards.</p>
      <ul>
        <li>Engineered reliable payment flows with <strong>PayU &amp; Razorpay</strong> and real-time webhook reconciliation.</li>
        <li>Designed high-concurrency client campaign analytics and bill payment tracking dashboards.</li>
        <li>Built with <strong>Next.js 16, React.js, and BBPS APIs</strong>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/BBPS-0052CC?style=flat-square" />
        <img src="https://img.shields.io/badge/PayU-1B98E0?style=flat-square" />
        <img src="https://img.shields.io/badge/Razorpay-0C2340?style=flat-square&logo=razorpay&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎙️ AI Voice Assistant &amp; Call Insights</h3>
      <p>Real-time voice intelligence pipeline powering low-latency bi-directional voice agents and automated call workflows.</p>
      <ul>
        <li>Sub-second end-to-end voice latency using <strong>FastAPI, WebRTC, Twilio, STT &amp; TTS</strong>.</li>
        <li>Automated root cause analysis and sentiment scoring via LLM-based post-call processing.</li>
        <li>Dynamic prompt chaining for structured task completion and CRM syncing.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white" />
        <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🌍 Multi-Country Visa &amp; CSC AI Chatbots</h3>
      <p>Enterprise AI conversational assistants deployed across multiple countries and the nationwide CSC network.</p>
      <ul>
        <li>Provides instant query resolution for international visa requirements and government bill services.</li>
        <li>High-accuracy contextual retrieval using structured knowledge schemas.</li>
        <li>Substantially slashed manual ticket resolution times across thousands of daily user interactions.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/LLM%20Workflows-FF6F00?style=flat-square&logo=openai&logoColor=white" />
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 CSC &amp; SVC Bill Payment Platforms</h3>
      <p>Mission-critical fintech infrastructure powering nationwide utility bill payment workflows.</p>
      <ul>
        <li>Engineered full-stack services using <strong>Node.js, Express, MongoDB, and Redis</strong>.</li>
        <li>Achieved substantial throughput optimization using Redis query caching, connection pooling, and payload compression.</li>
        <li>Bulletproof payment integrations with <strong>PayU and Razorpay</strong> with robust webhook reconciliation.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
        <img src="https://img.shields.io/badge/Microservices-0052CC?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏦 Saarthi – Central Bank of India Platform</h3>
      <p>Next-generation digital banking platform engineered for maximum security, compliance, and seamless customer onboarding.</p>
      <ul>
        <li>Architected mission-critical financial web journeys with <strong>Next.js, React, and TypeScript</strong>.</li>
        <li>Strict adherence to banking grade UI state management, accessibility, and zero-trust data security.</li>
        <li>Cross-functional collaboration with core banking backend and security audit teams.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Fintech-00C49F?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>✈️ Best Sky Fare (<a href="https://bestskyfare.com" target="_blank">bestskyfare.com</a>)</h3>
      <p>Comprehensive travel booking engine featuring live search, booking workflows, and responsive travel management.</p>
      <ul>
        <li>Modern, responsive frontend built with <strong>Next.js and Tailwind CSS</strong>.</li>
        <li>High-speed flight aggregation and booking workflows backed by <strong>FastAPI</strong> services.</li>
        <li>Optimized for SEO, core web vitals, and instant mobile load speeds.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔗 Web3 &amp; Bound Finance Systems</h3>
      <p>Decentralized finance frontend modules and smart contract wallet integrations.</p>
      <ul>
        <li>Integrated non-custodial wallet connectors (MetaMask, WalletConnect) with BSC contracts.</li>
        <li>Built real-time transaction event listeners and state synchronization engines.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Web3-F16822?style=flat-square&logo=web3dotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
        <img src="https://img.shields.io/badge/BSC-F0B90B?style=flat-square&logo=binance&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

### 💼 Career Milestones & Engineering Impact

```mermaid
timeline
    title Professional Journey & Engineering Evolution
    2022 - 2023 : Techpile Technology Pvt. Ltd. : MERN Stack Intern : Full stack development with MongoDB, Express, React, Node.js
    2023 - 2024 : Speqto Technology Pvt. Ltd. : Front-End Developer : Next.js, React, Web3 & BSC Smart Contract Wallet Integrations
    2024 - Present : Plutos One Pvt. Ltd. : Software Engineer (AI & Full Stack) : Production LLM Chatbots, Real-time Voice AI, CSC Bill Pay, Central Bank Saarthi
```

---

### 📊 GitHub Activity & Statistics

<div align="center">

  <table border="0" style="border: none; background: transparent;">
    <tr style="border: none; background: transparent;">
      <td align="center" style="border: none; padding: 10px;">
        <a href="https://github.com/satishchaubey">
          <img height="185em" src="https://github-readme-stats.vercel.app/api?username=satishchaubey&show_icons=true&hide_border=true&hide_rank=true&bg_color=0d1117&title_color=58a6ff&icon_color=38bdf8&text_color=c9d1d9" alt="Satish's GitHub Stats" />
        </a>
      </td>
      <td align="center" style="border: none; padding: 10px;">
        <a href="https://github.com/satishchaubey">
          <img height="185em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=satishchaubey&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top Languages" />
        </a>
      </td>
    </tr>
  </table>

</div>

---

### 🤝 Let's Connect & Collaborate

<div align="center">

  <!-- Connect Call-to-Action Banner -->
  <a href="mailto:satishchaubey02@gmail.com">
    <img src="./footer.svg" alt="Let's Connect Banner" width="100%" />
  </a>

  <br/><br/>

  <!-- Clean 4-Column Interactive Contact Grid -->
  <table border="0" style="border: none; width: 100%; max-width: 850px;">
    <tr align="center" style="border: none;">
      <td width="25%" style="padding: 16px; border: 1px solid #30363d; border-radius: 8px;">
        <a href="https://linkedin.com/in/satish-chaubey" target="_blank">
          <img src="https://skillicons.dev/icons?i=linkedin" width="44" height="44" alt="LinkedIn" /><br/><br/>
          <strong>LinkedIn</strong><br/>
          <sub style="color: #8b949e;">Career &amp; Network</sub><br/><br/>
          <img src="https://img.shields.io/badge/Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
        </a>
      </td>
      <td width="25%" style="padding: 16px; border: 1px solid #30363d; border-radius: 8px;">
        <a href="https://satishchaubey.vercel.app" target="_blank">
          <img src="https://skillicons.dev/icons?i=vercel" width="44" height="44" alt="Portfolio" /><br/><br/>
          <strong>Portfolio</strong><br/>
          <sub style="color: #8b949e;">Live Demos &amp; Work</sub><br/><br/>
          <img src="https://img.shields.io/badge/Visit_Site-000000?style=flat-square&logo=vercel&logoColor=white" alt="Visit Portfolio" />
        </a>
      </td>
      <td width="25%" style="padding: 16px; border: 1px solid #30363d; border-radius: 8px;">
        <a href="mailto:satishchaubey02@gmail.com">
          <img src="https://skillicons.dev/icons?i=gmail" width="44" height="44" alt="Email" /><br/><br/>
          <strong>Direct Email</strong><br/>
          <sub style="color: #8b949e;">Opportunities &amp; Chat</sub><br/><br/>
          <img src="https://img.shields.io/badge/Send_Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Send Email" />
        </a>
      </td>
      <td width="25%" style="padding: 16px; border: 1px solid #30363d; border-radius: 8px;">
        <a href="https://github.com/satishchaubey">
          <img src="https://skillicons.dev/icons?i=github" width="44" height="44" alt="GitHub" /><br/><br/>
          <strong>GitHub</strong><br/>
          <sub style="color: #8b949e;">Repos &amp; Open Source</sub><br/><br/>
          <img src="https://img.shields.io/badge/Follow-181717?style=flat-square&logo=github&logoColor=white" alt="Follow on GitHub" />
        </a>
      </td>
    </tr>
  </table>

  <br/>

  <sub>⚡ <i>"Building resilient, low-latency architectures that bridge cutting-edge AI models with production-grade reliability."</i></sub>

</div>
