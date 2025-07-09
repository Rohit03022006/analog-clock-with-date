Here's a `README.md` file for your **Analog Clock with Date and Sticky Notes** project:

---

# 🕒 Analog Clock with Date & Sticky Notes 📝

A responsive and visually engaging web application that features a **live analog clock**, **real-time digital clock and date display**, and **interactive sticky notes** with **localStorage** support.

---

## 📌 Features

* **Analog Clock** – Beautifully styled with rotating hour, minute, and second hands.
* **Digital Clock & Date** – Displays current time, day of the week, month, and day.
* **Sticky Notes** – Users can:

  * Create colorful sticky notes
  * Delete notes
  * Edit notes
  * Notes persist in `localStorage` even after refreshing
* **Responsive Design** – Optimized for various screen sizes with smooth layout transitions.
* **Stylish UI** – Uses soft gradients, shadows, and modern typography for an aesthetic experience.

---

## 💻 Technologies Used

* HTML5
* CSS3 (including media queries and CSS variables)
* JavaScript (ES6)
* Google Fonts (Poppins)

---

## 📂 File Structure

```
project-folder/
├── index.html        # Main HTML file
├── style (inline)    # CSS styles inside <style> tag
└── script (inline)   # JavaScript logic inside <script> tag
```

---

## 🚀 Getting Started

### 1. Clone or Download

```
git clone https://github.com/yourusername/analog-clock-sticky-notes.git
```

### 2. Open in Browser

Open `index.html` in any modern web browser.

---

## 🧠 How It Works

### Analog Clock:

* Uses `setInterval()` to update every second.
* Rotates hands using `transform: rotate()` based on current time.

### Sticky Notes:

* Click **`+`** button to add a note.
* Notes are assigned a random pastel color and rotation.
* Text is editable.
* Each note includes a **delete button (×)**.
* All changes are saved to `localStorage` automatically.

---

## 📱 Responsive Behavior

* Full functionality across devices (desktops, tablets, mobiles).
* Sticky notes rearrange and resize based on screen width.

---

## 📦 Local Storage Format

Notes are saved as an array of objects:

```json
[
  {
    "text": "Buy groceries",
    "color": "note-2",
    "rotation": "rotate(-1deg)"
  }
]
```

---

## 📸 Preview

*Add a screenshot here if available*

---

## ✨ Future Enhancements

* Drag & drop note positioning
* Reminders with notification support
* Dark mode toggle
* Export/import notes as JSON

---

## 📝 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

## 👨‍💻 Author

**Rohit**

---
