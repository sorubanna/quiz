# 🧠 Code With AI Quiz App

A clean, responsive, and lightweight interactive quiz web application built with vanilla HTML, CSS, and JavaScript. Test your core knowledge of Large Language Models, coding best practices, unit testing, and algorithmic complexity.

---

## ✨ Features

- **Interactive Multiple-Choice Quiz**: Smooth question-by-question transition with immediate choice selection.
- **Dynamic Score Tracking**: Tracks your answers and calculates the final score upon completion.
- **Elegant & Responsive Design**: Crafted with a premium navy and gold theme, smooth hover micro-interactions, and mobile-friendly responsive layout.
- **Zero Dependencies**: Pure HTML5, CSS3, and modern JavaScript—no frameworks, bundlers, or external libraries needed.

---

## 🗂️ Project Structure

```plaintext
quiz/
├── index.html    # Core markup and application structure
├── style.css     # Design system, CSS variables, typography, and styling
├── script.js     # Question bank, quiz state management, and DOM logic
└── README.md     # Project documentation
```

---

## 🚀 Getting Started

No installation or build step is required! You can run this app directly in your browser.

### Option 1: Direct File Open
Simply double-click [`index.html`](index.html) or right-click and choose **Open With > Google Chrome** (or your browser of choice).

### Option 2: Local Development Server (Recommended)

Using **VS Code Live Server**:
- Open the project folder in VS Code.
- Right-click [`index.html`](index.html) and click **"Open with Live Server"**.

Using **Python**:
```bash
# Python 3
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

Using **Node.js (`npx serve`)**:
```bash
npx serve .
```

---

## 🛠️ Customization

### Adding or Modifying Questions
Questions are stored in [`script.js`](script.js) inside the `questions` array. You can easily add, edit, or remove questions using this structure:

```javascript
{
  question: "Your question here?",
  options: [
    "Option A",
    "Option B",
    "Option C",
    "Option D"
  ],
  answer: "Option A" // Must match one of the options exactly
}
```

### Changing Colors & Styles
The styling in [`style.css`](style.css) utilizes CSS custom properties (variables) defined at the `:root` level:

```css
:root {
  --navy: #0b1f3a;
  --navy-mid: #16365d;
  --blue: #1e4d8c;
  --blue-light: #2a63b0;
  --gold: #c9a227;
  --gold-bright: #e0bc4a;
  --gold-soft: #f4e6b5;
  --white: #ffffff;
  --ivory: #f7f4ec;
  --text: #10243f;
}
```
You can update these color tokens to match your preferred theme.

---

## 💻 Tech Stack

- **HTML5**: Semantic markup.
- **CSS3**: Custom design system, Flexbox, CSS Variables, and CSS transitions.
- **JavaScript (ES6+)**: Event handling and dynamic DOM manipulation.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
