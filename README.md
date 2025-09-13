# Semantic Book Recommender with LLMs (Reproduction)

This repository is a reproduction of the excellent freeCodeCamp course titled "Build a Semantic Book Recommender with LLMs – Full Course". The project showcases how to build a semantic book recommendation system powered by Large Language Models (LLMs), vector search, and a user-friendly Gradio interface.

The project is structured into five core components:

---

## 🔍 Components

### 1. Text Data Cleaning
- **Notebook:** `data-exploration.ipynb`
- Explore and clean book text data to prepare it for downstream tasks like vector search and classification.

### 2. Semantic Search with Vector Database
- **Notebook:** `vector-search.ipynb`
- Build a vector search engine using sentence embeddings to find books similar to natural language queries like "a book about survival on an island".

### 3. Zero-Shot Text Classification
- **Notebook:** `text-classification.ipynb`
- Use zero-shot learning with LLMs to classify books into categories like "fiction" or "non-fiction".

### 4. Sentiment and Emotion Analysis
- **Notebook:** `sentiment-analysis.ipynb`
- Extract emotional tone and sentiments (e.g., joyful, suspenseful, sad) from book descriptions to support mood-based recommendations.

### 5. Interactive Web Application
- **Script:** `gradio-dashboard.py`
- Deploy a Gradio web interface that allows users to:
  - Search for books using natural language
  - Filter by genre (fiction/non-fiction)
  - Sort by emotional tone

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.11
- Install required dependencies:

```bash
pip install -r requirements.txt
```

### 🔐 API Key
You'll need an OpenAI API key to run the LLM-powered components. Create a `.env` file in the project root:

```
OPENAI_API_KEY=your_openai_key_here
```

### 📦 Data
The dataset is available on Kaggle. Instructions for downloading and integrating it are provided in the course and notebooks.

---

## 🧠 Technologies & Libraries
- `langchain`
- `transformers`
- `kagglehub`
- `gradio`
- `chroma`
- `pandas`, `matplotlib`, `seaborn`
- `python-dotenv`
- `ipywidgets`

---

## 📺 Reference
This project is a direct reproduction of the tutorial from freeCodeCamp:
- 📹 "Build a Semantic Book Recommender with LLMs – Full Course"
- 🔗 Watch the full course on YouTube

---

## 📄 License
This project is for educational and reproducibility purposes based on the original work by the course author. Please refer to the original video for guidance and credit.