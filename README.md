<div align="center">

# Shahrukh Baloch
### CS Student · AI Engineer · Builder

*"I don't just study AI — I ship it."*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=6E40C9&center=true&vCenter=true&width=500&lines=RAG+%26+LLM+Engineer;IoT+%2B+AI+Systems+Builder;Full-Stack+Developer;Microsoft+Learn+Student+Ambassador)](https://git.io/typing-svg)

</div>

---

<div align="center">

![Sukkur IBA](https://img.shields.io/badge/🎓_Sukkur_IBA-Computer_Science-1a1a2e?style=flat-square)
![Year](https://img.shields.io/badge/3rd_Year-2026-6E40C9?style=flat-square)
![MLSA](https://img.shields.io/badge/Microsoft-MLSA-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![FlyRank](https://img.shields.io/badge/FlyRank-ML_Track_2026-8B5CF6?style=flat-square)
![Status](https://img.shields.io/badge/🟢_Open_To-Remote_Internships-22c55e?style=flat-square)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shahrukh-baloch-bb73a632a/)
[![Email](https://img.shields.io/badge/Email-shahrukhbaloch648@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shahrukhbaloch648@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Shahrukh--aidev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shahrukh-aidev)

</div>

---

## 🧠 Who Am I

I'm a **3rd-year CS student at Sukkur IBA University** and a **Microsoft Learn Student Ambassador** building production-grade AI systems — not just notebook experiments.

My work spans **RAG pipelines**, **IoT + AI integration**, and **full-stack platforms** — each project deployed, documented, and built to solve real problems for real people in Pakistan and beyond.

> Currently accepted into **FlyRank AI's ML Track (July 2026 cohort)** and actively building toward advanced ML research.

---

## 🚀 Featured Projects

---

### ⚖️ HAQ (حق) — Pakistani Legal AI Assistant
> *Democratizing legal knowledge for 220 million Pakistanis*

[![HuggingFace](https://img.shields.io/badge/🤗_Live_Demo-HuggingFace_Spaces-FFD21E?style=flat-square)](https://huggingface.co/spaces/Shahrukh350/Advocate-AI)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/Shahrukh-aidev)
[![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square)](https://github.com/Shahrukh-aidev)
[![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-13aa52?style=flat-square)](https://github.com/Shahrukh-aidev)
[![Groq](https://img.shields.io/badge/Groq-Llama_3-F55036?style=flat-square)](https://github.com/Shahrukh-aidev)

**The problem:** Most Pakistanis can't afford a lawyer. Legal documents are dense, in English, and inaccessible.

**What I built:** A bilingual (Urdu + English) RAG-based legal AI covering **4,000+ law chunks across 80+ Pakistan Acts** with source verification links and custom anti-hallucination prompting.

| Component | Technology |
|-----------|-----------|
| Embeddings | Cohere multilingual |
| Vector Store | Pinecone |
| LLM | Groq-hosted Llama 3 |
| Pipeline | LangChain RAG |
| UI | Gradio on HuggingFace Spaces |
| Anti-hallucination | Custom prompt engineering + source linking |

→ **[View Repository](https://github.com/Shahrukh-aidev)**

---

### 🦺 IRIS Jacket — AI Navigation System for the Deaf-Blind
> *A sixth sense for 285 million visually impaired people worldwide*

[![Arduino](https://img.shields.io/badge/ESP32-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)](https://github.com/Shahrukh-aidev/IRIS_Jacket_A-Deaf-Blind-Navigation-System)
[![Azure](https://img.shields.io/badge/Azure-Computer_Vision-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://github.com/Shahrukh-aidev/IRIS_Jacket_A-Deaf-Blind-Navigation-System)
[![Python](https://img.shields.io/badge/Raspberry_Pi-Python-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)](https://github.com/Shahrukh-aidev/IRIS_Jacket_A-Deaf-Blind-Navigation-System)

**The problem:** White canes can't detect chest-height obstacles or identify what an obstacle *is*. 285 million people live with this limitation every day.

**What I built:** A wearable jacket with 7 vibration motors, 3 ultrasonic sensors, a Raspberry Pi, and Azure AI Vision — giving users haptic feedback *before* contact with any obstacle.

**Key engineering decisions:**

- **Trigonometric motor model** — PWM intensity computed via vector projection math, not simple on/off switching. Each motor has a fixed angular orientation θ; intensity scales based on both center and side distances simultaneously.
- **Kick-start mechanism** — 50ms full-power burst overcomes ERM static friction before settling to proportional intensity.
- **mDNS device discovery** — No hardcoded IPs. ESP32 advertises as `esp32.local`; Pi finds it automatically on any network.
- **UDP over MQTT** — ~1ms latency vs ~50ms for MQTT. For haptics, speed beats reliability.
- **Azure dual-pipeline** — Object detection + scene description every 3 seconds. Objects under 50% confidence discarded. 3-zone frame analysis (left/center/right) maps directly to motor zones.

```
PWM = 255 - (255 × side × center) / √(center²·cos²θ + side²·sin²θ)
```

→ **[View Repository](https://github.com/Shahrukh-aidev/IRIS_Jacket_A-Deaf-Blind-Navigation-System)**

---

### 📊 Interactive Derivative Visualizer
> *Making calculus actually make sense — animated, real-time, intuitive*

[![Python](https://img.shields.io/badge/Python-Matplotlib-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/Shahrukh-aidev/interactive-derivative-visualizer)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square)](https://github.com/Shahrukh-aidev/interactive-derivative-visualizer)

A Python + Matplotlib tool that animates any function alongside its derivative in real time — with a live tangent line, moving point, dark/light mode, and keyboard controls. Built for students, educators, and anyone who wants calculus to click visually.

**Features:** Smooth animation · Tangent line tracking · Speed/domain/resolution controls · Dark/light toggle · Keyboard shortcuts

→ **[View Repository](https://github.com/Shahrukh-aidev/interactive-derivative-visualizer)**

---

### 🛡️ VerifyIntern — AI Fraud Detection for Job Offers
> *Protecting students from fake internship scams using Google Gemini*

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Shahrukh-aidev)
[![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=flat-square&logo=google&logoColor=white)](https://github.com/Shahrukh-aidev)

Real-time trust scores and red-flag analysis on job/internship offers — with verified career alternatives.

---

### ♟️ Chess-Game — Full AI Chess Engine
> *Offline multiplayer + 5-level AI powered by Stockfish*

[![JavaScript](https://img.shields.io/badge/HTML/CSS/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://github.com/Shahrukh-aidev/Chess-Game)

Browser-based chess with smooth UI, sound effects, and AI difficulty levels 1–5 via the Stockfish REST API.

→ **[View Repository](https://github.com/Shahrukh-aidev/Chess-Game)**

---

### 🎬 Downlynk — Multi-Platform Video Downloader

[![Python](https://img.shields.io/badge/Flask-Python-000000?style=flat-square&logo=flask&logoColor=white)](https://downlynkfrontend.vercel.app/)
[![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=flat-square&logo=react&logoColor=black)](https://downlynkfrontend.vercel.app/)

Java desktop app + Flask/React web platform deployed on Railway + Vercel.

---

## 🛠️ Tech Stack

### AI / ML Engineering
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-LLM_Inference-F55036?style=flat-square)
![Cohere](https://img.shields.io/badge/Cohere-Embeddings-1E293B?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-13aa52?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Spaces-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Azure AI](https://img.shields.io/badge/Azure-Computer_Vision-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

### Web & Backend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

### IoT & Hardware
![ESP32](https://img.shields.io/badge/ESP32-Arduino_C++-00979D?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-Python-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)

### Databases & Cloud
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_Store-13aa52?style=flat-square)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Shahrukh-aidev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shahrukh-aidev&layout=compact&theme=tokyonight&hide_border=true" width="48%" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Shahrukh-aidev&theme=tokyonight&hide_border=true" width="65%" />

</div>

---

<div align="center">

*3rd-year CS student from Sukkur, Pakistan — building AI that matters.*
**Open to remote internships and AI/ML roles.**
[shahrukhbaloch648@gmail.com](mailto:shahrukhbaloch648@gmail.com)

</div>
