
# ✨ My Personal Task Assistant

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/LocalStorage-Browser%20Storage-6C63FF?style=for-the-badge" alt="Local Storage">
</p>

<p align="center">
  <strong>A beautiful, premium, and customizable task manager designed to help you stay organized, focused, and productive.</strong>
</p>

<p align="center">
  Manage your daily tasks, organize priorities, customize your workspace, and keep your data safe with backup and restore.
</p>

---

## 🌟 Overview

**My Personal Task Assistant** is a lightweight, responsive task management application built with HTML, CSS, and vanilla JavaScript.

It combines an elegant interface with practical productivity tools, allowing you to manage everyday responsibilities without installing complex software or creating an account.

## 🚀 Features

### 📋 Smart Task Management
- ➕ Add new tasks with a simple interface.
- ✏️ Edit task details whenever needed.
- ✅ Mark tasks as completed.
- 🗑️ Delete tasks when they are no longer needed.
- 📅 Set due dates for better planning.
- 🎯 Assign High, Medium, or Low priority.

### 🗂️ Task Categories
Organize tasks using dedicated categories:

- 💻 Work
- 📚 Study
- 🕌 Islamic
- 🏋️ Health
- 👤 Personal
- 🛒 Shopping
- 📌 Other

### 📊 Organized Task Views
- **Task List:** A read-only overview of unfinished tasks.
- **Pending Tasks:** Manage, edit, complete, and delete unfinished tasks.
- **Completed Tasks:** Keep completed work organized separately.
- 📈 View task counts and daily progress.

### 🔎 Search, Filter & Sort
- Search tasks by title, category, or priority.
- Filter tasks by category.
- Sort by due date, priority, creation time, or title.
- Find the tasks you need without scrolling through everything.

### 🎨 Premium Customization
- 🌗 Light and dark themes.
- 🌈 Multiple gradient color presets.
- 🎨 Custom RGB color controls.
- ✨ Optional animated RGB lighting.
- 💾 Save theme preferences in your browser.

### 💾 Backup & Restore
- 📥 Export tasks to a JSON backup file.
- 📤 Restore tasks from a supported JSON backup.
- 🔄 Add or update tasks from a backup while preserving existing tasks.
- 🛡️ Protect the current task list against empty or invalid backups.

**Tip:** Keep a backup in a safe location before restoring important data.

### 📱 Responsive Design
Enjoy a clean interface on desktop, laptop, tablet, and mobile browsers.

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive layout, themes, gradients, and animations |
| JavaScript | Task management and application logic |
| Browser Local Storage | Persist tasks and preferences locally |
| JSON | Task backup and restore format |

---

## ⚡ Getting Started

### Option 1: Run Locally

1. Download or clone this repository.
2. Locate `index.html`.
3. Open it in your preferred web browser.
4. Start adding and organizing tasks.

No build tools, package installation, or backend server are required.

### Option 2: Run with VS Code

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

Your browser will open the application. Save your changes to refresh the preview.

### Option 3: Deploy with GitHub Pages

1. Push the project files to a GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Choose **Deploy from a branch**.
5. Select your branch and the root folder.
6. Save and open the published URL.

---

## 💾 How Data Storage Works

The application uses browser Local Storage to save tasks and preferences.

- Your tasks remain available in the same browser after refreshing or reopening the app.
- Theme and customization preferences are stored locally.
- Different browsers and devices have separate local storage.
- Clearing browser site data may delete locally stored tasks.

### 🔐 Backup Recommendations

1. Export a JSON backup regularly.
2. Keep a copy outside the browser.
3. Verify that your backup file contains your expected tasks.
4. Restore from the correct backup when needed.

**Important:** This version does not use Firebase, Google authentication, or automatic cloud synchronization. Moving tasks between devices requires manual backup and restore.

---

## 📂 Project Structure

```text
my-personal-task-assistant/
│
├── index.html
└── README.md
```

The application is self-contained in a single HTML file, including its styles and JavaScript.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `/` | Focus task search |
| `Ctrl + K` | Focus task search |
| `Ctrl + S` | Save code changes in your editor |

*Note: Keyboard shortcuts depend on browser focus and the environment in which the app is running.*

---

## 🔒 Privacy

- No account is required.
- No authentication system is included.
- Tasks are stored in the current browser.
- Backups are downloaded to your device.
- Anyone with access to the same browser profile may be able to access its stored tasks.

Avoid storing passwords or other sensitive information in task titles or notes.

---

## 🗺️ Future Improvements

Potential enhancements include:

- [ ] Optional cloud synchronization.
- [ ] Recurring tasks and reminders.
- [ ] Calendar and weekly planning views.
- [ ] Drag-and-drop task organization.
- [ ] Task notes and subtasks.
- [ ] Productivity analytics.
- [ ] Progressive Web App support.

---

## 🤝 Contributing

Suggestions and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test task creation, editing, deletion, backup, and restore.
5. Submit a pull request.

---

## 📄 License

Choose a license before distributing the project publicly. For example, the MIT License allows reuse and modification while retaining the copyright and license notice.

---

<p align="center">
  Made with ❤️ and JavaScript
</p>

<p align="center">
  <strong>Plan smarter. Stay focused. Make every day count. ✨</strong>
</p>
