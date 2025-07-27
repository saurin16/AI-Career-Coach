Here’s a **polished and professional README** for your **AI-Powered Career Coach App** project:

---

# AI-Powered Career Coach App

A **full-stack AI career coaching platform** that helps job seekers elevate their **resumes, cover letters, and interview preparation** with real-time **AI insights** and **industry trends**. Built with **Next.js, Prisma, PostgreSQL, Clerk, and Google Gemini API**, the app combines **modern UI/UX** and **AI-powered features** to deliver a production-grade SaaS solution.

---

## Features

### **Core AI Features**

* **ATS-Optimized Resume Builder**
  Build resumes in markdown or form mode, enhanced via AI for better phrasing and keyword optimization.
* **AI Cover Letter Generator**
  Generate personalized cover letters tailored to job descriptions and user profiles.
* **Mock Interview Module**
  AI-generated role-specific questions with real-time feedback and performance tracking.

### **Industry Insights Dashboard**

* Weekly updated insights on **salary trends**, **market demand**, and **recommended skills**.
* Automated updates using **Inest background job scheduling** (Cron jobs).

### **Modern UI/UX**

* Built with **Next.js 13**, **Tailwind CSS**, and **Shad CN UI** for a sleek, responsive interface.
* Interactive charts and markdown-based resume previews with **live PDF export**.

### **User Authentication & Data Management**

* **Clerk integration** for secure authentication (Google/email login).
* **Prisma ORM** with PostgreSQL for structured relational database design.

### **Deployment & Scalability**

* Deployed on **Vercel** with continuous integration and automated backend tasks via Inest.
* Modular API design for scalable growth and future feature expansion.

---

## Tech Stack

* **Frontend:** Next.js 13 (App Router), Shad CN UI, Tailwind CSS, React Hook Form, Zod
* **Backend:** Prisma ORM, PostgreSQL, Inest for background jobs
* **Authentication:** Clerk
* **AI Services:** Google Gemini API
* **Deployment:** Vercel (Serverless + CI/CD)
* **Utilities:** Markdown rendering, html2pdf for PDF export, recharts for data visualization

---

## Key Highlights

* 🤖 **AI-First Experience:** Resume improvements, mock interviews, and cover letter generation powered by Gemini API.
* 🔄 **Automated Insights:** Weekly Cron jobs ensure job seekers always see the latest market data.
* 🎨 **Responsive Modern UI:** Built with Shad CN UI and Tailwind CSS for a professional, mobile-friendly experience.
* 🚀 **Production Ready:** Includes deployment strategies, environment management, and CI/CD workflows.

---

## Architecture Overview

**Frontend:** Next.js handles UI rendering with server/client component architecture.
**Backend:** Prisma + PostgreSQL manage relational data (users, resumes, assessments, insights).
**AI Layer:** Google Gemini API powers generative features (resume, interview, cover letter).
**Background Jobs:** Inest runs weekly updates for industry insights.
**Deployment:** Hosted on Vercel with automatic scaling and edge caching for performance.

---

## Setup Instructions

### Prerequisites

* Node.js (v18+)
* PostgreSQL database
* Clerk account (for auth)
* Google Gemini API key
* Vercel account for deployment

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```
