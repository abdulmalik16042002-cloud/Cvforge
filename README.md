# CVForge: ATS Resume Maker

CVForge is a web app that allows users to generate ATS-friendly resumes in **Word (.docx) format**. Built with **React.js** for the frontend and **Vercel serverless functions** for backend Word generation.

---

## **Features**

- Paste your resume text directly into the app.
- Generate a real Word `.docx` file instantly.
- ATS-friendly formatting applied automatically.
- Fully online via Vercel.

---

## **Tech Stack**

- **Frontend:** React.js (Vite)
- **Backend:** Node.js + Serverless Function (`/api/generate-cv.js`)
- **Resume Generation:** [docx](https://www.npmjs.com/package/docx)
- **Deployment:** Vercel

---

## **Getting Started (Local Development)**

### **1. Clone the repository**

```bash
git clone https://github.com/yourusername/cvforge-vercel.git
cd cvforge-vercel
# Cvforge
cvforge-vercel/ ├── api/ │   └── generate-cv.js ├── public/ │   └── index.html ├── src/ │   ├── App.js │   └── styles.css ├── package.json └── vite.config.js
