<h1 align="center">💸 AI-Finance-Platform</h1>

<p align="center">
  A smart, modern finance tracking platform powered by AI — manage accounts, track expenses, generate insights, and receive smart email reports.
</p>

---

## 🚀 Features

- 🔐 User Authentication via Clerk  
- 📊 Dashboard to track accounts and transactions  
- 📅 Budget planning & monthly budget alerts  
- 📤 Email notifications for budget alerts & reports  
- 📈 Insights with AI-generated financial summaries  
- 🧾 Receipt Scanner using Gemini Vision  
- ⏱️ Automated Cron jobs via Inngest  
- 🌐 Deployed with Vercel

---

## 🧱 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Clerk-3B82F6?style=for-the-badge&logo=clerk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Inngest-FC575E?style=for-the-badge&logo=cloudflare&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</p>

---

## 🖼️ Demo Screenshot

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/AryanJiyani007/AI-Finance-Platform/main/public/demo.png" alt="AI-Finance-Platform Demo" />
</p>


## ⚙️ Getting Started

### 1️⃣ Clone the Repository

git clone https://github.com/AryanJiyani007/AI-Finance-Platform.git
cd AI-Finance-Platform

### 2️⃣ Clone the Repository

npm install

### 3️⃣ Configure Environment Variables

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY

CLERK_SECRET_KEY

NEXT_PUBLIC_CLERK_SIGN_IN_URL

NEXT_PUBLIC_CLERK_SIGN_UP_URL

# Supabase

DATABASE_URL

DIRECT_URL

# Arcjet

ARCJET_KEY

# Gemini AI

GEMINI_API_KEY

# Resend Email API

RESEND_API_KEY

### 4️⃣ Setup the Database

npx prisma db push

To seed dummy transaction data, visit:

http://localhost:3000/api/seed

### 5️⃣ Run Development Server

npm run dev


