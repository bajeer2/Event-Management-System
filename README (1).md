# 🎟️ EventFlow — Event Management System

> A fully offline, single-file web application for managing events, participant registrations, QR-based entry passes, and attendance records.

**Developed by: Rashid Akbar**

---

## 🚀 Live Demo

Simply download `event-management-system.html` and open it in any browser — **no internet, no server, no installation required.**

---

## ✨ Features

### 📋 Event Registration
- Register participants with Name, Email, Phone, and Event selection
- Optional Organization/Company field
- Instant form validation with error messages

### 👥 Participant Management
- View all registered participants in a sortable table
- **Search** by name, email, or event
- **Filter** by specific event
- **Edit** participant records inline
- **Delete** participants with confirmation

### 🎫 QR-Based Entry Passes
- Auto-generates a unique QR code for every participant on registration
- QR code encodes: Pass ID, Name, and Event
- View all passes on the Entry Passes page
- Fully **offline QR generation** — no CDN or internet needed

### ✅ Attendance Management
- Mark participants **Present / Absent** with one click
- Filter attendance by event
- **Mark All Present** bulk action
- Live attendance stats update in real time

### 📊 Admin Dashboard
- Total Registrations counter
- Present / Absent counters
- Active Events counter
- Attendance Rate donut chart
- Per-event registration & attendance progress bars
- Recent registrations table

### 📱 Responsive Design
- Mobile-friendly sidebar with hamburger menu
- Adaptive grid layout for all screen sizes
- Clean, dark-themed professional UI

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure & markup |
| CSS3 | Animations, transitions, custom design system |
| Bootstrap 5 | Responsive grid & utilities |
| JavaScript (Vanilla) | All logic, data management, routing |
| Font Awesome 6 | Icons |
| LocalStorage | Persistent data (survives page refresh) |
| Canvas API | Inline QR code generation (zero dependencies) |
| Chart.js | Dashboard charts |

---

## 📁 Project Structure

```
event-management-system.html   ← Entire app in one file
README.md                      ← This file
```

No build tools. No frameworks. No backend. **One file does everything.**

---

## ⚡ Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/your-username/event-management-system.git

# 2. Open the file in your browser
# Windows:
start event-management-system.html

# macOS:
open event-management-system.html

# Linux:
xdg-open event-management-system.html
```

That's it. ✅

---

## 📸 Screenshots

| Dashboard | Registration | Entry Pass |
|---|---|---|
| Stats, charts, recent activity | Clean form with validation | QR code pass per participant |

| Participants | Attendance | Events |
|---|---|---|
| Search, edit, delete | Toggle present/absent | Per-event capacity & stats |

---

## 💾 Data Storage

All data is stored in the browser's **LocalStorage** — it persists across page refreshes and browser restarts on the same device. Clearing browser data will reset the app.

---

## 🔒 Privacy

Everything runs **100% locally** in your browser. No data is ever sent to any server.

---

## 📄 License

This project is open source and free to use for educational and personal purposes.

---

## 👨‍💻 Author

**Rashid Akbar**
- Developed as part of Technify Internship Program
- Built with passion for clean UI and practical utility
