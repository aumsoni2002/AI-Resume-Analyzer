# ResMind – AI Resume Analyzer

ResMind is a simple AI-powered web app that helps you check how well your resume matches a job description. It gives you a score, shows missing keywords, and suggests ways to improve tone, structure, content, and skills.

👉 **Try it here:** [Live App](https://puter.com/app/aum-soni-ai-resume-analyzer)

---

## What it does
- Upload your resume as a PDF (drag and drop).
- Paste the job title and description.
- Get an instant ATS score (0–100).
- See feedback in four areas: Tone & Style, Content, Structure, Skills.
- Find out what keywords or skills your resume is missing.
- Keep a history of uploaded resumes on the homepage.

---

## How it works
1. You upload your resume → stored in Puter FS and previewed as an image.  
2. You add the job title and description.  
3. Resume + JD are analyzed by AI → results returned in a structured format.  
4. Feedback is saved → you can revisit it later from the dashboard.  

---

## Tech stack
- **Frontend:** React, React Router, TypeScript  
- **Styling:** Tailwind CSS  
- **State:** Zustand  
- **File handling:** react-dropzone, pdfjs-dist  
- **Infra & AI:** Puter.js (auth, storage, AI, key-value store)
