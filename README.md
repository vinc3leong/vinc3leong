# Hi, I'm Vince 👋  

Just a student messing around with **AI** and building **ML models**.  
Half learning, half experimenting, and occasionally making something that actually works. 🚀

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vince-zi-yong-leong)


## 🚀 Relevant Projects

### 1. Neural Grammatical Error Correction (GEC) Study 
[![Read the Paper](https://img.shields.io/badge/📄-Read%20the%20Paper-orange?style=flat&logoColor=white)](https://github.com/vinc3leong/Grammatical-Error-Correction/blob/main/G08_report.pdf)

**Tech Stack:** Python, PyTorch, Hugging Face Transformers, ERRANT, Pandas, LaTeX

* Conducted a **comparative analysis** of Transformer architectures (T5, Flan-T5, BART) for sequence-to-sequence error correction.
* Implemented a **two-stage fine-tuning curriculum**:
    * **Domain Adaptation:** Trained on 1M+ noisy sentences (Lang-8).
    * **Specialization:** Refined on high-quality gold corpora (NUCLE, FCE, W&I).
* Developed an **Edit-based System Combination (ESC)** to ensemble model outputs, leveraging the complementary strengths of precision-focused (T5) and recall-oriented (BART) models.
* Achieved a top **F0.5 score of 68.97** on the BEA-2019 benchmark with T5-base, outperforming the significantly larger BART-large model.

---

### 2. Review Filtering Model  
**Tech Stack:** Jupyter Notebook, Apify API, Gemini API  
- Built a **multi-classification model** to classify Google reviews into: *ad, spam, irrelevant, rant_no_visit, relevant*.  
- Fine-tuned **DistilBERT** to improve review filtering efficiency.  
- Processed and cleaned data, scraped reviews with **Apify API**, and trained the model with high-quality inputs.  
- Evaluated performance with **accuracy and F1 scores**, ensuring reliable classification.  

---

### 3. Travel Scout  
**Tech Stack:** React Native, DeepSeek API, TypeScript, Python  
- Developed during a hackathon to provide **personalised travel planning**.  
- Features:  
  - **Dynamic itinerary generation** based on user inputs (location, budget, preferences, dates).  
  - **Chatbot** for real-time itinerary modifications.  
  - **Speech translation** to enhance accessibility.  
- Adapted to real-world conditions (e.g., crowds, weather) to improve user experience.  

---

### 4. Automated Rostering System  
**Tech Stack:** Excel VBA  
- Semi-automated rostering system.  
- Features:  
  - **Roster generation algorithm** with staff swapping support.  
  - **Analysis report generation** and sheet protection.  
- Reduced rostering time from **two weeks → under one minute**, boosting efficiency and accuracy.  
- Conducted user interviews and integration testing to ensure seamless adoption.  

---

### 5. NUSell  
**Tech Stack:** React Native, Express.js, Node.js, Axios, MongoDB, JavaScript, eBay API  
- Full-stack marketplace app.
- Key features:  
  - **Buy, list, and sell items** with user authentication and payments.  
  - **eBay API integration** for price comparison.  
  - **Basic image recognition** with suggested item names.  
