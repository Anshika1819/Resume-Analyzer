# CV Analyzer - AI-Powered Resume Analysis

## 📌 Project Overview

CV Analyzer is a web-based application that uses Google's Gemini AI to analyze resumes/CVs and provide detailed insights. Users can upload their CV in PDF, DOC, or DOCX format and receive a structured analysis including skills, experience, education, strengths, and improvement recommendations.

## 🚀 Features

* 📄 Upload CV/Resume (PDF, DOC, DOCX)
* 🤖 AI-powered resume analysis using Gemini AI
* 👤 Extract personal information
* 🛠️ Identify technical and soft skills
* 💼 Analyze work experience
* 🎓 Extract educational background
* ⭐ Highlight strengths and achievements
* 📈 Provide career recommendations
* 🎨 Modern and responsive user interface
* 🖱️ Drag-and-drop file upload support

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### AI Integration

* Google Gemini 1.5 Pro API

### Storage

* Browser LocalStorage

---

## 📂 Project Structure

```text
CV-Analyzer/
│
├── index.html          # Main upload page
├── analysis.html       # Analysis results page
├── styles.css          # Styling file
├── script.js           # Upload and AI analysis logic
├── results.js          # Results display logic
└── README.md
```

---

## ⚙️ How It Works

1. User uploads a CV.
2. File content is extracted.
3. Resume data is sent to Gemini AI.
4. Gemini analyzes the resume and returns:

   * Personal Information
   * Summary
   * Skills
   * Experience
   * Education
   * Strengths
   * Recommendations
5. Results are stored in LocalStorage.
6. User is redirected to the analysis page to view insights.

---

## 📊 Output Example

The AI generates structured information such as:

```json
{
  "personalInfo": "John Doe, johndoe@gmail.com",
  "summary": "Software Engineer with 3 years of experience",
  "skills": ["Java", "Python", "SQL", "Communication"],
  "experience": "Worked at ABC Company...",
  "education": "B.Tech in Computer Science",
  "strengths": "Strong problem-solving abilities",
  "recommendations": "Add more project details"
}
```

---

## 🚀 Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/cv-analyzer.git
```

### Navigate to Project

```bash
cd cv-analyzer
```

### Run Project

Simply open:

```text
index.html
```

in your browser.

Or use VS Code Live Server:

```bash
Right Click → Open with Live Server
```

---

## 🎯 Future Enhancements

* Resume score calculation
* ATS (Applicant Tracking System) compatibility checking
* Resume improvement suggestions
* Multiple resume templates
* Download analysis as PDF
* Job role matching
* Skill gap analysis
* Authentication system

---

## 👨‍💻 Author

**Anshika**

Developed as an AI-powered Resume Analysis project using Gemini AI.
