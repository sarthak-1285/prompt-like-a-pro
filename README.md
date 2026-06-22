# 🧠 Prompt Like a Pro

> **The ultimate interactive guide to getting exceptional results from AI.**

A beautifully designed, single-file web app that teaches prompt engineering from the ground up — covering core principles, advanced techniques, real-world examples, and a library of **100 ready-to-use prompts** organized across 5 categories and 20 sub-sections.

---

## ✨ Features

- **5 Pillars Framework** — A structured approach to crafting effective prompts (Role, Task, Context, Format, Tone)
- **Advanced Techniques** — Chain-of-thought, few-shot prompting, role-based prompting, constraints
- **100 Power Prompts Library** — 5 categories × 4 sub-sections × 5 prompts each, with one-click copy buttons
- **Interactive Quiz** — Test your prompting knowledge with instant scored feedback
- **Dark Mode** — Toggle with preference saved to `localStorage`
- **Reading Progress Bar** — Tracks how far through the guide you are
- **Sidebar Navigation** — Sticky table of contents with active-section highlighting and section search
- **Mobile Responsive** — Hamburger menu with a closeable backdrop overlay
- **Zero Dependencies** — Pure HTML + Tailwind CDN + Vanilla JS. No build step required.

---

## 🚀 Getting Started

### Run locally

Just open the file in your browser — no server needed:

```bash
git clone https://github.com/sarthak-1285/prompt-like-a-pro.git
cd YOUR_REPO
open index.html   # macOS
# or: start index.html  (Windows)
# or: xdg-open index.html  (Linux)
```

### Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose `main` branch and `/ (root)` folder
5. Click **Save**

Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/` within a minute.

---

## 📁 Project Structure

```
.
├── index.html    # The entire app — all HTML, CSS, and JS in one file
└── README.md     # This file
```

Everything lives in `index.html` — keeping deployment and sharing as simple as possible.

---

## 🗂️ Content Sections

| Section | Description |
|---|---|
| **Introduction** | What prompting is and why it matters |
| **Fundamentals** | Core concepts and how AI interprets requests |
| **5 Pillars** | Role · Task · Context · Format · Tone |
| **Advanced Techniques** | Chain-of-thought, few-shot, role-based, constraints |
| **Common Mistakes** | What to avoid with before/after examples |
| **Real-World Examples** | Email, education, coding, brainstorming, data analysis |
| **Quiz** | 5-question self-assessment with instant scoring |
| **Power Prompts Library** | 100 prompts across 5 categories & 20 sub-sections |

### 📦 Prompt Library Breakdown

| Category | Sub-sections |
|---|---|
| 🎨 **Creativity** | Writing & Poetry · Storytelling & Fiction · Branding & Marketing Copy · Ideation |
| ⚡ **Productivity** | Communication · Planning & Scheduling · Task Management · Focus & Habits |
| 📚 **Learning** | Explaining Concepts · Study & Research · Skill Development · Teaching & Assessment |
| 💻 **Technical** | Code Writing · Debugging & Review · Architecture & Design · Docs & Testing |
| 💼 **Business** | Market & Competitive Analysis · Planning & Strategy · Sales & Marketing · Operations & Finance |

---

## 🛠️ Customisation

To add your own prompts, find the relevant `category-group` div and add a new prompt block:

```html
<div class="prompt-block my-4">
  <button class="copy-btn" onclick="copyPrompt(this)">
    <!-- SVG icon already in file -->
    Copy
  </button>
  <pre><code>Your prompt template here with [bracketed placeholders].</code></pre>
</div>
```

To add a new sub-section heading within a category:

```html
<h4 class="prompt-sub-heading">🔖 My New Sub-Section</h4>
```

---

## 🤝 Contributing

Contributions are welcome! If you have great prompts, a fix, or an improvement:

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-improvement`
3. Commit your changes: `git commit -m 'Add: new business prompts'`
4. Push and open a Pull Request

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

> Made with ❤️ for the AI-curious. Feel free to share and adapt.


---

## ✨ Features

- **5 Pillars Framework** — A structured approach to crafting effective prompts (Role, Task, Context, Format, Tone)
- **Advanced Techniques** — Chain-of-thought, few-shot prompting, role-based prompting, constraints
- **50+ Power Prompts Library** — Categorized prompts for creativity, productivity, learning, technical, and business use cases — each with a one-click copy button
- **Interactive Quiz** — Test your prompting knowledge with instant scored feedback
- **Dark Mode** — Toggle with preference saved to `localStorage`
- **Reading Progress Bar** — Tracks how far through the guide you are
- **Sidebar Navigation** — Sticky table of contents with active-section highlighting and section search
- **Mobile Responsive** — Hamburger menu with a closeable backdrop overlay
- **Zero Dependencies** — Pure HTML + Tailwind CDN + Vanilla JS. No build step required.

---

## 🚀 Getting Started

### Run locally

Just open the file in your browser — no server needed:

```bash
git clone https://github.com/sarthak-1285/prompt-like-a-pro.git
cd YOUR_REPO
open index.html   # macOS
# or: start index.html  (Windows)
# or: xdg-open index.html  (Linux)
```

### Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose `main` branch and `/ (root)` folder
5. Click **Save**

Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/` within a minute.

---

## 📁 Project Structure

```
.
├── index.html    # The entire app — all HTML, CSS, and JS in one file
└── README.md     # This file
```

Everything lives in `index.html` — styles, scripts, and content — keeping deployment and sharing as simple as possible.

---

## 🗂️ Content Sections

| Section | Description |
|---|---|
| **Introduction** | What prompting is and why it matters |
| **Fundamentals** | Core concepts and how AI interprets requests |
| **5 Pillars** | Role · Task · Context · Format · Tone |
| **Advanced Techniques** | Chain-of-thought, few-shot, role-based, constraints |
| **Common Mistakes** | What to avoid with before/after examples |
| **Real-World Examples** | Email, education, coding, brainstorming, data analysis |
| **Quiz** | 5-question self-assessment with instant scoring |
| **Power Prompts Library** | 50+ categorized, copyable prompt templates |

---

## 🛠️ Customisation

Want to add your own prompts? Find the relevant section in `index.html` (e.g. `data-category="creativity"`) and add a new prompt block:

```html
<div class="prompt-block my-6">
  <button class="copy-btn" onclick="copyPrompt(this)">
    <!-- copy icon SVG already in file -->
    Copy
  </button>
  <pre><code>Your prompt template here with [bracketed placeholders].</code></pre>
</div>
```

To add a whole new category, duplicate a `category-group` block and update its `data-category` attribute, then add a matching filter button.

---

## 🤝 Contributing

Contributions are welcome! If you have great prompts, a fix, or an improvement:

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-improvement`
3. Commit your changes: `git commit -m 'Add: new business prompts'`
4. Push and open a Pull Request

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

> Made with ❤️ for the AI-curious. Feel free to share and adapt.
