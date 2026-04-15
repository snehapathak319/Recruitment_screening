# AI-Based Recruitment Screening System

AI | HR Analytics | NLP | Machine Learning | Recruitment Automation

---

## Overview

This project demonstrates an AI-assisted recruitment screening system designed to support HR teams in shortlisting candidates efficiently. It combines natural language processing techniques with a structured scoring model to evaluate candidate profiles against a job description.

The system uses TF-IDF vectorization and cosine similarity to measure how closely candidate skills match job requirements. Additional factors such as experience, education, and certifications are incorporated into a weighted scoring model to generate a final ranking.

This project is intended for academic and learning purposes, simulating a simplified version of real-world recruitment analytics.

---

## Key Features

* Synthetic dataset of 20 candidate profiles
* Text-based matching using TF-IDF
* Cosine similarity for resume-job comparison
* Feature normalization for fair scoring
* Weighted ranking model combining multiple HR factors
* Automated candidate ranking and shortlisting
* Exportable results for further analysis in Excel or Power BI

---

## Technology Stack

* Python
* Pandas
* NumPy
* Scikit-learn

---

## Workflow

### 1. Data Preparation

A structured dataset is created containing:

* Candidate ID
* Name
* Skills
* Experience (years)
* Education
* Certifications

### 2. Job Description Definition

A sample job description is defined to act as a benchmark for candidate evaluation.

### 3. Text Vectorization

TF-IDF (Term Frequency–Inverse Document Frequency) is applied to convert textual data into numerical form.

### 4. Similarity Calculation

Cosine similarity is used to measure the similarity between candidate skills and the job description.

### 5. Feature Engineering

Additional features are processed:

* Experience normalized to a 0–1 scale
* Certifications normalized to a 0–1 scale
* Education converted into a numerical score

### 6. Weighted Scoring Model

A final score is computed using weighted components:

* Similarity Score: 50%
* Experience Score: 25%
* Education Score: 15%
* Certification Score: 10%

### 7. Candidate Ranking

Candidates are ranked based on the final score in descending order.

### 8. Shortlisting

Top candidates are shortlisted for HR review.

### 9. Output Generation

Final results are exported as a CSV file for further analysis.

---

## Sample Output

The output includes:

* Candidate details
* Individual component scores
* Final score
* Recommendation label (Strong Match / Moderate Match / Low Match)

---

## Use Cases

* HR analytics learning
* AI-assisted recruitment screening
* Resume matching systems
* Academic projects and demonstrations

---

## Limitations

* Uses synthetic data, not real-world datasets
* Education scoring is simplified and may not reflect real hiring standards
* Does not consider soft skills, cultural fit, or behavioral aspects
* Model is rule-based and not fully automated AI

---

## Future Improvements

* Integration with real resume datasets
* Use of advanced NLP models (BERT, embeddings)
* Bias detection and fairness evaluation
* Web-based dashboard integration
* Real-time recruitment analytics

---

## Conclusion

This project demonstrates how AI can assist HR professionals in streamlining the recruitment process. While it improves efficiency and consistency in screening, human judgment remains essential for final hiring decisions.

---

## Author

Sneha Pathak

---

## License

This project is for academic and educational use only.
