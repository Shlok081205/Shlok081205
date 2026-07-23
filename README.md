# Hi, I'm Shlok Patel 👋

> CS student at LJ University — I build things that actually work, from ML engines written from scratch to production Django apps, fine-tuned LLMs, and deployed AI systems.

---

## 🚀 What I'm Building

- 🍽️ **[CulinaAI](https://github.com/Shlok081205/CulinaAI-Backend)** — A full-stack Django app with 500K+ recipe archive, a **custom fine-tuned LLM** for recipe generation, intelligent grocery basket comparison, and a personalized 7-day meal planner backed by TDEE-based calorie targeting. Deployed over Tailscale with production-hardened security (HSTS, secure cookies, GIN trigram indexes on PostgreSQL).

- 📈 **[TradeAlchemy](https://github.com/Shlok081205/Trade_Alchemy)** — AI-powered stock analysis platform built with Flask + TensorFlow. Features a multi-timeframe LSTM confidence model, real-time Yahoo Finance scraping, and Gemini AI-driven market insights.

---

## 🧠 Featured Work

### 🤗 Fine-tuned LLM — Published on HuggingFace
I fine-tuned **Qwen2.5-7B-Instruct** on 22,000 recipes from the Recipe1M+ dataset (MIT CSAIL) using **QLoRA** (LoRA rank 16, 4-bit quantized base) via Unsloth Studio. Exported to **GGUF Q4_K_M (~4.68 GB)** for local inference in LM Studio and Ollama.

**[🤗 Shlok0011/CulinaAI-Qwen2.5-7B-GGUF](https://huggingface.co/Shlok0011/CulinaAI-Qwen2.5-7B-GGUF)** — 283+ downloads

| Hyperparameter | Value |
|---|---|
| Base model | Qwen2.5-7B-Instruct |
| Fine-tuning method | QLoRA (LoRA r=16, α=32) |
| Training data | 22,000 recipes — Recipe1M+ |
| Epochs | 3 · LR: 2e-4 · Optimizer: AdamW 8-bit |
| Best eval loss | **0.719** |
| Format | GGUF Q4_K_M · 4.68 GB |

### 🤖 ML From Scratch — No Libraries
In my [Stock Market Predictor](https://github.com/CrimsonDevil8038/StockMarketPrerdictor), I implemented a complete ML training pipeline in **pure Java** — no Scikit-learn, no TensorFlow:
- **Batch Gradient Descent** with **L2 Regularization** across 16 technical indicators (RSI, MACD, Bollinger Bands, EMA, SMA...)
- Custom feature engineering pipeline computing derived indicators from raw OHLCV data
- PostgreSQL-backed portfolio management with a custom Linked List data structure

### 📅 Date Algorithms From Scratch
In my [Calendar & Event System](https://github.com/Shlok081205/Calender_and_Event_Managment_System), every calendar operation — leap year detection, day-of-week calculation, date arithmetic, palindrome date finding, recurring event projection — was implemented using raw loops and control flow. Zero `java.time`.

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frameworks & Libraries**

![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white)

**Databases & Tools**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Maven](https://img.shields.io/badge/-Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)

**AI / ML**

![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Kaggle](https://img.shields.io/badge/-Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini%20AI-4285F4?style=flat&logo=google&logoColor=white)
![LM Studio](https://img.shields.io/badge/-LM%20Studio%20%2F%20Qwen-6B21A8?style=flat&logo=meta&logoColor=white)
![Unsloth](https://img.shields.io/badge/-Unsloth-FF6B35?style=flat&logoColor=white)

---

## 📂 Projects

| Project | Stack | What's Interesting |
|---|---|---|
| [CulinaAI](https://github.com/Shlok081205/CulinaAI-Backend) | Django · PostgreSQL · Fine-tuned LLM | GIN trigram search, TDEE meal planning, custom QLoRA model |
| [CulinaAI LLM](https://huggingface.co/Shlok0011/CulinaAI-Qwen2.5-7B-GGUF) | QLoRA · Unsloth · GGUF | Fine-tuned Qwen2.5-7B on 22K recipes · 283+ downloads |
| [TradeAlchemy](https://github.com/Shlok081205/Trade_Alchemy) | Flask · TensorFlow · Gemini AI | Multi-timeframe LSTM, real-time scraping, AI market insights |
| [Stock Market Predictor](https://github.com/CrimsonDevil8038/StockMarketPrerdictor) | Java · Maven · PostgreSQL | Gradient Descent + L2 Reg from scratch, 16 technical indicators |
| [Calendar & Event System](https://github.com/Shlok081205/Calender_and_Event_Managment_System) | Core Java | All date arithmetic from scratch — no date libraries |
| [EnhancedRecipe Dataset](https://www.kaggle.com/datasets/shlokpatel0812/culinaai-datasets) | Kaggle Dataset · NLP | Recipe1M+ enriched with per-serving nutrition, NER tags, & meal types |
| [BSE Company List](https://www.kaggle.com/datasets/shlokpatel0812/bombay-stock-exchange-bse-company-list) | Kaggle Dataset · Finance | Scraped listing of all companies on the Bombay Stock Exchange |

---

*📍 LJ University, Ahmedabad · Open to internship opportunities*
