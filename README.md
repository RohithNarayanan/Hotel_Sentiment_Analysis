# 🏨 Hotel Review Sentiment Analysis using IBM Watsonx

This project performs **sentiment analysis** on hotel customer reviews using **IBM Watsonx's FLAN-UL2 foundation model**. It classifies feedback as either **positive (1)** or **negative (0)** using prompt-based predictions through IBM's cloud AI service.

---

## 📌 Key Features

- ✅ Uses a zero-shot LLM (FLAN-UL2) from IBM Watsonx
- ✅ Prompt-based binary classification (0 = Negative, 1 = Positive)
- ✅ Displays actual vs predicted sentiments side-by-side
- ✅ Handles API rate limits with auto-throttling

---

## 🛠️ Tech Stack

- **Language:** Python 3.11  
- **Libraries:** `pandas`, `ibm-watson-machine-learning`  
- **Model:** FLAN-UL2 via IBM Watsonx  
- **Deployment:** Notebook-based analysis
