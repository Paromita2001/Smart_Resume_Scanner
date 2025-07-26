## Resume Scanner App
A smart Resume Scanning Application that uses Natural Language Processing (NLP) to analyze resumes, extract useful keywords, and classify candidate profiles. The final product is deployed with a Streamlit interface, making it interactive and user-friendly.

# Features
✅ Upload PDF resumes

✅ Extract text using PyMuPDF

✅ Clean and preprocess text with Regular Expressions

✅ Extract skills, email, contact numbers

✅ Identify keywords relevant to job descriptions

✅ Classify resumes into categories like Data Science, Web Development, etc.

✅ Deploy the app using Streamlit

# Tech Stack
Tool	Purpose
Python	Core Programming Language
PyMuPDF	Resume text extraction from PDFs
re (regex)	Pattern matching and text cleaning
Streamlit	Web UI for the resume scanning app
pandas	Data manipulation
sklearn	(Optional) Resume classification
pickle	Saving models or extracted features

Installation
git clone https://github.com/your-username/resume-scanner-app.git
cd resume-scanner-app

pip install -r requirements.txt
How to Run
streamlit run app.py
Then open http://localhost:8501 in your browser.

## Project Structure

# resume-scanner-app/
│
├── app.py                  # Streamlit frontend
├── resume_parser.py        # Extraction and processing logic
├── utils/                  # Helper functions
├── sample_resumes/         # Folder with sample PDFs
├── output/                 # Parsed output data
├── requirements.txt        # List of dependencies
└── README.md               # Project overview (this file)

# Sample Use Case
Upload a resume → Extract details → Identify matching skills → Get classified profile type
Example output:
{
  "Name": "John Doe",
  "Email": "john.doe@gmail.com",
  "Phone": "+91-9876543210",
  "Skills": ["Python", "NLP", "Machine Learning"],
  "Category": "Data Science"
}


# Future Scope
Integrate with job portals for auto-matching

Add database storage (MongoDB / SQL)

Visual dashboards with candidate insights

Enhance classification with deep learning
