# CrackAI

# 🚀 CrackAI – AI-Powered Career Insight & Resume Platform

CrackAI is a cutting-edge, AI-integrated career assistance platform built using modern technologies like *Next.js*, *PostgreSQL*, *Prisma*, *Tailwind CSS*, and *Shadcn UI*. It provides real-time salary trends, personalized interview preparation, and intelligent ATS-friendly resume generation. Whether you're a student, job seeker, or switching domains, Crack AI has everything you need to get ahead.

## 🌟 Key Features

### 📊 1. Industry Salary Insights (Auto-updated Weekly)
- Get real-time, role-based salary data (Min, Median, Max) for different domains.
- Covers *50+ industries* including Tech, Design, Finance, Marketing, HR, Management, and more.
- Insights are auto-refreshed every *7 days* using trusted datasets and ML pipelines.

### 🧠 2. Unlimited Mock Tests & Smart Feedback
- Take unlimited *AI-generated mock interview tests* – no limit on question sets.
- Question bank is *dynamically generated via AI*, so you never get the same test twice.
- Post-test report includes:
  - Your score
  - Correct/Incorrect analysis
  - Explanations for each question
  - AI-powered personalized *feedback* on weak topics and suggested practice.

### 📄 3. Resume & CV Generator (AI-Enhanced)
- Generate *ATS-optimized resumes* using AI suggestions.
- Enter your *industry, role, and skills*, and let AI build a tailored resume/CV.
- Key features:
  - Real-time resume editing with live preview
  - Multiple section customizations
  - One-click PDF download
  - Smart AI hints to improve sections
  - Resume saving for future edits

### 🔐 4. Authentication & User Data Security
- Secure login system with encrypted sessions.
- All resumes, test results, and personal data stored safely using PostgreSQL via Prisma.

## 🧑‍💻 Tech Stack Used

| Layer              | Technology                     |
|--------------------|---------------------------------|
| Frontend           | Next.js (App Router), React.js |
| Styling            | Tailwind CSS, Shadcn UI        |
| Backend API Routes | Next.js API                    |
| ORM                | Prisma                         |
| Database           | PostgreSQL                     |
| AI Integration     | Gemini API                     |
| Auth               | JWT Middleware                 |
| Deployment         | Vercel                         |

## 🛠 Installation & Setup (Local Dev)

```bash
# 1. Clone the repository
git clone https://github.com/gutanaitik46/CrackAI.git

# 2. Navigate to the folder
cd CrackAI

# 3. Install dependencies
npm install

# 4. Setup environment variables
cp .env.example .env
# Fill in: DATABASE_URL, NEXTAUTH_SECRET, GEMINI_API_KEY, etc.

# 5. Run Prisma migrations
npx prisma generate
npx prisma migrate dev

# 6. Start the development server
npm run dev
