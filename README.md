# 🌟 SensiAI – Your AI-Powered Career Coach

SensiAI is a full-stack AI-driven career coaching platform that delivers personalized industry insights, mock interview prep, resume building, and cover letter generation — powered by Google Gemini AI.

Built with **Next.js 15**, **React 19**, **Tailwind CSS**, **Prisma**, **NeonDB**, **Clerk Authentication**, **Inngest**, and **Shadcn UI**, this project showcases expertise across the modern full-stack web development ecosystem.

![SensiAI Preview](./public/sensiai-cover.png)

---

## 🚀 Features

- 🔐 **Clerk Authentication** – Secure login/signup flows with a custom UI.
- 🧠 **Gemini AI Integration** – Industry insights, mock interview questions, and AI-generated resumes & cover letters.
- 📆 **Scheduled Tasks with Inngest** – Weekly email insights delivered automatically.
- 📝 **Resume & Cover Letter Builder** – Markdown-based resume creation with PDF export.
- 📊 **Interview Performance Dashboard** – Analyze strengths and weaknesses visually.
- 🧩 **Onboarding System** – Capture user goals, industry, and role to personalize experience.

---

## 🛠️ Tech Stack

| Frontend         | Backend             | Database      | Auth    | AI        | Dev Tools      |
|------------------|---------------------|---------------|---------|-----------|----------------|
| React 19         | Next.js 15 (App dir) | NeonDB (PostgreSQL) | Clerk  | Gemini API | Inngest, Prisma |
| Tailwind CSS     | API Routes & Actions | Prisma ORM    |         |           | Shadcn UI      |

---

## 📁 Folder Structure

/app
/auth → Custom login/signup
/onboarding → User onboarding form & logic
/dashboard → Interview stats, resume builder
/api → Backend routes for AI, user data
/lib
/utils → API hooks, helpers
/inngest → Background jobs
/prisma
schema.prisma → DB models
/public
assets, images

yaml
Copy
Edit

---

## 🧑‍💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sensiai.git
cd sensiai
2. Install Dependencies
bash
Copy
Edit
pnpm install
# or
npm install
3. Setup Environment Variables
Create a .env file based on .env.example:

env
Copy
Edit
DATABASE_URL=your_neondb_url
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
GOOGLE_GEMINI_API_KEY=your_gemini_api_key
NEXT_PUBLIC_CLERK_FRONTEND_API=...
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
4. Setup Prisma and DB
bash
Copy
Edit
npx prisma db push
5. Run the App Locally
bash
Copy
Edit
npm run dev
# or
pnpm dev






