# koprodead335.github.io
Experiments with animation
# 🎯 Interactive Feedback Form with Background Animations

[![Live Demo](https://shields.io)](https://koprodead335.github.io)

A modern, static **feedback website** featuring a completely JavaScript-free implementation of a slide-in modal window and continuously moving decorative background elements.

---

## ✨ Features
*   **Pure CSS Animations:** Infinite, smooth background movement using pure CSS `@keyframes`.
*   **Slide-In Modal:** An interactive window that transitions into view without a single line of JavaScript.
*   **3-Field Feedback Form:** Clean, accessible layout containing three input fields:
    1.  👤 **Name**
    2.  📧 **Email**
    3.  💬 **Message**

---

## 🛠 Tech Stack
*   **HTML5** — Semantic page structure, form elements, and custom shortcut icon implementation.
*   **CSS3** — Advanced styling, layout, infinite background animations, and modal transition triggers (using CSS techniques like `:target` or checkbox hacks).

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com
cd koprodead335.github.io
```

### 2. Run the project
Since this is a lightweight static website, no installation or local server is required. Simply double-click the `index.html` file to open it instantly in any modern web browser.

---

## 📂 Project Structure
```text
├── index.html          # Main page structure and form layout
├── index.css           # UI styles, responsive design, and animations
└── images/
    └── favicon.icon     # Shortcut icon displayed in the browser tab
```

---

## 📝 Form Code Preview
The feedback form embedded within the animated modal window consists of the following three standard rows:
```html
<form>
  <label for="name">Ваше имя</label>
  <input type="text" id="name" autocomplete="cc-given-name" placeholder="Введите имя" required>
  <label for="email">Email</label>
  <input type="email" id="email" autocomplete="off"  placeholder="example@mail.com" required>
  <label for="message">Сообщение</label>
  <textarea id="message" type="text" placeholder="Напишите сообщение..." required></textarea>
  <button type="submit">Отправить сообщение</button>
</form>
```

> [!NOTE]
> This website was created exclusively for educational practice and to showcase CSS animation skills in my personal portfolio. It demonstrates how powerful modern CSS is, allowing complex overlay animations and continuous motion without a single line of JavaScript.
