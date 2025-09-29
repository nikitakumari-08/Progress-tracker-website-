# 📊 Kiki’s Tracker — Progress & Task Tracker

A sleek, user‑friendly web app for managing tasks and tracking progress. Many users struggle to stay organized or see how far they’ve come — Kiki’s Tracker helps by letting you add, edit, complete, and delete tasks while visualizing your progress over time.

Built with **HTML5**, **CSS3**, **JavaScript**, and **LocalStorage** — no backend needed, all data stored in your browser.

---

## ✨ Features

### 🎯 Core Functionality
- **Add Tasks**: Create tasks with descriptions, due dates, priorities, and category tags  
- **Edit Tasks**: Modify existing task details  
- **Complete / Toggle**: Mark tasks as done; toggle back if needed  
- **Delete Tasks**: Remove tasks you no longer want  
- **Progress Visualization**: Show task completion via progress bars or stats  
- **Views / Filters**: Optionally filter by Today, Overdue, Upcoming, All, Completed  

### 🖼️ User Experience
- **Responsive Design**: Works elegantly on desktop and mobile  
- **Modern UI**: Clean layout, subtle animations, intuitive interactions  
- **Keyboard Shortcuts**: (If implemented) quick commands to speed up entry  
- **Notifications / Feedback**: Visual cues or alerts for actions (success, errors)  
- **Empty States**: Friendly prompt when there are no tasks  

### 💾 Storage & Utility
- **LocalStorage Persistence**: Tasks persist across browser sessions  
- **Import / Export**: Backup or restore your data via JSON (if implemented)  
- **Customizable Labels / Categories**: You can define your own categories  

---

## 🖼️ Screenshots / Demo

*(Add images or GIFs to showcase key screens: task list, progress indicator, filters, etc.)*

---

## 🛠️ Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)  

### Installation & Running Locally
```bash
git clone https://github.com/nikitakumari-08/Progress-tracker-website-.git
cd Progress-tracker-website-
Then:

Open index.html in your browser

Or run a simple local server (e.g. via live-server or VS Code)

🎮 Usage Guide
➕ Adding Tasks
Click on the “New Task” input or form

Enter title / description

(Optional) Set due date, priority, and category

Save (or press Enter)

✅ Managing Tasks
Complete: Click the checkbox or toggle icon

Edit: Click the edit (pencil) icon

Delete: Click the trash icon

Search / Filter: Use search bar or filters to find tasks

📂 Views / Filters
Today: Tasks due today

Overdue: Tasks past their due date

Upcoming: Tasks due in the future

All Tasks: All tasks not yet completed

Completed: All tasks you’ve marked done

⌨️ (If applicable) Keyboard Shortcuts
Shortcut	Action
Ctrl + N	Focus new task / add task
Ctrl + F / Ctrl + K	Open search / filter
Enter	Save a new or edited task
Esc	Cancel / close modal or edit

📐 Architecture & Tech Details
🧱 Architecture
Frontend: HTML5 + CSS3 + JavaScript (ES6+)

Storage: LocalStorage for persistent state

Styling / Theme: CSS variables (custom properties)

Icons / Fonts: Font Awesome (or similar), Google Fonts

📁 File Structure
bash
Copy code
Progress-tracker-website/
├── index.html           # Main UI
├── styles.css           # All styles and themes
├── script.js            # Logic for tasks, storage, UI update
├── images/               # Logos, icons, illustrations
└── README.md             # This documentation
🔍 Key Components
TaskManager / Controller: Handles CRUD for tasks

Storage Module: Reads / writes task list from LocalStorage

UI Renderer: Updates DOM & progress bars / stats

Event Handlers: Reacts to clicks, inputs, filters, searches

🎨 Customization & Theming
🖌️ Theme Colors
In your CSS (or :root), define main colors:

css
Copy code
:root {
  --primary-color: #4c9aff;
  --hover-color: #357ae8;
  --success-color: #28a745;
  --warning-color: #ffc107;
  --danger-color: #dc3545;
  /* etc. */
}
You can change these to match your brand or preferences.

📂 Custom Categories / Labels
If the categories are hardcoded in HTML, you can add or change them by editing the <select> element for task category:

html
Copy code
<select id="task-category">
  <option value="personal">Personal</option>
  <option value="work">Work</option>
  <option value="study">Study</option>
  <option value="misc">Miscellaneous</option>
  <!-- Add more -->
</select>
📜 Browser / Platform Support
Browser	Version	Support
Chrome	60+	✅ Full
Firefox	55+	✅ Full
Safari	12+	✅ Full
Edge	79+	✅ Full

🤝 Contributing
Contributions are welcome and appreciated!

How to Contribute
Fork this repository

Create a branch: git checkout -b feature/your-feature

Make your changes and commit: git commit -m "Add feature X"

Push: git push origin feature/your-feature

Open a Pull Request

Guidelines
Follow existing code style

Test across browsers (desktop & mobile)

Ensure new features are documented

Use clear commit messages

🙏 Acknowledgments
Font Awesome (for icons)

Google Fonts (for typography)

Inspiration from productivity / tracker apps

Modern CSS & vanilla JS patterns

📞 Support & Contact
📘 Report bugs or request features via GitHub Issues

📧 Email: (your email)

👤 Author: Nikita Kumari — nikitakumari-08
   
