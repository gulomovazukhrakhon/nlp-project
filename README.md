# ✈️ Topic Modeling on Air France Customer Reviews

## 📌 Project Overview

This project applies Natural Language Processing (NLP) techniques to identify the most frequent topics in customer complaints from the **Air France Reviews** dataset. The dataset contains unstructured customer feedback about airline experiences, including topics like flight delays, food quality, staff behavior, and comfort.

The project was developed as part of the **Data Analysis Portfolio** for the IU Applied AI Bachelor's program.

---

## 🔍 Objectives

- Clean and preprocess textual data
- Convert text into numeric vectors using both:
  - TF-IDF (frequency-based)
  - Sentence-BERT (semantic-based)
- Extract meaningful topics using:
  - LDA (Latent Dirichlet Allocation)
  - BERTopic (BERT + clustering)
- Compare both approaches in terms of topic coherence and interpretability

---

## 🧰 Technologies and Libraries

- **Python**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `nltk`, `spacy`, `gensim`, `scikit-learn`
- `sentence-transformers`, `transformers`
- `bertopic`, `pyLDAvis`, `torch`

---

## 📊 Results Summary
- LDA discovered clear but shallow keyword-based groupings.
- BERTopic identified more coherent and context-aware themes using semantic sentence embeddings.

Most common topics included: ***flight delays, rude staff, uncomfortable seating, and poor food quality***.

