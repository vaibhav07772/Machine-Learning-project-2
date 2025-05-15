# Machine-Learning-project-2
Resume Screening project using TF-IDF, Random Forest, NER Spacy
This project automates the process of resume screening using classic NLP and ML techniques. It classifies resumes into job categories using TF-IDF vectorization, Random Forest classifier, and extracts key skills using spaCy's Named Entity Recognition (NER).

## Demo

Input: Raw text resume data  
Output:  
- Predicted job category  
- Extracted skills/entities from resume


## Tech Stack

- Python 3
- Libraries:
  - pandas, numpy
  - scikit-learn
  - spaCy
## Project Flow

1. *Data Loading*
   - Read resumes and job categories from CSV.
2. *TF-IDF Vectorization*
   - Transform resume text into numerical vectors.
3. *Model Training*
   - Train a RandomForestClassifier on the vectorized text.
4. *NER for Skill Extraction*
   - Use spaCy to extract relevant named entities (skills, technologies, etc.)
5. *Prediction*
   - Predict categories for new/unseen resumes.
