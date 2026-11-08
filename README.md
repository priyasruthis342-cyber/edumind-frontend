# EduMind AI — Frontend (React + Vite)

Interactive web application for EduMind AI, built with React, TypeScript, Tailwind CSS, Lucide icons, and Mermaid.js diagrams.

## Features
- **University Syllabus & Exam Question Bank:** 2-mark, 3-mark, 8-mark, and 12-mark university exam questions with on-demand answer breakdowns.
- **AI Study Assistant Sidebar:** Context-aware study tutor with real-time Mermaid.js flowchart rendering.
- **Continuous Voice Input:** Manual microphone control with a stop button for speech-to-text.
- **Full OCR Document Extraction:** Multi-page PDF and scanned document reader.
- **Audio Story Lessons:** Conversational voice lessons in Tamil & English.
- **Dynamic API Routing:** Seamlessly connects to external backend via `VITE_API_URL`.

---

## Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Configure Environment Variables
Copy `.env.example` to `.env`:
```bash
cp .env.example .env
```
Set `VITE_API_URL` to your backend URL:
- Local development: `http://localhost:5050`
- Production (e.g. Render): `https://your-edumind-backend.onrender.com`

### 3. Run Development Server
```bash
npm run dev
```

### 4. Build for Production
```bash
npm run build
```
Build output is saved to the `dist/` directory.

---

## Deployment (Vercel / Render / Netlify)
- **Framework:** Vite
- **Build Command:** `npm run build`
- **Output Directory:** `dist`
- **Environment Variables:** Set `VITE_API_URL`, `VITE_SUPABASE_URL`, `VITE_SUPABASE_ANON_KEY`, and `VITE_RAZORPAY_KEY_ID`.
