
# 🔍 AI-ModelHub

## 🔹 Sessions

- NLP
- Computer Vision
- Multimodal
- Voice / Speech
- Text Generation / Conversational AI

# 🧠 NLP

## 1. Language Translation  
**Model**: `facebook/nllb-200-distilled-600M`  
A distilled multilingual translation model developed by Meta AI, supporting 200+ languages including low-resource ones (e.g., Tamil, Sinhala, Amharic).

- **Architecture**: Transformer-based  
- **Framework**: Hugging Face Transformers  
- **Use Case**: Real-time translation for multilingual apps, chatbots, and localization.  
- **Latest Update**: Released under the NLLB (No Language Left Behind) initiative in 2022 for global language accessibility.  
- **Why It's Preferred**: Faster than larger models, broad language support, optimized for production.

---

## 2. Text Summarization  
**Model**: `facebook/bart-large-cnn`  
A summarization model based on BART (Bidirectional and Auto-Regressive Transformers), fine-tuned on CNN/DailyMail articles.

- **Architecture**: Encoder-decoder transformer (BART)  
- **Framework**: Hugging Face Transformers  
- **Use Case**: Summarizing long articles, documents, or reports into short, fluent summaries.  
- **Latest Update**: Actively maintained on Hugging Face; widely adopted as a summarization benchmark.  
- **Why It's Preferred**: High-quality outputs, fluent and readable summaries, balances speed and accuracy.

# 🎨 Generative Models

## 1. Shifting Focus to Global Audio Perception in Portrait Animation  
**Model Name**: Shifting Focus to Global Audio Perception in Portrait Animation  
**Framework**: Sonic  
**Architecture**:  
- Context-enhanced audio learning, which extracts long-range intra-clip audio knowledge to provide facial expression and lip motion cues (e.g., tone, speech speed).  
- Motion-decoupled controller to separately handle head motion and facial expressions.  
- Time-aware position shift fusion to connect intra-clip motion for global perception.

**Use Case**:  
- Virtual avatars and digital assistants that can perform realistic face and lip animations based on speech input.  
- Used in customer service bots, gaming characters, and virtual companionship.

**GitHub**: [Sonic Repo](https://github.com/jixiaozhong/Sonic?tab=readme-ov-file)  
**Research Paper**: [View on arXiv](https://arxiv.org/pdf/2411.16331)

---

## 2. TrajectoryCrafter: Redirecting Camera Trajectory for Monocular Videos via Diffusion Models  
**Model Name**: TrajectoryCrafter  
**Framework**: Hugging Face  
**Architecture**:  
- Dynamic Point Cloud Generation  
- Dual-Stream Conditional Video Diffusion Model

**Use Case**:  
- Generates dynamic 3D environments from single-view gameplay or video footage.  
- Speeds up environment prototyping or immersive scene recreation for VR/AR games.  
- Example: Creating new walkthroughs of real-world locations in first-person games.

**GitHub**: [TrajectoryCrafter Repo](https://github.com/TrajectoryCrafter/TrajectoryCrafter?tab=readme-ov-file)  
**Research Paper**: [View on arXiv](https://arxiv.org/pdf/2503.05638)


# 🔄 Multimodal

## 1. Qwen2-Audio-7B  
**Created By**: Salesforce Research (LAVIS team)  
**Release Date**: 2023  
**Framework**: PyTorch + Hugging Face Transformers  
**Tasks it Performs**:  
- Image Captioning  
- Visual Question Answering  
- Cross-Modal Matching  
- Grounding (via attention)  

**Reference Use Case**:  
Automates image-based product descriptions, improving SEO and user accessibility. Reduces manual effort in large-scale e-commerce platforms.

---

## 2. BLIP-2  
**Created By**: Salesforce Research (LAVIS team)  
**Release Date**: 2023  
**Framework**: PyTorch + Hugging Face Transformers  
**Tasks it Performs**:  
- Image Captioning  
- Visual Question Answering  
- Cross-Modal Matching  
- Grounding (via attention)  

**Reference Use Case**:  
Automates image-based product descriptions, improving SEO and user accessibility. Reduces manual effort in large-scale e-commerce platforms.

