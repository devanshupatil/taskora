# Weekly to Monthly Task Planner

## 1. Project Overview

A personal productivity app where users can plan their week, organize tasks, set monthly goals, track progress, and manage deadlines in one place.

**Core idea:** Help users answer three questions:
- What do I need to do today?
- What do I need to finish this week?
- What am I trying to achieve this month?

## 2. Core Features (MVP)

### Task Management
- Add, edit, delete, and organize tasks
- Task title and description
- Priority: High, Medium, Low
- Due date and optional time
- Status: To do, In progress, Done
- Categories such as Work, Personal, Learning, and Health
- Subtasks and checklists

### Weekly Planner
- Monday–Sunday view
- Move tasks between days
- See unfinished tasks
- Plan the next week
- View daily workload

### Monthly Calendar
- Monthly calendar grid
- Display tasks on their due dates
- Show upcoming deadlines
- Set monthly goals
- Navigate between months

### Progress Dashboard
- Tasks completed today
- Weekly completion percentage
- Monthly completion percentage
- Pending and overdue tasks
- Progress bars and charts

## 3. Productivity Features

### Goal Setting
Create larger goals and connect smaller tasks to them.

Example: **Learn React in 30 days**
- Week 1: Learn components
- Week 2: Learn hooks
- Week 3: Build a project
- Week 4: Deploy the project

### Recurring Tasks
Automatically repeat tasks:
- Every day
- Selected days of the week
- Every week
- Every month

Examples:
- Exercise every Monday, Wednesday, and Friday
- Study for one hour every day
- Review goals every Sunday
- Pay bills on the 5th of every month

### Reminders and Notifications
- Remind users before deadlines
- Daily morning task summary
- Evening unfinished-task reminder
- Overdue-task notifications

### Time Tracking and Focus Timer
- Estimate task duration
- Record actual time spent
- Pomodoro timer (for example, 25 minutes)
- Track weekly focus time
- Compare estimated time with actual time

### Notes and Attachments
- Notes and links
- Documents and images
- Reference materials
- Meeting notes
- Task-specific checklists

## 4. Advanced Features

### AI Task Assistant
- Break large tasks into smaller steps
- Suggest a realistic daily schedule
- Identify tasks that may need more time
- Summarize the week
- Suggest tasks to reschedule

Example task: **Prepare for my full-stack developer interview**
Suggested subtasks:
1. Revise JavaScript fundamentals
2. Practice React interview questions
3. Revise Node.js and Express
4. Practice SQL queries
5. Complete one mock interview

### Task Dependencies
Some tasks cannot start until others are complete. For example, finish designing a website before starting frontend development.

### Habit Tracker
- Daily streaks
- Weekly habit completion
- Monthly consistency calendar
- Personal targets, such as reading 20 minutes a day

### Weekly Review
At the end of each week, show:
- What did I finish?
- What did I postpone?
- What took longer than expected?
- What should I focus on next week?

### Search, Filters, and Saved Views
Filter tasks by:
- Priority
- Date
- Category
- Status
- Tags

Allow users to save useful views such as **High priority this week** or **All overdue tasks**.

## 5. Suggested App Screens

1. **Dashboard** — Today's tasks, progress, upcoming deadlines, and quick add.
2. **My Tasks** — All tasks with search, filters, sorting, and categories.
3. **Weekly Planner** — Seven-day view with task scheduling.
4. **Monthly Planner** — Monthly calendar, deadlines, and goals.
5. **Goals** — Long-term goals, milestones, and linked tasks.
6. **Habits** — Recurring habits, streaks, and consistency.
7. **Analytics** — Completion trends, focus time, and weekly reports.
8. **Settings** — Themes, notifications, account, and data export.

## 6. Suggested Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React + TypeScript |
| Styling | Tailwind CSS |
| Backend | Node.js + Express |
| Database | PostgreSQL / Supabase |
| Authentication | Supabase Auth |
| Notifications | Web Push / email |
| Charts | Recharts |
| Hosting | Vercel + backend hosting |

This is a suggested stack, not a strict requirement. Choose based on the app's needs and deployment plan.

## 7. Important Product Design Decision

Support both:
- **Scheduled tasks:** Have a specific date and time.
- **Flexible tasks:** Need to be completed within a period, but do not need a specific time.

Do not force every task to have a time. Many users plan tasks they want to finish sometime during the week.

## 8. Development Roadmap

### Phase 1 — MVP (Week 1)
- [ ] Add, edit, and delete tasks
- [ ] Due dates, priority, and status
- [ ] Weekly and monthly views
- [ ] Basic dashboard
- [ ] Local or cloud data storage

### Phase 2 — Productivity (Week 2)
- [ ] Categories and filters
- [ ] Recurring tasks
- [ ] Reminders
- [ ] Subtasks and notes
- [ ] Progress tracking

### Phase 3 — Advanced (Weeks 3–4)
- [ ] Goals and milestones
- [ ] Time tracking and Pomodoro
- [ ] Analytics and weekly reviews
- [ ] Habit tracker
- [ ] AI task breakdown

## 9. Project Name Ideas

Names below are creative suggestions only. Domain, app-store, and trademark availability have not been verified.

### Modern and Professional
- **Taskora** — Task + aura; a modern productivity identity
- **Planora** — Plan + aura; suitable for weekly and monthly planning
- **TaskFlow** — Tasks and workflow
- **Daywise** — Day-by-day planning
- **Plannix** — Short, tech-oriented planning name
- **Organizo** — Organization-focused and approachable

### Short and Catchy
- Tiqo
- Planny
- Taskly
- Dozen
- Doto
- Zentro
- Flowly
- Ticksy
- Nexday
- Timo

### Meaningful Names
- **Daymark** — Mark what matters each day
- **NextStep** — Focus on the next action
- **Momentum** — Keep making progress
- **OneWeek** — Plan and finish your week
- **Milesto** — Milestones and progress
- **ClearDay** — A clearer, less cluttered day
- **TaskNest** — A home for tasks
- **TimeTrail** — Track your journey over time

### Premium / SaaS-Style
- Veyra
- Orbito
- Tandem
- Avora
- Nuvio

### Initial Shortlist
- **Planora** — “Plan your week. Own your month.”
- **Taskora** — “Every task, one clear direction.”
- **Daymark** — “Make today count.”

Before choosing a final name, check domain availability, app-store listings, and relevant trademarks.

## 10. Recommended Starting Scope

Start with a simple, reliable planner:
1. Task CRUD (create, read, update, delete)
2. Due dates, priority, and status
3. Weekly and monthly views
4. Dashboard with pending, completed, and overdue counts
5. Categories and basic filters

Add reminders, recurring tasks, goals, analytics, and AI after the core planning experience works smoothly.
