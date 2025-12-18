# Operationalizing Implicit Consent in Conversational AI

This repository contains the proof-of-concept (PoC) implementation for the framework presented in the paper: **"Operationalizing Implicit Consent in Conversational AI: A Privacy-Focused Framework for Detecting Unintended User Consent"**.

## 📌 Project Overview
[cite_start]This study addresses the challenge of identifying cases where users express implicit or unintended consent during conversations with AI systems[cite: 6]. [cite_start]The proposed framework treats implicit consent as a computational construct, combining natural language processing with a privacy-aware execution layer[cite: 8].


## 📊 Performance Summary
[cite_start]Our prototype achieved a robust overall accuracy of **85.0%**[cite: 163, 198]. 
* [cite_start]**No Consent / Explicit Consent:** Achieved perfect F1-scores of **1.00**, ensuring strict refusals are never overlooked[cite: 165, 166].
* [cite_start]**Ambiguous Intent:** Reached an F1-score of **0.73**[cite: 167].
* [cite_start]**Implicit Consent:** Scored **0.57**, reflecting the system's deliberate conservative calibration to prevent accidental data leakage[cite: 168, 171].

## 🛠 Tech Stack
* [cite_start]**Language:** Python 3.9 [cite: 151]
* [cite_start]**Model:** Fine-tuned DistilBERT (`distilbert-base-uncased`) [cite: 126, 154]
* [cite_start]**NLP Tools:** spaCy PhraseMatcher [cite: 148]
* [cite_start]**Logic:** Bayesian approximation via MC Dropout [cite: 138]


*Note: This repository is intended for peer-review purposes.*
