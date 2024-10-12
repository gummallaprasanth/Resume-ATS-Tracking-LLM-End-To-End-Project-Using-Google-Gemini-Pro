# Resume-ATS-Tracking-LLM-End-To-End-Project-Using-Google-Gemini-Pro

## Overview

This project aims to develop an end-to-end system that leverages Google Gemini Pro for tracking and analyzing resumes through Applicant Tracking Systems (ATS). By integrating machine learning capabilities, this solution enhances the recruitment process by improving resume screening efficiency and candidate matching.

## Features

Resume Parsing: Automatically extracts relevant information from resumes.

ATS Integration: Seamlessly integrates with popular ATS platforms.

Candidate Ranking: Uses LLM to rank candidates based on job descriptions.

Analytics Dashboard: Provides insights on applicant pools and hiring metrics.

Customizable Filters: Allows recruiters to set specific criteria for candidate selection.

## Technologies Used

Google Gemini Pro: For advanced language processing and model training.

Python: Primary programming language for the implementation.

Streamlit: Web framework for creating the API.

## Usage

Access the API: ""

Upload a resume: Use the /upload endpoint to submit resumes for parsing.

Get candidate rankings: Call the /rank endpoint with job description and resume data to receive ranked candidates.

## Steps Involved In the Project:

1.Create new Environment and import all Dependencies.

2.Create app.py file

  a.Create a function for extracting the text from the pdf using PyPDF2.

  b.Create a function for the comparing the resume with the job description using gemini llm model and give the good response(prompt should be important it plays a key role)
  
