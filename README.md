# ResView: Applicant Tracking System

This is a Streamlit application that serves as an Applicant Tracking System (ATS). It allows users to upload resume files (in PDF format) and compare them against a provided job description. The system calculates similarity scores between the resumes and the job description, and provides feedback on missing keywords and overall suitability for the role.

## Features

- Upload multiple resume files (PDF) at once
- Enter a job description manually or load it from a text file
- Compare resumes against the job description using the HuggingFace BERT model
- Calculate similarity scores between resumes and the job description
- Identify missing keywords from the resumes based on the job description
- Filter resumes based on a customizable similarity threshold
- User-friendly interface with tabs for easy navigation

## Installation

1. Clone the repository: 
```
git clone https://github.com/Harshvardhan2164/Applicant-Tracking-System-Minor-Project.git
```
2. Navigate to the project directory: 
```
cd Applicant-Tracking-System-Minor-Project
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```
4. Run the Streamlit application:
```
streamlit run application.py
```