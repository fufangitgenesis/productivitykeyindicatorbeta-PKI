# Changelog

---
### v0.9.0-alpha: Theme Customization (Latest)

* Implemented a theme customization system with multiple pre-defined themes (Dark, Light, Rosé, Forest, etc.).

* Created a theme selection modal for users to preview and apply different themes.

* Refactored CSS to use variables, allowing for dynamic theme changes.

* User's theme choice is now saved to localStorage and persists across sessions.

### v0.8.0-alpha: UI Overhaul with Sidebar Navigation

*  Replaced the top control bar with a collapsible sidebar menu for a cleaner interface.

*  Moved profile management, data import/export, and settings into the new sidebar.

*  Added a hamburger menu button to toggle the sidebar's visibility.
### v0.7.0-alpha: Daily Quest System 

*   Added a daily quest system to enhance user engagement and provide motivation.
*   Quests are tracked per-profile and reset automatically each day.
*   Implemented logic to evaluate quest completion based on daily log activity.
*   Added a new UI component to display quest status.

### **v0.6.0-alpha: Multi-Profile System & Data Overhaul**

*   Introduced support for multiple user profiles.
*   Refactored data storage to a unified `appData` object, associating all logs with a specific profile.
*   Added functionality to create, edit, delete, and switch between profiles.
*   Implemented a full data backup/restore feature using a single JSON file.

### **v0.5.0-alpha: Analytics & Dashboards**

*   Introduced weekly and monthly dashboards for long-term trend analysis.
*   Added summary cards for average score and total productive/distraction time.
*   Integrated Chart.js to create a bar chart visualizing time spent per category.

### **v0.4.0-alpha: UI Enhancements & Editing**

*   Implemented the ability to edit existing log entries through a modal window.
*   Made general UI improvements, including increasing the width for better readability.

### **v0.3.0-alpha: Data Persistence**

*   Integrated browser `localStorage` to save all log entries.
*   Ensured that user data persists between sessions.

### **v0.2.0-alpha: Data Portability**

*   Added functionality to export the daily log to `.csv` and Markdown formats.
*   Implemented an import feature for `.csv` and `.xlsx` files.

### **v0.1.0-alpha: Prototype**

*   Initial version with core functionality: activity logging, time tracking, categorization, and a real-time daily score calculation.
