# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Initialization & Configuration**
  Initialize a new TanStack Start project. Configure Tailwind CSS for styling. Set up the basic folder structure for components, routes, and server functions. Ensure the dev server runs correctly.

- [ ] ⏳ **Database Schema & ORM Setup**
  Install Drizzle ORM and Better-SQLite3. Define the database schema for 'transactions' (id, amount, date, description, category, type) and 'categories' (id, name, budget_limit). Create a seed script to populate initial categories.

## Phase 2

- [ ] ⏳ **Core Server Functions Implementation**
  Implement TanStack Start server functions (RPC) for the core CRUD operations: `getTransactions`, `addTransaction`, `updateTransaction`, and `deleteTransaction`. Ensure inputs are validated using Zod schemas.

- [ ] ⏳ **Application Layout & Navigation**
  Create the main application shell using TanStack Router. Implement a responsive sidebar/header navigation menu linking to Dashboard, Transactions, and Budget pages. Include a layout route wrapper.

- [ ] ⏳ **Transaction Form Component**
  Build a reusable form component for adding and editing transactions. Use React Hook Form or TanStack Form with Zod validation. Connect it to the server functions created in task-3.

- [ ] ⏳ **Transaction List View**
  Develop a data table or list view to display transactions. Implement server-side data loading using `createFileRoute` loaders. Add basic formatting for currency and dates.

- [ ] ⏳ **Dashboard Summary Cards**
  Create a new server function to calculate aggregates (Total Balance, Income, Expenses). Build UI cards to display these metrics on the main dashboard route.

## Phase 3

- [ ] ⏳ **Budget Management Feature**
  Implement a view to list categories and edit their monthly budget limits. Update the database schema if necessary (or use the existing 'categories' table). Show progress bars indicating spending vs. budget.

- [ ] ⏳ **Spending Visualization Charts**
  Integrate a charting library (e.g., Recharts) to display a Pie Chart of spending by category and a Bar Chart of monthly activity. Fetch aggregated data via a new server function.

## Phase 4

- [ ] ⏳ **UI Polish & Responsive Design**
  Refine the styling using Tailwind CSS. Ensure all forms and tables look good on mobile devices. Add empty states for lists and loading skeletons for data fetching.

---

_Last updated by dev0 automation_
