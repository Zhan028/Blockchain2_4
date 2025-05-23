#  AI Crypto Assistant

An **AI-powered cryptocurrency assistant** that delivers real-time market data, news, and smart analysis using **Retrieval-Augmented Generation (RAG)** architecture — all via a sleek Streamlit interface.

---

##  Features

###  Real-Time Crypto Data
-  **Price Tracking** — Get live prices from **Binance API**
-  **Market Capitalization & Rankings** — Powered by **CoinMarketCap API**
-  **Latest News Updates** — Stay informed with **CryptoPanic API**

###  AI-Powered Analysis
-  Uses **GPT-4** or local LLM (**Ollama**) for intelligent, context-aware answers
-  **News Summarization** — TL;DR for busy traders
-  Understands and responds with crypto-specific context

###  User-Friendly Interface
-  Built with **Streamlit** for a modern, interactive experience
-  Fully **mobile-responsive** for on-the-go access
-  **Query history** — Look back at past conversations anytime

---

##  Tech Stack

| Component         | Tech                                  |
|------------------|---------------------------------------|
| Frontend         | [Streamlit](https://streamlit.io)     |
| AI Model         | GPT-4 / Ollama (Local LLM)            |
| Crypto Data APIs | Binance, CoinMarketCap, CryptoPanic   |
| Backend          | Python + Retrieval-Augmented Generation (RAG) |

---

##  Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/BLOCKCHAIN2_4.git
cd BLOCKCHAIN2_4
```


### Set Your API Keys
### Create a .env file in the root directory and add your keys:
```bash
BINANCE_API_KEY=your_key_here
COINMARKETCAP_API_KEY=your_key_here
CRYPTOPANIC_API_KEY=your_key_here
OPENAI_API_KEY=your_key_here
```

###  Run the App
```bash
streamlit run app.py
```

### Authors 
Moldabek Zhanbatyr, Nadir Shugay, Dias Makhatov