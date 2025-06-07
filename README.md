# 🎯ZENITH – Your AI Career Partner

**Zenith** is a modern, AI-powered career development platform that helps you navigate the job market with confidence. Whether you're crafting the perfect resume, writing a compelling cover letter, or preparing for interviews — Zenith has your back. Every feature is tailored to your industry, skills, and goals.

---

## 🚀 Features

### 🧠 AI-Powered Resume Builder
- Generate professional resumes based on your experience, skills, and industry standards.
- Custom content suggestions optimized by Gemini AI.

### ✉️ Cover Letter Generator
- Create personalized and compelling cover letters in seconds.
- AI highlights your strengths aligned with the job role.

### 🎤 Interview Preparation System
- Practice with dynamic, AI-generated questions.
- Track performance and receive smart, actionable feedback.

### 📊 Real-Time Industry Insights
- Weekly insights on:
  - Salary trends
  - In-demand skills
  - Career growth tips
- Powered by AI-driven market analysis.

### 🛡️ Secure User Data
- Authentication via **Clerk**.
- End-to-end encryption and best security practices to keep your data safe.

### 📝 Fully Editable Content
- Intuitive markdown editor to modify and tailor AI-generated resumes and cover letters as you wish.

### 📈 Progress Tracking
- Visual analytics for tracking interview prep.
- Get personalized tips for continuous improvement.

---

## 📦 Getting Started

### ✅ Prerequisites
Make sure you have the following installed or set up:

- [Node.js](https://nodejs.org/) (Latest LTS)
- [Vercel](https://vercel.com/) account for deployment
- [Clerk](https://clerk.dev/) account for authentication

---

### 🧪 Installation

1. **Clone the repository**
```bash
git clone https://github.com/meantaraa/ai-career-partner-zenith.git
cd ai-career-partner-zenith
```

2. **Install dependencies**
```bash
npm install
```

3. **Run the development server**
```bash
npm run dev
```

---

## ⚙️ Environment Variables

Create a `.env` file in the project root and populate it as follows:

## ⚙️ Environment Variables

Create a `.env` file in the root of your project and add the following keys:

```env
# Database
DATABASE_URL=
DIRECT_URL=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# AI & External APIs
GEMINI_API_KEY=
INNGEST_EVENT_KEY=

# Email Delivery (e.g., Resend)
RESEND_API_KEY=
```

> 🔐 **Note:** Never commit your `.env` file or sensitive keys to version control. Use `.env.example` for sharing required variable names.

---

## 🌐 Deployment

Zenith is deployed and live at:  
🔗 [https://ai-career-partner-zenith.vercel.app](https://ai-career-partner-zenith.vercel.app)

---

## 🤝 Contributing

We welcome contributions!

1. **Fork** the repository  
2. **Create** a new branch  
```bash
git checkout -b feature/your-feature
```
3. **Commit** your changes  
```bash
git commit -m "Add your feature"
```
4. **Push** to your fork  
```bash
git push origin feature/your-feature
```
5. **Open** a Pull Request

---

## 🛠 Built with ❤️ by Antara Chanda

---

## 📜 License

This project is licensed under the **MIT License**.