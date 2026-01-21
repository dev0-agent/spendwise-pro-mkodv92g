# SpendWise Pro

> Master your money with real-time insights and seamless tracking.

## Overview
SpendWise Pro is a high-performance, full-stack budget manager built to provide immediate clarity on your financial health. Leveraging the power of TanStack Start, it delivers server-rendered views for speed and SEO, combined with a rich interactive client experience. It features transaction tracking, budget management, and visual analytics, all backed by a local SQLite database for privacy and ease of use.

## Tech Stack
- **Framework:** TanStack Start (React + SSR)
- **Routing:** TanStack Router
- **Styling:** Tailwind CSS
- **Database:** SQLite (via Better-SQLite3)
- **ORM:** Drizzle ORM
- **Validation:** Zod

## Features
- 📊 **Real-time Dashboard:** Instant view of your total balance and monthly flows.
- 💸 **Transaction Tracking:** Easily log income and expenses with categorization.
- 🎯 **Budget Goals:** Set monthly limits per category and track your progress.
- 📈 **Visual Analytics:** Interactive charts showing spending distribution.
- ⚡ **Instant Load:** Server-side rendering ensures data is ready before the page loads.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd spendwise-pro
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Initialize the database**
   ```bash
   npm run db:push
   npm run db:seed
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000` to start managing your budget.

## Documentation
- [Task List](./TASKLIST.md) - Detailed breakdown of development tasks.
- [Learnings](./LEARNINGS.md) - Technical decisions and lessons learned.
- [Rules](./.dev0/RULES.md) - Project coding standards.