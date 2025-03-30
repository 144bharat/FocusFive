# **Focus Five**

A local desktop application built to streamline and structure your **daily interview preparation**. Focus Five helps you stay on track by presenting **five sequential questions every day** to encourage focused learning. Designed with privacy and efficiency in mind, it operates entirely on your local system, ensuring a distraction-free and secure experience.

---

## **Features**

- 🎯 **Daily Questions Pop-Up**:
  - Sequentially displays five interview questions each day.
  - Unlocks answers and subsequent questions only after engagement.

- ✍️ **Question Management**:
  - Add, edit, and preview your custom questions and solutions through a user-friendly interface.

- 📊 **Progress Tracking**:
  - Automatically logs daily activity, enabling you to review past questions and solutions.

- 🔔 **Notifications**:
  - Gentle reminders to complete your daily questions and stay on schedule.

- ⚙️ **Auto-Startup**:
  - Optional setting to start the application automatically when the system boots.

- 🔒 **Privacy-Focused**:
  - All data is stored locally, ensuring security and privacy.

---

## **Tech Stack**

- **Electron.js**: Framework for cross-platform desktop applications.
- **Node.js**: Backend logic for managing data and local storage.
- **HTML/CSS/JavaScript**: Frontend for the user interface.
- **SQLite or JSON**: For local storage of questions and progress logs.

---

## **Installation**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/focus-five.git
   cd focus-five
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   npm start
   ```

---

## **File Structure**

```
focus-five/
├── main.js               # Controls the application lifecycle
├── preload.js            # Secure communication between backend and frontend
├── renderer/
│   ├── index.html        # Main UI for displaying daily questions
│   ├── manage.html       # Question and answer management interface
│   ├── styles.css        # Styling for the user interface
│   └── script.js         # Frontend logic for user interactions
├── database.sqlite       # Local SQLite database (optional: questions.json)
├── history/              # Logs daily question progress
│   └── example-log.json  # Example daily log file
├── notifications/        # Logic for reminders and notifications
├── package.json          # Project metadata and dependencies
└── .gitignore            # Ignore unnecessary files in version control
```

---

## **Usage**

- **Add Questions**: Use the "Manage Questions" screen to input your custom questions and solutions.
- **Daily Prep**: Open the application daily to receive a pop-up with your five sequential questions.
- **Track Progress**: Review your daily logs in the history section.

---

## **Future Enhancements**

- **Theming**: Add light/dark mode support for a more customizable interface.
- **Web Version**: Adapt for web deployment to reach more users.
- **Analytics Dashboard**: Visualize user progress through graphical insights.

---

## **Contributing**

Contributions are welcome! If you have ideas for new features or enhancements, feel free to open an issue or submit a pull request.

---
