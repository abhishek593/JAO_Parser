# JAO_Parser
Resume Parser for Amdocs Round 2, 2022  

User can upload their Resume, and the application will parse all the keywords in the Resume for further procesing.
---

### Technologies Used
Django  
Python 
### Install Requirements
First, create a python virtual environment. Then install requirements as-
```
pip install -r requirements.txt
```
### Setup
```
python manage.py makemigrations
python manage.py migrate
```
### Usage
In development server  
User website - 'http://127.0.0.1:8000/'  

## Usage
1. First visit 'http://127.0.0.1:8000/resume/' and uplaod a resume. Verify that your file has been uploaded. It will be visible on the same page.
2. Then visit 'http://127.0.0.1:8000/resume/resume_text/' to view all the parsed keywords from the resume.

## Limitations
Currently, only the latest resumes uploaded are visible on the link 'http://127.0.0.1:8000/resume/resume_text/'. We will improve this functionality to redirect the user 
directly to this page when they upload their resume.
