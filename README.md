# ⚡ SmartTask AI

> An AI-powered task management dashboard built with HTML, CSS, and JavaScript.

## 🚀 Project Overview

SmartTask AI is a productivity tool that helps users manage their daily tasks with the power of AI. It features a clean dark-themed UI, task prioritization, category filtering, and an integrated AI chat assistant (powered by Claude) that gives personalized productivity advice.

## ✨ Features

- **Smart Task Management** — Add, complete, and delete tasks with priorities and categories
- **AI Assistant** — Chat with Claude AI to get focus tips, workload analysis, and daily reviews
- **Real-time Stats** — See total tasks, completed count, high priority items, and due-today count
- **Progress Tracking** — Visual progress bar for today's tasks
- **Category Filtering** — Filter by Work, Personal, Study, Health
- **Priority Tabs** — Filter by High / Medium / Low priority
- **Quick Add** — Add tasks instantly from the bottom bar
- **Local Storage** — Tasks persist across browser sessions
- **Responsive Design** — Works on desktop and tablet

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | App logic, state management |
| Fetch API | Communicating with Claude AI API |
| LocalStorage | Persisting tasks across sessions |

## 📁 Project Structure

```
smarttask-ai/
├── index.html       # Complete app (HTML + CSS + JS in one file)
└── README.md        # This file
```

## ⚙️ Setup & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/smarttask-ai.git
   cd smarttask-ai
   ```

2. **Open the app:**
   - Simply open `index.html` in any modern browser
   - No build tools or npm install required!

3. **AI Features (optional):**
   - The AI chat uses the Anthropic Claude API
   - The app works without an API key (AI features will show a connection error)
   - To enable AI: host the file on a server with the Anthropic API proxy configured

## 🎯 How to Use

| Action | How |
|---|---|
| Add a task | Click **+ Add Task** or type in the bottom bar and press Enter |
| Complete a task | Click the checkbox on the left |
| Delete a task | Click the × button on the right |
| Filter tasks | Use the sidebar (left) or priority tabs |
| AI Chat | Ask anything in the right panel or click quick buttons |

## 📸 Screenshots

The app features:
- Dark theme with purple/teal accent colors
- Three-column layout: Sidebar | Tasks | AI Panel
- Animated task cards with color-coded priority indicators
- Real-time stats strip showing task metrics

## 💡 Resume Talking Points

- Built a full-stack-like single-page application using only vanilla web technologies
- Integrated a third-party AI API (Anthropic Claude) for intelligent task assistance
- Implemented persistent state management using the Browser LocalStorage API
- Designed a responsive, accessible UI with CSS Grid and custom animations
- Features real-time filtering, dynamic stats, and an animated progress tracker

## 🔧 Possible Enhancements

- [ ] Drag-and-drop task reordering
- [ ] Dark/Light mode toggle
- [ ] Export tasks to CSV
- [ ] Email reminders
- [ ] Pomodoro timer integration
- [ ] Backend with Node.js + MongoDB

## 📄 License

MIT License — free to use and modify.
