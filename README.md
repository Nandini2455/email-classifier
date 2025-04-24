
# 📧 Email Classification & PII Masking API

Developed by **P. Nandini**, this project automates classification of emails into predefined categories while masking personally identifiable information (PII) such as names, emails, and phone numbers. It is deployed as a REST API using FastAPI.

🚀 **Live Demo**: [Hugging Face Space](https://huggingface.co/spaces/nandini2455508/email-classifier-space)

---

## 🔍 Features

- ✅ PII Masking (Names, Emails, Phones, Addresses, Credit Cards)
- ✅ Email Classification using Random Forest
- ✅ TF-IDF for feature extraction
- ✅ REST API with FastAPI
- ✅ Dockerized deployment
- ✅ 80% model accuracy

---

## 📦 Installation

### ⚙️ Requirements

- Python 3.10
- pip
- Docker (optional)

### 🛠️ Setup (Without Docker)

```bash
# Clone the repository
git clone https://huggingface.co/spaces/nandini2455508/email-classifier-space
cd email-classifier-space

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download NLTK resources
python -m nltk.downloader stopwords wordnet
