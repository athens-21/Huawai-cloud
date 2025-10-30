# Global Power Dynamics & Financial News Intelligence Platform  
**Predicting the Rise and Fall of Nations Through Historical Patterns, Financial News, and Interactive Analytics**

---

## 🌍 Project Overview  

This project aims to **analyze the long-term development trajectories of countries** by integrating **historical empire data**, **real-time financial news**, and **Ray Dalio’s 8 Measures of National Power** framework from *The Changing World Order*.  

By studying how nations rose, peaked, and declined in the past — and combining that with **deep financial and geopolitical news analysis** — we can:  
- Identify **early warning signals** of national rise or decline  
- Map **global supply chain dependencies** and **inter-country relationships**  
- Forecast **future power shifts** and **market impacts**  

Ultimately, this becomes a **predictive intelligence engine** for geopolitics, economics, and investment strategy.

---

## 🎯 Core Objectives  

| Objective | Status |
|---------|--------|
| Analyze historical rise/fall patterns of empires (500+ years) | Done |
| Implement Ray Dalio's 8 Measures of Power Index | Done |
| Efficiently extract & filter financial news for single stock (S&P 500) | Done |
| Build **Interactive Relationship Map** (countries ↔ industries ↔ stocks ↔ resources) | In Progress |
| Predict country & market trends using historical + news sentiment | Planned |
| Real-time API integration (World Bank, IMF, SIPRI, etc.) | Planned |

---

## ✅ What’s Already Built  

### 1. **Country Power Index (Ray Dalio Framework)**  
> `country-power-index.ipynb`  

- **20 major countries** analyzed (US, China, Japan, Germany, India, etc.)  
- **8 weighted power measures**:  
  - Education (15%)  
  - Innovation & Tech (15%)  
  - Economic Output (20%)  
  - Trade (15%)  
  - Military (10%)  
  - Financial Center (10%)  
  - Reserve Currency (10%)  
  - Competitiveness (5%)  
- Simulated realistic data with variance per country  
- Ready for **real API integration** (World Bank, IMF, OECD, SIPRI)

---

### 2. **Historical Empire Pattern Recognition (1500–2025)**  
> `Historical Pattern Recognition.ipynb`  

- Tracks **7 major empires**:  
  - Dutch Empire  
  - British Empire  
  - United States  
  - Qing & Modern China  
  - Soviet Union  
  - Japan (Meiji → Present)  
- Includes:  
  - Key historical events  
  - Power score timeline (0–100)  
  - Peak, rise, and decline phases  
- Foundation for **pattern matching** current nations to past trajectories

---

### 3. **Single-Stock Financial News Deep Dive (Optimized)**  
> `only data for ONE stock efficiently.ipynb`  

- Downloads **FNSPID dataset** (~22 GB) from Hugging Face  
- Filters **only news for one ticker** (e.g., `AAPL`) → **memory efficient**  
- Configurable:  
  - `TICKER`, `YEARS`, `MIN_NEWS_COUNT`  
- Prepares data for:  
  - Sentiment analysis  
  - Event detection  
  - Supply chain entity extraction (NER)  
  - Relationship graph construction

---

## 🚧 In Progress  

### Interactive Relationship Knowledge Graph  
```text
[Country] ↔ [Industry] ↔ [Company] ↔ [Resource] ↔ [Supplier Country]
     ↓           ↓            ↓            ↓              ↓
  Policy     Earnings     Supply       Commodity      Trade Deal
  Protests   Guidance     Disruption   Price Shock     Sanctions
