# 🍎 AI Calorie Tracker

AI-powered nutrition analysis app built with **Streamlit** and **OpenAI Vision API**. Upload a food image, get instant calorie and macro breakdown.

![Python](https://img.shields.io/badge/Python-3.8+-blue) ![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red) ![OpenAI](https://img.shields.io/badge/OpenAI-Vision_API-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Features

- **AI Food Recognition** — Upload any food photo and get nutritional data in seconds
- **9-Nutrient Analysis** — Calories, protein, fat, carbs, fiber, sugar + confidence score
- **Daily Tracker** — Log meals and view daily totals with interactive charts
- **Export Data** — Download nutrition results as JSON
- **Premium UI** — Professional design with color-coded metrics and animations

---

## Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/calorie-tracker.git
cd calorie-tracker

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set up API key
cp .env.example .env
# Edit .env and add your API key (OpenRouter or OpenAI)

# 4. Run the app
streamlit run app.py
```

The app opens at `http://localhost:8501`

---

## API Key Setup

Create a `.env` file from the example:

**OpenRouter** (recommended):
```env
OPENROUTER_API_KEY=sk-or-v1-your-key-here
OPENAI_BASE_URL=https://openrouter.ai/api/v1
```

**OpenAI**:
```env
OPENAI_API_KEY=sk-your-key-here
```

Get your key: [OpenRouter](https://openrouter.ai) | [OpenAI](https://platform.openai.com/api-keys)

---

## Project Structure

```
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies
├── .env.example            # API key template
├── .gitignore              # Git ignore rules
├── .streamlit/
│   └── config.toml         # Streamlit theme config
└── notebook/
    └── Build a Calorie Tracker.ipynb   # Original Jupyter notebook
```

---

## Screenshots

| Upload & Analyze | Nutrition Results | Daily Tracker |
|:---:|:---:|:---:|
| Upload any food photo | Color-coded macro breakdown | Track meals with charts |

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Streamlit | Web UI framework |
| OpenAI Vision API | Food image recognition |
| Plotly | Interactive charts |
| Pandas | Data handling |
| Pillow | Image processing |

---

## License

MIT — free for personal and commercial use.
