# 🌐 Web Development & Designing – Internship Projects

Projects built for the **Web Development & Designing** track of my Oasis Infobyte internship,
covering **Level 1** (3 tasks) and **Level 2** (4 tasks) using HTML5, CSS3 and vanilla JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📁 Projects

### Level 1
| # | Project | Highlights |
|---|---------|-----------|
| 1 | [Landing Page](level1/task1_landing_page) | Sticky navbar, hero + CTA, Features / About / Testimonials, footer, fully responsive (HTML + CSS only) |
| 2 | [Personal Portfolio](level1/task2_portfolio) | Hero with avatar, About, Skills grid, Project cards, Contact, smooth scroll |
| 3 | [Temperature Converter](level1/task3_temperature_converter) | °C / °F / K, live validation, shows all units at once, absolute-zero check |

### Level 2
| # | Project | Highlights |
|---|---------|-----------|
| 1 | [Calculator](level2/task1_calculator) | CSS Grid layout, operator chaining, backspace, divide-by-zero handling, keyboard support, no `eval()` |
| 2 | [Tribute Page](level2/task2_tribute_page) | Tribute to Dr. A.P.J. Abdul Kalam: biography, timeline, quote block, 2 fonts, multiple background colours |
| 3 | [To-Do Web App](level2/task3_todo_app) | Add / complete / edit / delete, pending & completed lists with counts, timestamps, `localStorage` |
| 4 | [Login Authentication System](level2/task4_login_system) | Register, login, protected dashboard, logout, salted SHA-256 password hashing |

## 🗂️ Folder Structure
```
├── index.html                 (links to all projects)
├── level1/
│   ├── task1_landing_page/
│   ├── task2_portfolio/
│   └── task3_temperature_converter/
└── level2/
    ├── task1_calculator/
    ├── task2_tribute_page/
    ├── task3_todo_app/
    └── task4_login_system/
```

## ▶️ How to Run
1. Download or clone the repository.
2. Open the root `index.html` in your browser and click a project, **or** open any project's `index.html` directly.
3. No installation or build step is needed.

> The Login System uses the browser's Web Crypto API, so open it from `localhost`, `file://` (Chrome/Firefox) or a `https` site such as GitHub Pages.

## 🚀 Live Demo (GitHub Pages)
Repository **Settings → Pages → Branch: `main` / root → Save**.
Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

## 🔐 Login System Notes
- Passwords are never stored in plain text: each user gets a random salt and a SHA-256 hash.
- Password rule: minimum 8 characters with at least 1 number.
- Wrong credentials show one generic message, so it does not reveal which field was wrong.
- Session is kept in `sessionStorage`, cleared on logout, and the dashboard redirects to login without a session.
- This is a front-end learning demo; real applications must authenticate on a server.

## 🖼️ Tribute Page Image
Add a royalty-free portrait from [Wikimedia Commons](https://commons.wikimedia.org) as
`level2/task2_tribute_page/images/kalam.jpg`. A placeholder avatar is shown until then.

## 🧰 Tech Stack
HTML5 · CSS3 (Flexbox, Grid) · JavaScript (ES6) · Web Storage API · Web Crypto API

## 📜 License
For educational purposes (internship submission).
