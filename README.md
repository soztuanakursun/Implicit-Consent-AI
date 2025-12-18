# Operationalizing Implicit Consent in Conversational AI

This repository contains the proof-of-concept (PoC) implementation for the framework presented in the paper: **"Operationalizing Implicit Consent in Conversational AI: A Privacy-Focused Framework for Detecting Unintended User Consent"**.

## Project Overview
This study addresses the challenge of identifying cases where users express implicit or unintended consent during conversations with AI systems. The proposed framework treats implicit consent as a computational construct, combining natural language processing with a privacy-aware execution layer.


## Performance Summary
Our prototype achieved a robust overall accuracy of **85.0%**.
* **No Consent / Explicit Consent:** Achieved perfect F1-scores of **1.00**, ensuring strict refusals are never overlooked
* **Ambiguous Intent:** Reached an F1-score of **0.73**.
* **Implicit Consent:** Scored **0.57**, reflecting the system's deliberate conservative calibration to prevent accidental data leakage

## 🛠 Tech Stack
* **Language:** Python 3.9 
* **Model:** Fine-tuned DistilBERT (`distilbert-base-uncased`) 
* **NLP Tools:** spaCy PhraseMatcher 
* **Logic:** Bayesian approximation via MC Dropout 


*Note: This repository is intended for peer-review purposes.*
