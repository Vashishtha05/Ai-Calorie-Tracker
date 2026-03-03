#  AI Calorie Tracker — Vision-Based Nutrition Analyzer

<p align="center">
  <img src="https://img.shields.io/badge/LLM-Vision%20API-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Streamlit-Interactive%20App-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-Nutrition%20AI-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Multimodal-Food%20Analysis-green?style=for-the-badge">
</p>

<p align="center">
  A vision-powered nutrition analysis app that estimates calories and macros from food images.
</p>

---

## 📌 Overview

AI Calorie Tracker is a multimodal application that uses a Vision-enabled LLM to analyze food images and estimate nutritional values.

The system:

- Detects food from uploaded images  
- Estimates calories and macro breakdown  
- Tracks daily intake  
- Visualizes consumption with interactive charts  

---

## ✨ Features

- 📷 AI-based food image recognition  
- 📊 9-nutrient analysis (calories, protein, fat, carbs, fiber, sugar, etc.)  
- 📅 Daily meal logging & tracking  
- 📈 Interactive charts with Plotly  
- 📤 Export results as JSON  
- 🎨 Clean Streamlit UI  

---

## ⚙️ Tech Stack

| Technology | Usage |
|------------|--------|
| Python | Core development |
| Streamlit | Web interface |
| OpenAI Vision API | Image-based nutrition analysis |
| Pandas | Data processing |
| Plotly | Data visualization |
| Pillow | Image handling |

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/ai-calorie-tracker.git
cd ai-calorie-tracker
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure API Key

Create a `.env` file:

**OpenRouter**
```env
OPENROUTER_API_KEY=your-key
OPENAI_BASE_URL=https://openrouter.ai/api/v1
```

**OpenAI**
```env
OPENAI_API_KEY=your-key
```

### 4️⃣ Run Application

```bash
streamlit run app.py
```

App runs at:

```
http://localhost:8501
```

---

## 🧠 Workflow

1. User uploads food image  
2. Image is sent to Vision-enabled LLM  
3. Model extracts food context  
4. Nutritional breakdown is generated  
5. Results are logged and visualized  

---

## 📂 Project Structure

```
├── app.py
├── requirements.txt
├── .env.example
├── .streamlit/config.toml
└── notebook/
```

## 👨‍💻 Author 
**Vashishtha Verma** 
* 🤖 Machine Learning & Generative AI
* 🧠 Agentic AI Systems
* 💻 Software Engineering & DSA
