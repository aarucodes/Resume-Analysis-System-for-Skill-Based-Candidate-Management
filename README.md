This project is a Resume Analysis Tool built with Python to assist recruiters in efficiently filtering and categorizing resumes based on required job skills. The system extracts text from resumes, identifies key skills, and matches them against job descriptions or predefined skill sets.

🚀 Features
📄 Upload and parse resumes in PDF or DOCX format

🔍 Extract skills, experience, and education from text

🧠 Match candidates to job descriptions using NLP and ML

📊 Visualize resume data (optional)

🧹 Clean and preprocess resume content

✅ Works for individual or batch resume analysis

🛠️ Tech Stack
Python

Pandas & NumPy

scikit-learn / spaCy / NLTK (for NLP)

Streamlit (if web-based interface is included)

Tika / PyMuPDF / docx2txt (for file parsing)

📁 Project Structure
bash
Copy
Edit
Resume-Analysis/
│
├── Resume Analyse.ipynb        # Main notebook with logic
├── resumes/                    # Folder to store resume files
├── skills.csv                  # Dataset of predefined skills (optional)
├── requirements.txt            # Python dependencies
└── README.md                   # You're reading it!
🔧 How to Run
Clone the repository
git clone https://github.com/aarucodes/resume-analysis.git

Navigate to the directory
cd resume-analysis

Install dependencies
pip install -r requirements.txt

Open the notebook
jupyter notebook "Resume Analyse.ipynb"

📌 Use Case
HR teams at startups or large companies

Resume shortlisting for internships or campus placements

Automating initial filtering in a hiring pipeline

✨ Future Improvements
Integrate with job portals or LinkedIn APIs

Add semantic analysis for better skill matching

Build a Streamlit or Flask frontend

Add support for ranking candidates
