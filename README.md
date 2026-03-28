<div align="center">

# 👋 Hey, I'm Sita Ram Saini

### Senior Data Scientist · AI/ML Engineer · IIT Kharagpur M.Tech

*Building production-grade AI systems for one of India's largest logistics networks*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srs02/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SRSaini)
[![Location](https://img.shields.io/badge/📍_Pune,_India-FF6B35?style=for-the-badge)](https://github.com/SRSaini)

</div>

---

## 🧠 About Me

I'm a Senior Data Scientist at **XpressBees** — one of India's fastest-growing logistics companies — where I own the full ML stack from GPU infrastructure to production deployment. My work sits at the intersection of **Vision-Language Models**, **NLP**, and **Voice AI**, solving real-world logistics challenges at scale.

- 🔬 **Researcher turned Engineer** — M.Tech from **IIT Kharagpur**
- 🏗️ I build and ship **end-to-end ML systems**: from dataset curation → fine-tuning → inference APIs → production
- 🚀 Currently pushing VLMs into logistics verification, address intelligence, and conversational AI
- 🛸 Exploring the **drone & swarm robotics** space as a future venture

---

## ⚙️ Tech Stack

### 🤖 AI / ML / Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![LoRA/PEFT](https://img.shields.io/badge/LoRA%2FPEFT-8A2BE2?style=flat-square)
![Unsloth](https://img.shields.io/badge/Unsloth-FF6B35?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

### 👁️ Vision & VLMs
![InternVL](https://img.shields.io/badge/InternVL2.5%2F3-00B4D8?style=flat-square)
![Qwen-VL](https://img.shields.io/badge/Qwen3--VL-4CAF50?style=flat-square)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

### 📝 NLP & Speech
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white)
![SentencePiece](https://img.shields.io/badge/SentencePiece-FF9800?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21F?style=flat-square&logo=huggingface&logoColor=black)

### 🛠️ Infra & Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![NVIDIA CUDA](https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### 🤝 LLM Providers Integrated
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4B483?style=flat-square)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Sarvam AI](https://img.shields.io/badge/Sarvam_AI-138808?style=flat-square)

---

## 🔭 What I'm Working On

### 📦 RVP — Reverse Pickup Verification (XpressBees)
> *AI-powered quality gate for reverse logistics at national scale*

- Built a **two-stage async inference pipeline** using **InternVL2.5** for real-time product image verification
- Fine-tuned **InternVL3** (LoRA + DeepSpeed ZeRO) and **Qwen3-VL** (via Unsloth) on proprietary logistics data
- Designed a **dual-model FastAPI** system supporting hot-switch between VLMs at runtime
- Built a browser-based **JSONL dataset editor** for ShareGPT-format annotation workflows
- Added an `image_quality` module with compression artifact detection and auto-enhancement

### 🗺️ Indian Address Intelligence
> *Seq2Seq transformer for parsing chaotic Indian delivery addresses*

- Custom **34M parameter seq2seq transformer** with **SentencePiece BPE** tokenizer
- Geo-aware address parsing: BPE vocabulary extended with **coordinate tokens** for lat/long prediction
- **Address NER pipeline** (spaCy) across 2,174+ Pune delivery records with span-level offset alignment
- Offline **ensemble geocoder** combining ML strategies for pin-to-coordinate resolution

### 🎙️ Voice Agent — Logistics IVR (XpressBees)
> *Multilingual conversational AI for last-mile delivery support*

- End-to-end **IVR pipeline** with FastAPI + WebSocket, handling 23 distinct call intents
- **Hinglish** (Hindi-English) support with a trilingual Q&A playbook
- LangChain-based **LLM provider abstraction** across OpenAI, Groq, Anthropic, Sarvam & more
- Modular provider switching with zero downtime

### 📄 POD — Proof of Delivery Analysis
> *Multi-class document intelligence for delivery verification*

- **YOLOv8** multi-class detection: signature, stamp, AWB, barcode, remark regions
- **OCR-based readability scoring** with structured JSON prompt engineering for VLM verification
- End-to-end document pipeline: detection → OCR → LLM reasoning → verdict

---

## 🏗️ System Design Patterns I Live By

```
📸 Raw Input
    ↓
🔍 Image Quality Check (artifacts, blur, exposure)
    ↓
🤖 Dual-VLM Inference API (InternVL3 ↔ Qwen3-VL hot-swap)
    ↓
📊 Structured Output (JSON verdict + confidence)
    ↓
🚀 Async FastAPI → Production
```

---

## 🚀 Exploring Next

| Domain | Stack |
|---|---|
| 🛸 Drone Swarm Intelligence | ArduPilot · ROS2 · MAVLink · ORCA |
| 🌦️ Extreme-weather UAVs | Custom firmware · real-time telemetry |
| 🎆 Sky Display Entertainment | Swarm choreography · LED mapping |
| 🌍 Multilingual South Asian NLP | Tiny Aya · Sarvam · Cohere |

---

## 📁 Featured Repos

| Repo | Description |
|---|---|
| [🧬 Adversarial-Autoencoder-network](https://github.com/SRSaini/Adversarial-Autoencoder-network) | CNN-based adversarial autoencoder experiments |
| [🔍 DeepDetection](https://github.com/SRSaini/DeepDetection) | Deep learning object detection notebooks |
| [🏏 IPL-match-win-predication](https://github.com/SRSaini/IPL-match-win-predication) | ML model for IPL win probability |
| [🧠 CNN](https://github.com/SRSaini/CNN) | Convolutional neural network experiments |

---

## 📊 GitHub Stats

<div align="center">

![Sitaram's GitHub Stats](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=SRSaini&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SRSaini&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎓 Background

- 🏛️ **M.Tech — IIT Kharagpur**
- 💼 **Senior Data Scientist @ XpressBees** — India's logistics unicorn
- 🔧 Hands-on with the full stack: GPU drivers → CUDA → training → inference → APIs → monitoring

---

<div align="center">

*"From chaotic Indian addresses to swarm drones — I like problems that are messy at scale."*

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srs02/)

</div>
