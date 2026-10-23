# ai-resume-screening-
AI-based resume screening and candidate ranking
B.Tech Project | Department of CSE (Data Science)
Shri Shankaracharya Institute of Professional Management & Technology, Raipur

**Project Guide:** Gurudatt Verma
**Team:** Rafiyat Khan (Team Lead), Ashi Mishra, G Ayush, Md Shadab Khan

> **Status:** Semester III – proposal stage (Project Review–I). No results are claimed before testing.

## Problem
Recruiters can receive hundreds of resumes for one job. Reading them manually is slow, inconsistent, and important skills are easy to miss. Keyword-only tools miss meaning and give no reason for their scores.

## Our Solution
A web-based system that:
1. Reads resumes (PDF/DOCX) and extracts skills, education, experience and projects.
2. Compares each profile with a job description using keyword (TF-IDF) and meaning-based (Sentence-BERT) similarity.
3. Shows a ranked shortlist with matched and missing skills, so every score can be explained.

The system supports the recruiter. It does not replace the recruiter's final decision.

## Planned Tech Stack
- **Language:** Python 3.10+, JavaScript, SQL
- **NLP / ML:** spaCy, scikit-learn, sentence-transformers
- **Backend:** FastAPI or Flask
- **Frontend:** React.js
- **Database:** PostgreSQL or MySQL
- **Tools:** Git/GitHub, Jupyter Notebook, VS Code, Postman

## Roadmap
| Semester | Focus | Output |
|---|---|---|
| III | Literature survey, scope, feasibility | Proposal + feasibility report |
| IV | Architecture, database, wireframes | Design document |
| V | Data collection, parser, TF-IDF baseline | Working prototype |
| VI | Sentence-BERT, database, login, APIs | Backend system |
| VII | Dashboard, explainable scores, bias checks | Integrated system v1 |
| VIII | Pilot test, evaluation, report, demo | Final demo + report |

## Repository Contents
- `docs/` – project proposal and presentation
- `notebooks/` – experiments (added from Semester V)

## Data and Privacy
We use public datasets and anonymised, consented resumes only. Datasets are **not** stored in this repository. See the dataset source on Kaggle: *(add the link here)*.

## References
1. G. Salton and C. Buckley, "Term-weighting approaches in automatic text retrieval," *Information Processing & Management*, vol. 24, no. 5, pp. 513–523, 1988.
2. N. Reimers and I. Gurevych, "Sentence-BERT: Sentence embeddings using Siamese BERT-networks," in *Proc. EMNLP-IJCNLP*, 2019, pp. 3982–3992.
3. J. Dastin, "Amazon scraps secret AI recruiting tool that showed bias against women," Reuters, Oct. 10, 2018.
4. The Ladders, "Eye-tracking study: Keeping an eye on recruiter behavior," 2018.

#add file 

