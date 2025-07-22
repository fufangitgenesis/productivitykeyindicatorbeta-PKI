# productivitykeyindicatorbeta-PKI
A tool for logging, scoring and tracking work effectiveness during a day. Created by Gemini 2.5 pro (using canvas features)
# Productivity Tracker

A single-file, zero-dependency web application to log your daily activities, track your productivity based on a point system, and visualize your progress over time.



## Features

*   **Detailed Activity Logging:** Log activities with descriptions, start/end times, and categories.
*   **Productivity Scoring System:** Each activity is assigned points based on its category to provide a daily productivity score.
*   **Daily Summary:** Get an at-a-glance summary of your day's activities and total score.
*   **Data Persistence:** All your data is saved locally in your browser's storage, so your logs are there when you return.
*   **History Viewer:** Use the date picker to review and manage logs from previous days.
*   **Analytics Dashboard:** Visualize your progress with weekly and monthly charts that show time spent per category and average scores.
*   **Data Portability:** Export your daily logs to .csv or copy them as a Markdown report. You can also import data from .csv and .xlsx files.

## How to Use

This application is a self-contained HTML file. No installation is needed.

1.  Download the `.html` file (e.g., V5.html).
2.  Open the file in any modern web browser like Chrome, Firefox, or Edge.
3.  Start logging your activities!

## How It Works

### Logging an Activity

The core of the tracker is the **Log Activity** form.

1.  **Activity Description:** Describe the task you were doing.
2.  **Start & End Time:** Select the time you began and finished the activity.
3.  **Category:** Choose the category that best fits your activity. This choice directly impacts your score.
4.  **Add to Log:** Click to save the activity to your daily log.

### The Scoring System

The "Productivity Score" gives you a simple measure of how effectively you used your time. Every minute you log is assigned a point value based on its category.

Here is the exact point system based on a 30-minute block of time:

| Category            | Points per 30 Mins | Purpose                                                    |
| ------------------- | ------------------ | ---------------------------------------------------------- |
| **Deep Work**       | +10 points         | For highly focused, high-value tasks (e.g., studying, coding). |
| **Shallow Work**    | +4 points          | For necessary but less demanding tasks (e.g., planning, emails). |
| **Scheduled Leisure** | +2 points          | For planned breaks and leisure that help you recharge.     |
| **Scheduled Break** | +2 points          | For essential rests like lunch or short breaks.            |
| **Distraction**     | -5 points          | For unplanned, low-value activities (e.g., aimless scrolling). |
| **Rabbit Hole**     | -10 points         | For significant, unplanned distractions.                   |

#### Pro-Tip: What's a 'good' score?

There's no magic number! The goal is to establish your own baseline and aim for gradual improvement. Focus on increasing your 'Total Productive Time' and seeing your 'Avg. Daily Score' rise over time.

### Managing and Analyzing Your Data

*   **Editing/Deleting:** Hover over any log entry to reveal the edit (pencil) and delete (trash) icons.
*   **Import/Export:** Use the buttons in the "Daily Summary" and log table headers to manage your data. **Note:** For a successful import, your file should contain columns for 'Start Time', 'End Time', 'Activity', and 'Category'.
*   **Dashboard:** Scroll to the bottom to see the Analytics Dashboard. Toggle between "This Week" and "This Month" to analyze your long-term trends.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

This means you are free to share and adapt the work for non-commercial purposes, as long as you give appropriate credit and distribute any new versions under the same license. For any commercial use, please contact me directly.

## Acknowledgements

This project was built using Gemini AI and the following fantastic libraries:

*   [Tailwind CSS](https://tailwindcss.com/)
*   [Chart.js](https://www.chartjs.org/)
*   [SheetJS (xlsx)](https://sheetjs.com/)
