
# Project Title
## Infosys_Springboard_TextMorph_Advanced_Text_Summarization_and_Paraphrasing

# 🧠 TextMorph  
AI-Powered Content Simplification, Summarization & Paraphrasing Suite  
Transforming complex content into clear, concise, and accessible communication.

---

## 🔗 Quick Links

| Category        | Link |
|----------------|------|
| 📽️ Demo Video  | https://drive.google.com/file/d/11BptchXlwkf57GmHGy3VI_m-XZZkZXcp/view |
| 🧩 Source Code | This Repository |
| 🐳 Docker Support | Coming Soon |
| 🧠 AI Models   | Pegasus · BART · FLAN-T5 |

---

## 📌 Table of Contents
- About the Project  
- Problem Statement & Motivation  
- Key Features  
- Architecture  
- Tech Stack  
- Models Used  
- Installation & Setup  
- Usage Guide  
- Admin Controls  
- Datasets & Evaluation  
- Screenshots  
- Team  
- License  

---

## 📖 About the Project

TextMorph is an advanced AI tool designed to enhance reading accessibility and content quality using NLP, readability science, and transformer-based language models.

It offers:
- Summarization  
- Paraphrasing  
- Readability scoring  
- Admin dashboard  

📌 Built as part of Infosys Springboard Internship Final Project  
📌 Target users: Students, educators, researchers, bloggers, media professionals  

---

## 🎯 Problem Statement & Motivation

Millions of people struggle to understand complex written content. Manual simplification takes time and expertise.

🔹 Our solution uses AI to:
- Improve readability  
- Shorten lengthy content  
- Rewrite content at different complexity levels  
- Help users learn faster  

---

## 🚀 Key Features

### 👤 User Features

| Feature | Description |
|--------|------------|
| 🔐 Secure JWT Authentication | Login, registration, OTP recovery |
| 📊 Readability Analyzer | Flesch, SMOG, Gunning Fog, graphs |
| ✂️ Summarization | Short / Medium / Long |
| 🔁 Paraphrasing | Simple / Neutral / Advanced |
| 👥 Comparison View | Original vs Generated |
| ⭐ Feedback System | Ratings |
| 🕘 History Log | Save & download |
| 🧑 Profile Management | Secure password update |

---

### 🛠 Admin Features
- User management (add/remove/promote)  
- Usage analytics & reports  
- Feedback monitoring  
- Global search system  
- Full audit logs  
- Lock/Unlock users  

---

## 🧩 Architecture

Monolithic deployment with secure database and ML model integration  

📌 Architecture Diagram: *(Add image here if needed)*  

---

## 🛠 Tech Stack

| Layer | Technology |
|------|-----------|
| Frontend | Streamlit |
| Backend | Python |
| NLP Models | Hugging Face Transformers |
| Database | PostgreSQL |
| Security | JWT, bcrypt |
| Deployment | Docker |

---

## 🤖 Models Used

| Model / Tool | Purpose |
|-------------|--------|
| Pegasus | Abstractive text summarization (long documents, news articles) |
| BART | Text summarization, rewriting, and generation |
| FLAN-T5 | Paraphrasing, QA, translation, instruction-based tasks |
| NLTK | Text preprocessing (tokenization, stemming, POS tagging) |
| textstat | Readability scoring (Flesch, Grade Level, etc.) |

---

## 📝 Installation & Setup

```bash
# Clone repository
git clone <your-repo-link>

# Navigate to project
cd textmorph

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

