# Applicant Tracking System (ATS)

## Project Overview
This project is a simplified Applicant Tracking System (ATS) built as part of an academic internship project.  
The system allows applicants to submit their personal details and resume, while administrators can view, manage, and export applicant data.

---

## Features

### Applicant Module
- Application form with validation
- Resume upload (PDF)
- Confirmation after successful submission

### Admin Module
- Secure admin login
- View all applicants in a dashboard
- View detailed applicant information
- Download uploaded resumes
- Export applicant data as CSV

### Additional Feature
- Resume keyword matching to assist in shortlisting candidates

---

## Tech Stack
- Frontend: React + TypeScript
- UI: Tailwind CSS + shadcn-ui
- Backend Logic: Simulated API / Local state (for demo)
- Build Tool: Vite

---

## Project Structure
src/
├── pages/
│ ├── Apply.tsx
│ ├── AdminLogin.tsx
│ ├── Dashboard.tsx
│ └── ApplicantDetail.tsx
├── components/
│ ├── ApplicantForm.tsx
│ ├── ApplicantTable.tsx
│ └── ProtectedRoute.tsx
├── utils/
│ └── keywordMatcher.ts
└── App.tsx
