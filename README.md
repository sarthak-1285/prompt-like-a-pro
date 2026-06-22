<div align="center">

# 🧠 Prompt Like a Pro

### The ultimate interactive guide to getting exceptional results from AI

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-4f46e5?style=for-the-badge&logo=github)](https://YOUR_USERNAME.github.io/prompt-like-a-pro/)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/Built%20With-HTML%20%2B%20JS-f97316?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-ec4899?style=for-the-badge)](index.html)

<br/>

> A single-file, zero-dependency web app that teaches prompt engineering  
> from scratch — with 100 copy-ready prompts, an interactive quiz, dark mode, and more.

<br/>

**[🚀 View Live Demo](https://sarthak-1285.github.io/prompt-like-a-pro/) · [📖 Read the Guide](#-content-sections) · [🤝 Contribute](#-contributing)**

</div>

---

## 📸 Preview

| Light Mode | Dark Mode |
|:---:|:---:|
| <img width="1918" height="976" alt="Screenshot 2026-06-22 165255" src="https://github.com/user-attachments/assets/5d44e1ab-6cf1-40a9-87a9-b5b5c166fb31" /> | <img width="1918" height="991" alt="Screenshot 2026-06-22 165315" src="https://github.com/user-attachments/assets/11212b0e-3504-4c93-ba75-cc67f2da0e74" /> |



---

## ✨ What's Inside

<table>
<tr>
<td width="50%">

### 📚 Learning Content
- **Introduction** — why prompting matters
- **Fundamentals** — how AI interprets your words
- **5 Pillars Framework** — Role · Task · Context · Format · Tone
- **Advanced Techniques** — chain-of-thought, few-shot, role-based, constraints
- **Common Mistakes** — before/after examples of bad vs good prompts
- **Real-World Examples** — email, coding, education, data analysis

</td>
<td width="50%">

### ⚡ App Features
- **100 Power Prompts** — 5 categories, 20 sub-sections, one-click copy
- **Interactive Quiz** — 5 questions with instant scored feedback
- **Dark Mode** — toggle with preference saved across sessions
- **Reading Progress Bar** — always know where you are
- **Sidebar Navigation** — sticky TOC with active highlighting & search
- **Fully Responsive** — works great on mobile, tablet, desktop

</td>
</tr>
</table>

---

## 📦 Prompt Library — 100 Prompts Across 5 Categories

Each category has **20 prompts** split into **4 focused sub-sections**.

| # | Category | Sub-sections | Prompts |
|---|---|---|:---:|
| 🎨 | **Creativity & Brainstorming** | Writing & Poetry · Storytelling & Fiction · Branding & Marketing Copy · Ideation | 20 |
| ⚡ | **Productivity & Efficiency** | Communication · Planning & Scheduling · Task Management · Focus & Habits | 20 |
| 📚 | **Learning & Education** | Explaining Concepts · Study & Research · Skill Development · Teaching & Assessment | 20 |
| 💻 | **Technical & Coding** | Code Writing · Debugging & Review · Architecture & Design · Docs & Testing | 20 |
| 💼 | **Business & Strategy** | Market Analysis · Planning & Strategy · Sales & Marketing · Operations & Finance | 20 |
| | | **Total** | **100** |

---

## 🚀 Getting Started

### Option A — Just open it in your browser (no setup at all)

1. Download `index.html` from this repo (click the file → click **Download raw file**)
2. Double-click it on your computer
3. Done — it opens in your browser and works fully offline

### Option B — Deploy as a free live website (GitHub Pages)

1. **Fork** or upload this repo to your GitHub account
2. Go to your repo → **Settings** → **Pages**
3. Under *Source*, choose `Deploy from a branch` → `main` → `/ (root)` → **Save**
4. Wait ~60 seconds — your site goes live at:

```
https://YOUR_USERNAME.github.io/prompt-like-a-pro/
```

> 💡 Every time you update `index.html` on GitHub, the live site auto-redeploys in ~30 seconds.

---

## 🗂️ Project Structure

This entire project is intentionally **one file**. No build step, no npm, no framework.

```
prompt-like-a-pro/
│
├── index.html        ← The whole app: HTML + CSS + JavaScript in one file
└── README.md         ← This file
```

**Why one file?**  
It makes the project trivially easy to share, fork, deploy, and modify. Anyone can open it, read it, and start editing without any tooling knowledge.

---

## 🛠️ How to Customise

### Add a new prompt

Find the right category in `index.html` (search for `data-category="creativity"` etc.) and paste in:

```html
<div class="prompt-block my-4">
  <button class="copy-btn" onclick="copyPrompt(this)">Copy</button>
  <pre><code>Your prompt template here. Replace [brackets] with your specifics.</code></pre>
</div>
```

### Add a new sub-section heading

```html
<h4 class="prompt-sub-heading">🔖 My Sub-Section Title</h4>
```

### Add a whole new category

1. Add a filter button:
```html
<button class="filter-btn" onclick="filterPrompts('mycat', this)">🆕 My Category</button>
```

2. Add the category header and group:
```html
<h3 class="text-2xl font-semibold mt-10 mb-2 text-indigo-700 category-header" data-category="mycat">
  🆕 My Category
</h3>
<div class="category-group" data-category="mycat">
  <!-- prompt blocks go here -->
</div>
```

---

## 🧱 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content |
| [Tailwind CSS](https://tailwindcss.com) (CDN) | Utility-first styling |
| [Google Fonts](https://fonts.google.com) — Inter + Sora | Typography |
| Vanilla JavaScript | Dark mode, copy, quiz, scroll, filter |
| GitHub Pages | Free hosting |

Zero npm packages. Zero build tools. Zero frameworks. Opens in any browser from 2018+.

---

## 🤝 Contributing

Contributions are very welcome — especially new prompts, bug fixes, or accessibility improvements.

**Quick contribution via GitHub website (no Git needed):**

1. Click **Fork** on this repo (top-right)
2. In your fork, click `index.html` → the pencil ✏️ edit icon
3. Make your changes
4. Scroll down → choose **"Create a new branch"** → click **Propose changes**
5. Click **Create pull request**

**What makes a great prompt contribution:**
- Uses `[bracketed placeholders]` for anything user-specific
- Specific enough to get a useful result, flexible enough to adapt
- Fits naturally into one of the existing sub-sections
- Doesn't duplicate an existing prompt

---

## 🐛 Found a Bug?

Open an [issue](../../issues/new) and include:
- What you expected to happen
- What actually happened
- Your browser and OS

---

## 📄 License

This project is open-source under the **[MIT License](LICENSE)** — you're free to use, modify, and distribute it for personal or commercial projects. Attribution appreciated but not required.

---

## 🌟 Show Your Support

If this guide helped you, consider:

- ⭐ **Starring this repo** — it helps others discover it
- 🍴 **Forking it** — make it your own
- 📢 **Sharing the live link** — spread the knowledge

---

<div align="center">

Made with ❤️ for the AI-curious.

**[⬆ Back to top](#-prompt-like-a-pro)**

</div>
