# Welcome to the Productivity Tracker (PKI)!

---

> A comprehensive, single-page web application for detailed personal productivity tracking.

PKI is designed to be a lightweight and powerful tool for anyone looking to gain insight into their daily habits and improve their focus. It operates entirely within your browser, ensuring your data remains private and local.

*   🌐 **100% Browser-Based:** No backend or server communication required.
*   🔐 **No Accounts Needed:** Your data is yours. It's all saved locally on your device.
*   ⚡ **Lightweight & Fast:** Built with vanilla technologies for maximum performance.

---

## How It Works

1.  **Log Your Activities:** Record what you're working on throughout the day.
2.  **Categorize Entries:** Assign a category to each activity, such as `Deep Work`, `Shallow Work`, or `Distraction`.
3.  **Get Your Score:** The app calculates a daily **Productivity Score** based on the duration and category of your activities, giving you an at-a-glance metric of your effectiveness.

---

## Key Features

### 🚀 Multi-Profile Support
Create and manage separate profiles to keep your work, personal projects, or different users' data completely isolated.

### 🎮 Gamification
Stay motivated with a **Daily Quest System** that challenges you with goals based on your productivity metrics (e.g., "Achieve 2 hours of Deep Work").

### 📊 Advanced Analytics
Visualize your progress with an integrated dashboard. Track trends with weekly and monthly charts showing time spent per category and your average daily scores.

### 🎨 Customization
Tailor the app to your liking. Features a clean, collapsible sidebar and multiple color themes to choose from, including **Dark**, **Light**, and **Forest**.

### 💾 Data Portability
You own your data. Perform full backups and restores from a single JSON file. You can also export daily logs individually to **.csv** or **Markdown** formats.

---

## Technology Stack

Built with a focus on simplicity and performance:
*   **JavaScript:** Vanilla JS for all core logic.
*   **HTML:** For semantic structure.
*   **Tailwind CSS:** For a modern, utility-first design.

# User Guide
This guide will help you master its features to understand and boost your daily effectiveness.

---

## 1. Getting Started: Logging Your First Activity

The core of the tracker is the **Log Activity** form. Here’s how to use it:

1.  **Activity Description:** In this field, write a brief description of what you were doing (e.g., "Wrote project report," "Replied to emails," "Watched YouTube").
2.  **Start Time & End Time:** Select the time you began and finished the activity.
3.  **Category:** This is the most important part! Choose the category that best fits your activity. This choice directly impacts your productivity score.
4.  **Add to Log:** Click this button to save the activity. It will immediately appear in the "Log for Today" table on the right.

## 2. How Your Productivity Score is Calculated

The "Productivity Score" is designed to give you a simple, at-a-glance measure of how effectively you used your time during the day. It's not just about being busy; it's about being productive.

### The Basic Idea
Every minute you log is assigned a point value based on its category. Productive tasks add points to your score, while distractions subtract them.

To be more specific, here is the exact point system based on a 30-minute block of time:

| Category | Points per 30 Mins | Purpose |
| :--- | :--- | :--- |
| **Deep Work** | +10 points | For highly focused, high-value tasks that require concentration (e.g., studying, coding, writing, strategic thinking). |
| **Shallow Work** | +4 points | For necessary but less demanding tasks (e.g., planning, organizing, responding to emails). |
| **Scheduled Leisure** | +2 points | For planned breaks and leisure activities that help you recharge (e.g., scheduled gaming, reading a book). |
| **Scheduled Break** | +2 points | For essential rests like lunch or short breaks away from your desk. |
| **Distraction** | -5 points | For unplanned, low-value activities that pull you away from your goals (e.g., aimless social media scrolling). |
| **Rabbit Hole** | -10 points | For significant, unplanned distractions where you lose a large chunk of time. |

Your **Total Score** for the day is the sum of the points from all your logged activities.

> **Pro-Tip: What's a 'good' score?**
> There's no magic number! The goal is to establish your own baseline and aim for gradual improvement. Focus on increasing your 'Total Productive Time' and seeing your 'Avg. Daily Score' rise over time.

## 3. Challenge Yourself with Daily Quests (v0.7beta)

To help you stay motivated, the tracker now includes **Daily Quests**! These are small challenges that reset every day, designed to guide you towards building productive habits.

Completing quests is simple: just use the tracker as you normally would, and the quests will automatically be marked as complete when you meet their goals.

Here are some of the quests you might encounter:

*   **Getting Started (Easy)**
    *   **First Step:** Log your first activity of the day.
    *   **Focused Sprint:** Complete a 30-minute deep work session.
    *   **Point Collector:** Earn a total of 50 points.
*   **Core Productivity (Medium)**
    *   **The Power Hour:** Log a total of 60 minutes of "Deep Work".
    *   **The 90-Minute Cycle:** Log a continuous 90-minute "Deep Work" session.
    *   **Balanced Effort:** Log at least an hour of "Deep Work" and an hour of "Shallow Work".
*   **Ambitious Goals (Hard)**
    *   **Deep Work Marathon:** Log a total of 3 hours of "Deep Work".
    *   **Elite Performer:** Earn a total of 300 points.
    *   **Perfect Focus:** Complete the day with zero time logged as a distraction.

These quests are a fun way to challenge yourself and see how consistent you can be!

## 4. Managing and Viewing Your Logs

Once you have entries, you can manage them easily.

*   **Viewing Past Days:** Use the date picker at the top of the log table to navigate to previous days and review your history.
*   **Editing an Entry:** Made a mistake? Hover over a log entry and click the **pencil icon** to open the edit window.
*   **Deleting an Entry:** Click the **trash can icon** on any entry to permanently remove it.
*   **Clearing a Day:** If you want to start a day over, click the **"Clear Day"** button. **Warning:** This will delete all entries for the selected date.

## 5. Importing & Exporting Your Data

You have full control over your data.

*   **Export CSV:** Creates a spreadsheet file (.csv) of the current day's log. This is great for saving your data or using it in other applications.
*   **Copy Markdown:** Formats the day's log into a clean, text-based report. A window will pop up, allowing you to copy the report to your clipboard.
*   **Import...:** Allows you to import logs from a .csv or .xlsx (Excel) file. After selecting a file, the app will ask if you want to **Merge** the imported activities with your current log or **Replace** the current log entirely.

> **Note:** For a successful import, your file should contain columns for 'Start Time', 'End Time', 'Activity', and 'Category'.

## 6. Analyzing Your Progress: The Dashboard

At the bottom of the page is your **Analytics Dashboard**, where you can see your long-term trends.

*   **Toggle View:** Switch between **"This Week"** and **"This Month"** to change the time frame for the analysis.
*   **Summary Cards:**
    *   **Avg. Daily Score:** Your average productivity score for the selected period.
    *   **Total Productive Time:** The combined time you spent on "Deep Work" and "Shallow Work."
    *   **Total Distraction Time:** The combined time you spent on "Distraction" and "Rabbit Hole."
*   **Analytics Chart:** This chart instantly visualizes where your hours go. Use it to spot trends and identify your biggest time sinks and opportunities for improvement.
