# 🧠 Natural Language Processing & Computer Vision (NLP-CV)

Repository for all laboratory and project work related to the CDAC Post Graduate Diploma in Artificial Intelligence (PG-DAI) program (September 2022 Batch, ACTS Pune).

[cite_start]The subject has a total duration of **100 hours**, comprising **60 hours** dedicated to NLP and **40 hours** dedicated to Computer Vision[cite: 7].

***

## ⚙️ Repository Structure

This repository is organized to map directly to the conceptual and practical modules of the syllabus.

***

## 🚀 Getting Started

### Prerequisites

* **Knowledge:** Good knowledge of Python Programming and fundamentals of Artificial Intelligence[cite: 9].
* **Python:** Python 3.8+
* **IDE:** Jupyter Notebooks, VS Code, or PyCharm

### Environment Setup

Create and activate a virtual environment, then install the required libraries.

```bash
# Create a new environment (optional but recommended)
python -m venv nlp_cv_env
source nlp_cv_env/bin/activate  # On Windows, use: .\nlp_cv_env\Scripts\activate

# Install core libraries
pip install numpy pandas scikit-learn matplotlib jupyter
pip install nltk spacy tensorflow opencv-python

# NLTK Downloads
import nltk
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')

# spaCy Model Download
!python -m spacy download en_core_web_sm
