# 💼 NextStepX – Smart Career & Resume Coach Platform

An AI-powered full-stack web application designed to help users build stronger resumes, analyze job opportunities, and receive personalized career guidance in real time.

---

## 🚀 Overview

**NextStepX** functions as an intelligent career mentor by integrating large language models with modern web technologies.

It enables users to:

* Interact with an AI coach (text + voice)
* Upload resumes and receive actionable feedback
* Analyze job descriptions
* Generate optimized professional summaries
* Get tailored career recommendations

Built as a **scalable, production-ready AI SaaS platform**.

---

## ✨ Core Features

* 🤖 AI Career Coach (text + voice interaction)
* 📄 Resume upload with instant AI evaluation
* 📊 Job description analysis with improvement suggestions
* 🧠 AI-generated professional summaries
* 🔐 Secure authentication using Clerk
* ⚡ Real-time data synchronization via Convex
* 🎨 Modern UI with Tailwind CSS + Shadcn UI
* 🚀 High-performance rendering using Next.js

---

## 🏗 Tech Stack

### Frontend

* Next.js
* React
* Tailwind CSS
* Shadcn UI

### AI & Voice

* Gemini AI
* Vapi Voice API

### Backend & Database

* Convex (Realtime Database)

### Authentication

* Clerk

---

## ⚙️ Environment Setup

Create a `.env.local` file and configure the following variables:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

---

## 🛠 Getting Started

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Configure environment variables
4. Start the development server:

```bash
npm run dev
```

---

## 🎯 Use Cases

* ✅ Resume enhancement projects
* ✅ Hackathons & AI demos
* ✅ Full-stack development practice
* ✅ Career guidance platforms
* ✅ Startup MVPs

---

## 🔮 Future Enhancements

* 📌 ATS score optimization
* 📌 LinkedIn profile analyzer
* 📌 Multi-language support

