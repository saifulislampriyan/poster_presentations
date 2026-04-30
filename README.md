#  1. Space Invaders: 2D Arcade Game using Pygame

> A classic 2D arcade-style shooting game inspired by Space Invaders, built using Python and Pygame.

---

##  Overview

This project recreates a **retro-style Space Invaders game** with multiple levels, sound effects, and player interaction.  
It demonstrates strong fundamentals of **game development, OOP, and real-time logic systems**.

---

##  Objectives

- Develop an interactive 2D shooting game  
- Implement multiple difficulty levels  
- Integrate sound effects and scoring  
- Practice object-oriented programming  

---

##  Features

-  Player movement and shooting  
-  Enemy waves with increasing difficulty  
-  Sound effects (shooting, explosion, background music)  
-  Lives system and scoring  
-  Win screen and restart functionality  

---

##  Technologies Used

- Python  
- Pygame  

---

##  Game Mechanics

- Stage-based progression  
- Increasing enemy speed  
- Collision detection  
- Sprite-based rendering  

---

##  Results

- Successfully implemented:
  - 3 game levels  
  - Score tracking  
  - Game restart system  
  - Visual feedback and animations  

---

##  Limitations

- Single-player only  
- Basic enemy AI  
- No high-score saving system  
- Simple graphics  

---

##  Future Improvements

- Multiplayer mode  
- AI-based enemy behavior  
- Advanced UI/UX  
- Leaderboard system  


---

##  Final Note

A fun and practical project demonstrating core concepts of game development using Python.


#  2. BanglaFakeDetect: Fake News Detection using ML & NLP

> A comparative study of machine learning and neural network models for detecting Bangla fake news with real-time prediction capability.

---

##  Overview

BanglaFakeDetect focuses on identifying fake news in Bangla language using **NLP and machine learning models**.  
The system benchmarks multiple algorithms and provides a **real-time prediction interface**.

---

##  Objectives

- Classify Bangla news as real or fake  
- Apply NLP techniques for text processing  
- Benchmark multiple ML models  
- Build a real-time prediction system  

---

##  Dataset

- 3,045 Bangla news articles  
- Sources:
  - Prothom Alo  
  - BDNews24  
  - Jugantor  
  - Bangla Tribune  

---

##  Methodology

-  Preprocessing:
  - Cleaning  
  - Tokenization  
  - Lemmatization  
  - TF-IDF Vectorization  

-  Models Used:
  - Logistic Regression  
  - SVM  
  - Random Forest  
  - Naive Bayes  
  - KNN  
  - AdaBoost  
  - Gradient Boosting  
  - XGBoost  

---

##  Results

-  **Gradient Boosting**
  - Accuracy: **83.15%**
  - F1-score: **87.64%**

- Other strong performers:
  - SVM  
  - Random Forest  

---

##  Key Insights

- TF-IDF + embeddings improve performance  
- Ensemble models outperform simple models  
- ML-based detection is effective for Bangla news  



---

##  Features

- Real-time prediction interface (React-based)  
- Lightweight and efficient models  

---


#  3. PhishGuard-AI: Phishing & Homoglyph Attack Detection

> A hybrid machine learning and deep learning system for detecting phishing emails and homoglyph-based obfuscation using feature engineering and LSTM networks.

---

##  Overview

PhishGuard-AI is designed to detect phishing emails by analyzing **email subject lines and deceptive character patterns (homoglyph attacks)**.  
The system combines **traditional machine learning models** with **deep learning (CNN + LSTM)** to achieve high accuracy in identifying malicious content.

---

##  Objectives

- Detect phishing and benign emails  
- Identify homoglyph-based obfuscation  
- Compare ML and DL model performance  
- Improve detection accuracy using sequence modeling  

---

##  Methodology

-  Dataset Collection:
  - Enron  
  - SpamAssassin  
  - CEAS  
  - Ling-Spam  
  - Nazario & Nigerian Scam datasets  
  - ~80,000 labeled samples  

-  Feature Engineering:
  - Character-level homoglyph detection  
  - Pattern extraction from subject lines  

-  Models Used:
  - Random Forest  
  - XGBoost  
  - CNN + LSTM (Hybrid Deep Learning)  

---

##  Results

| Model | Accuracy |
|------|--------|
| Random Forest | 75.37% |
| XGBoost | 75.00% |
| **CNN + LSTM** | **92.09%** |

 LSTM-based model significantly outperformed traditional approaches.

---

##  Key Insights

- LSTM captures sequential patterns effectively  
- Homoglyph attacks can be detected via character-level analysis  
- Hybrid approach improves phishing detection accuracy  

---



