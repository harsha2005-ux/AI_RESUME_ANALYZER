<<<<<<< HEAD
# ResumeAI - AI Resume Analyzer

## Features
- Register/login/logout
- PDF and DOCX upload
- Resume text extraction
- Skill detection
- Missing-skill analysis
- ATS-style score
- Job recommendation
- Course suggestions
- Interview questions
- User resume history
- Admin dashboard

## Run on Windows (VS Code)
1. Open the `ai_resume_analyzer` folder in VS Code.
2. Open Terminal.
3. Create a virtual environment:
   `python -m venv venv`
4. Activate it:
   PowerShell: `venv\Scripts\Activate.ps1`
   CMD: `venv\Scripts\activate`
5. Install packages:
   `pip install -r requirements.txt`
6. Create the database and admin:
   `flask --app app init-db`
7. Run:
   `python app.py`
8. Open:
   `http://127.0.0.1:5000`

Admin login:
- Email: admin@resumeai.com
- Password: Admin@123

## Important
This is a working student-project MVP. The ATS score is a transparent rule-based estimate, not a real recruiter ATS score. For production, replace the skill rules with an AI/NLP service, add CSRF protection, secure file scanning/storage, email verification, password reset, and a production database.
=======
# ResumeAI
<<<<<<< HEAD
AI-powered resume builder and analyze
>>>>>>> 60f7995ef24101607c11d7bbf50dd2394d330bc7



=======
An AI-powered resume analyzer web application
>>>>>>> 82dbd1c0f9192598813d445aaafda176e685f3a7
