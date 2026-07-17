# HireFlow
An AI-powered resume parser and candidate ranking system that extracts key information from resumes, analyzes skills and qualifications, and automatically shortlists the best candidates.

## 🚀 Features

- Parse resumes from **PDF** and **DOCX**
- Extract candidate information using **LLMs**
- Analyze job descriptions into structured data
- Match resumes against job requirements
- Generate compatibility scores and hiring insights
- Rank candidates from best to least suitable

## 🛠️ Tech Stack

- **Python**
- **Groq API**
- **GPT-OSS-120B**
- **Pydantic**
- **PyPDF**
- **python-docx**
- **python-dotenv**
- **JSON**

## 📂 Project Structure

```text
ResumeRankAI/
├── resumes/
├── main.py
├── .env
├── requirements.txt
└── README.md
```

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/ResumeRankAI.git
cd ResumeRankAI
pip install -r requirements.txt
python main.py
```

## 🔑 Environment Variable

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key
```

## 📌 Future Enhancements

- Streamlit Web Interface
- Multi Job Description Support
- ATS Resume Scoring
- CSV/Excel Export
- Semantic Skill Matching
- Vector Database Integration

## 👨‍💻 Author

**Navoneel Dey**
