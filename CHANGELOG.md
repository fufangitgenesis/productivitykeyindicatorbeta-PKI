# Changelog

*Note: This project follows Semantic Versioning for initial development (v0.y.z). Each `0.y` release represents a major feature addition.*

---

### **v0.7.0: Daily Quest System (Latest)**

*   Added a daily quest system to enhance user engagement and provide motivation.
*   Quests are tracked per-profile and reset automatically each day.
*   Implemented logic to evaluate quest completion based on daily log activity.
*   Added a new UI component to display quest status.

### **v0.6.0: Multi-Profile System & Data Overhaul**

*   Introduced support for multiple user profiles.
*   Refactored data storage to a unified `appData` object, associating all logs with a specific profile.
*   Added functionality to create, edit, delete, and switch between profiles.
*   Implemented a full data backup/restore feature using a single JSON file.

### **v0.5.0: Analytics & Dashboards**

*   Introduced weekly and monthly dashboards for long-term trend analysis.
*   Added summary cards for average score and total productive/distraction time.
*   Integrated Chart.js to create a bar chart visualizing time spent per category.

### **v0.4.0: UI Enhancements & Editing**

*   Implemented the ability to edit existing log entries through a modal window.
*   Made general UI improvements, including increasing the width for better readability.

### **v0.3.0: Data Persistence**

*   Integrated browser `localStorage` to save all log entries.
*   Ensured that user data persists between sessions.

### **v0.2.0: Data Portability**

*   Added functionality to export the daily log to `.csv` and Markdown formats.
*   Implemented an import feature for `.csv` and `.xlsx` files.

### **v0.1.0: Prototype**

*   Initial version with core functionality: activity logging, time tracking, categorization, and a real-time daily score calculation.
