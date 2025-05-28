## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Assets & Code](#snippets)
6. 🚀 [More](#more)

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- OpenAI API
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Income and Expense Input**: Allows users to input their income and expenses.

👉 **Budget Management**: Enables users to manage their budgets effectively.

👉 **Personalized Financial Advice**: Provides detailed financial advice based on user-specific financial data using OpenAI's GPT-4 model.

👉 **Responsive Design**: Ensures a seamless experience across different devices.


**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=p
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
NEXT_PUBLIC_OPENAI_API_KEY=

NEXT_PUBLIC_DATABASE_URL=

```

Replace the placeholder values with your actual OpenAI credentials. You can obtain these credentials by signing up on the [OpenAI website](https://openai.com/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.