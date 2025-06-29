# Why Resumes Fail: A Beginner ATS Resume Analyzer

In my first year of college, I applied to several data internships and heard nothing back.

I had some skills. I had passion. I wrote a resume.  
But what I didn’t realize was most resumes don’t even reach human eyes.

This project started from that frustration and turned into my first professional data project. It simulates how Applicant Tracking Systems (ATS) score resumes and shows why most get filtered out.

# What this project does

- Reads and cleans raw resume data  
- Compares each resume to a real job description (JD)  
- Finds matching and missing keywords  
- Scores the resume based on relevance to the JD  
- Gives a friendly recommendation on what to add  
- Checks if formatting is ATS-friendly (bullet points, structure)  
- Shows how your resume ranks compared to others

# Sample Output

📄 ATS Score: 4/10

Matched Keywords: python, sql
Missing Keywords: tableau, data wrangling, presentation, excel

Recommendation:
Resume is under-matching. Try including these key terms:
• tableau, data wrangling, excel

Format Feedback:
No bullet points detected
No 'Experience' section found

# Project Structure

ats-resume-analysis/
├── resume_analysis.ipynb        
├── data/
│   ├── resumes.csv              
│   └── job_description.txt      
├── requirements.txt             
└── README.md                   

# Tech & Tools

- Python
- pandas, nltk, regex
- matplotlib, seaborn
- Text preprocessing (stopwords, tokenization)
- Basic scoring logic (overlap with job keywords)
- Friendly feedback generation

# Dataset Used

- Resume Dataset from Kaggle
[Link](https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset)

- Job description manually added (`job_description.txt`)

# Why I Made This

I wanted to get better at Python.  
I wanted to understand why I didn’t get interviews.  
I wanted to turn something that felt bad into something that helps people.

This project is beginner-friendly, personal, and real.  
If you're also a student figuring things out maybe this helps.

# What You Can Learn From This Repo

- How to turn a personal experience into a portfolio project  
- How basic NLP can be applied to real career problems  
- How to write clean, structured code that gives human feedback  
- That rejection can be re-framed as analysis

# What’s Next

Want to build on this?
- Make it a Streamlit app so people can upload resumes
- Add skill-category tagging (e.g., data viz, soft skills)
- Train a simple classifier for resume types
- Compare multiple JDs at once

# Created by Nafsiha Ahmed

Second-year undergrad • Mathematics & Computing • Data-curious  
Connect with me on [LinkedIn](https://www.linkedin.com/in/nafsihaahmed)