📰 Fake News & AI Content Detector
🧠 Explainable AI for Truth Verification
<p align="center"> <b>Not just detection — understanding the truth behind the text.</b><br/> <i>AI that explains, verifies, and evaluates content credibility.</i> </p>
🌟 What Makes This Special?

Most tools:

❌ Just say “Fake” or “Real”

This system:

✅ Explains → Verifies → Scores → Detects AI

🧠 Overview

Fake News & AI Content Detector is an advanced system that analyzes text to:

Detect fake or misleading information
Identify AI-generated content
Provide clear explanations for its decisions
Cross-check claims with trusted sources
Generate a credibility score

👉 Built with a combination of LLMs, fact-checking, and explainable AI techniques

🎬 Demo
🧾 Input
“Scientists say drinking coffee cures cancer instantly.”
⚡ Output
⚠️ Likely Fake (Confidence: 87%)

Reasons:
- No credible sources cited
- Uses exaggerated claims ("cures instantly")
- Not supported by scientific evidence

AI Content Probability: 72%
Fact Check: No trusted sources found
Credibility Score: 18/100
🏗️ System Architecture
⚡ Core Features
🧠 Fake News Detection
Classifies content as:
Real
Likely Fake
Fake
Provides confidence score
🤖 AI Content Detection
Detects whether text is:
Human-written
AI-generated
Uses LLM + statistical patterns
🔍 Explainability Engine (🔥 Key Feature)
Highlights:
Misleading claims
Emotional language
Lack of sources
Provides human-readable reasoning
🌐 Fact Cross-Verification
Searches trusted sources
Validates claims
Flags contradictions
📊 Credibility Score
Combines:
Writing style
Source reliability
Fact-check results
Outputs a final score (0–100)
🛠️ Tech Stack
Layer	Technology
Backend	Python, FastAPI
LLM	Ollama / OpenAI
ML Models	BERT / Logistic Regression
Fact Check	Tavily / SerpAPI
Frontend	Streamlit / React
📂 Project Structure
fake-news-detector/
│
├── backend/
│   ├── main.py
│   ├── models/
│   │   ├── classifier.py
│   │   ├── ai_detector.py
│   │   └── fact_checker.py
│   │
│   ├── llm/
│   │   └── analyzer.py
│   │
│   └── utils/
│       └── preprocessing.py
│
├── frontend/
│   └── app.py
│
├── requirements.txt
└── README.md
🚀 Quick Start
1️⃣ Clone the Repo
git clone https://github.com/your-username/fake-news-detector.git
cd fake-news-detector
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Backend
uvicorn main:app --reload
4️⃣ Run Frontend (Streamlit)
streamlit run app.py
💡 Use Cases
📰 Detect misleading news articles
🤖 Identify AI-generated content
🎓 Assist students & researchers
🛡️ Combat misinformation
🏆 Hackathon-ready AI project
