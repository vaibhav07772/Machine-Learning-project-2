# Machine-Learning-project-2
# Resume Screening using TF-IDF, Random Forest, and spaCy NER

## Overview
This project automates the resume screening process by using a combination of NLP and ML. It extracts relevant candidate details using spaCy NER and uses TF-IDF + Random Forest to match resumes to job descriptions.

## Key Features
- Extracts structured data from resumes: Name, Skills, Education, Experience, etc.
- Uses TF-IDF to vectorize resumes and job descriptions.
- Applies Random Forest Classifier to rank resumes based on job-fit.
- Outputs the most suitable resumes for a given job post.

## Technologies Used
- Python
- spaCy (NER)
- Scikit-learn (TF-IDF, Random Forest)
- Pandas, NumPy
- Resume parsing tools (docx2txt, pdfplumber, etc.)

## Use Case
Ideal for recruiters and HR tools to speed up the hiring process by filtering top-matching candidates using AI-based techniques.
