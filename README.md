# 🚀 Toaster Notification System (Vanilla JS + Tailwind CSS)

A lightweight, customizable toaster notification system built using **Vanilla JavaScript** and **Tailwind CSS**.  
Designed for smooth UX, dynamic positioning, and clean UI without any external libraries.

---

## 🔥 Features

- 📍 Dynamic positioning (Top / Bottom, Left / Right)
- ⚡ Instant toast rendering
- 🧩 Fully customizable content (title, message, type)
- 🎨 Styled using Tailwind CSS utility classes
- ⏱️ Auto-dismiss with configurable duration
- 🔁 Stack multiple notifications
- 🎯 Clean and minimal DOM manipulation (no frameworks)

---

## 🛠️ Tech Stack

- **HTML**
- **Tailwind CSS**
- **Vanilla JavaScript**

---

## ⚙️ How It Works

1. A toast container (`.parent`) is positioned dynamically using config.
2. Notifications are created using JavaScript and appended to the DOM.
3. Tailwind classes handle layout, spacing, and animations.
4. Each toast auto-removes after a set timeout.

---

## 🧠 Example Usage

```js
showToast({
  title: "Success",
  message: "Task added successfully!",
  type: "success", // success | error | warning
  positionX: "right",
  positionY: "bottom",
  duration: 3000
});
```

---

## 📂 Project Structure

```
📁 toaster_notification_using_js
 ├── index.html
 ├── style.css (if any custom styles)
 ├── script.js
 └── README.md
```

---

## 🚀 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/your-username/toaster_notification_using_js.git
```

2. Open `index.html` in your browser

No build tools. No dependencies. Just run and test.

---

## ⚠️ Known Limitations

- No accessibility support (ARIA roles, screen readers)
- No animation library (basic transitions only)
- No queue management for large volumes of notifications

---

## 💡 Future Improvements

- Add animation (bounce / slide transitions)
- Add close button for manual dismiss
- Add toast queue system
- Improve accessibility

---