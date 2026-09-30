# C3 — Campus to Corporate 🚀

> **From Campus to Corporate.**
> Learn skills. Build connections. Create opportunities.

C3 (Campus to Corporate) is a **student-driven technology community** focused on helping CSE students develop the technical, professional, communication, leadership, and industry-oriented skills required to transition confidently from college to the corporate world.

This repository contains the source code for the **C3 Campus to Corporate website**, along with a GitHub Actions CI/CD workflow for automated testing, building, and deployment to GitHub Pages.

---

## 🌐 Live Website

**C3 — Campus to Corporate**

🔗 https://ashfaq-ahmed02.github.io/c3-testing/

---

## 📌 About C3

C3 is designed to bridge the gap between:

```text
        CAMPUS
           │
           ▼
   ┌─────────────────┐
   │     C3 CLUB     │
   │                 │
   │ Learn           │
   │ Build           │
   │ Collaborate     │
   │ Communicate     │
   │ Lead            │
   └─────────────────┘
           │
           ▼
       CORPORATE
```

The community focuses on practical learning rather than only academic theory.

### 🎯 Mission

To help students bridge the gap between academic learning and real-world industry skills through:

* Hands-on sessions
* Practical projects
* Technical learning
* Communication activities
* Collaboration
* Industry-oriented preparation

### 👁️ Vision

To build a strong student technology community where members continuously:

**Learn → Share → Build → Collaborate → Grow**

---

## ✨ Website Features

The website provides a modern, responsive interface for exploring the C3 community.

### 🏠 Home

* C3 introduction
* Campus-to-Corporate concept
* Community statistics
* Why C3 section
* Domain overview
* Event highlights
* Community call-to-action

### 👥 About

* C3 mission
* C3 vision
* Community values
* Growth journey
* What makes C3 different

### 💻 Domains

C3 provides multiple learning domains:

* 🎨 Design & Development
* 🤖 AI & Machine Learning
* 🔐 Networking & Cybersecurity
* 📊 Data Analytics
* 🗣️ Communication Skills

### 👨‍💻 Team

The team section contains:

* Leadership
* Domain teams
* Team filtering
* Community roles

### 📅 Events

The website provides sections for:

* Upcoming events
* Recent events
* Workshops
* Technical sessions
* Hands-on learning activities

### 🤝 Join C3

Students can explore the community and learn how to become part of C3.

---

## 🛠️ Tech Stack

This project intentionally uses a lightweight frontend architecture.

| Technology     | Purpose                          |
| -------------- | -------------------------------- |
| HTML5          | Website structure                |
| Tailwind CSS   | UI styling                       |
| JavaScript     | Interactions and dynamic content |
| Google Fonts   | Typography                       |
| Git            | Version control                  |
| GitHub         | Source code hosting              |
| GitHub Actions | CI/CD automation                 |
| GitHub Pages   | Website deployment               |

### 🎨 UI Technologies

The website uses:

* **Tailwind CSS CDN**
* **Space Grotesk**
* **Inter**
* **JetBrains Mono**
* Custom CSS animations
* Responsive layouts
* CSS gradients
* SVG graphics

---

## 📁 Project Structure

```text
c3-testing/
│
├── .github/
│   └── workflows/
│       ├── main.yml
│       └── main1.yml
│
├── index.html
│
└── README.md
```

### `index.html`

The main website file containing:

* HTML structure
* Tailwind configuration
* Custom CSS
* JavaScript
* Navigation
* Website sections
* Dynamic content
* Animations

### `.github/workflows/`

Contains GitHub Actions workflows responsible for automatically testing, building, and deploying the website.

---

# ⚙️ CI/CD Pipeline

This project includes a GitHub Actions CI/CD pipeline.

Every time changes are pushed to the `main` branch, the workflow can automatically:

```text
Developer
    │
    ▼
Git Push
    │
    ▼
GitHub Repository
    │
    ▼
Continuous Integration
    │
    ├── Checkout Code
    │
    └── Test index.html
    │
    ▼
Build
    │
    └── Create build/
         │
         └── Copy index.html
    │
    ▼
Deploy
    │
    └── GitHub Pages
    │
    ▼
🌐 Live Website
```

---

## 🔄 CI — Continuous Integration

The CI stage checks whether the required website file exists.

```bash
test -f index.html
```

If the file exists:

```text
HTML file exists!
CI test passed!
```

This provides a basic automated validation before deployment.

---

## 🏗️ Build Stage

The build stage creates a production directory:

```bash
mkdir build
cp index.html build/
```

The generated `build/` directory is then uploaded as a GitHub Pages artifact.

---

## 🚀 Deployment

After the build succeeds, GitHub Actions deploys the website using:

```text
actions/deploy-pages@v4
```

The website is hosted through **GitHub Pages**.

---

# 🧪 Run Locally

Because this is a static website, you don't need Node.js, Python, or a backend server to view the basic project.

### 1. Clone the repository

```bash
git clone https://github.com/ashfaq-ahmed02/c3-testing.git
```

### 2. Enter the project

```bash
cd c3-testing
```

### 3. Open the website

You can simply open:

```text
index.html
```

in your browser.

### Recommended

For development, use **VS Code Live Server** or another local static server.

---

# 💡 Development Workflow

A typical development workflow looks like:

```bash
# Clone
git clone https://github.com/ashfaq-ahmed02/c3-testing.git

# Enter project
cd c3-testing

# Make changes
code .

# Check changes
git status

# Add changes
git add .

# Commit
git commit -m "Update C3 website"

# Push
git push origin main
```

After pushing to `main`, GitHub Actions handles the CI/CD process.

---

# 🔐 Accessibility & UX

The website includes several usability considerations:

* Responsive layout
* Mobile navigation
* Keyboard focus states
* Smooth scrolling
* Reduced-motion support
* Responsive typography
* Mobile-friendly sections
* Semantic HTML structure

The project also includes support for:

```css
@media (prefers-reduced-motion: reduce)
```

to reduce animations for users who prefer less motion.

---

# 🎨 Design System

The website follows a **Campus → Corporate** visual concept.

### Campus

Represented primarily through:

```text
Blue / Cyan
```

### Corporate

Represented primarily through:

```text
Orange / Amber
```

### Overall Style

```text
Dark background
      +
Cyan Campus
      +
Orange Corporate
      =
Campus → Corporate
```

The design uses gradients to visually represent the transition from campus life to the corporate environment.

---

# 📈 Future Improvements

Possible future improvements include:

* [ ] Connect the Join Us form to a backend
* [ ] Add real team member profiles
* [ ] Add event registration
* [ ] Add event certificates
* [ ] Add admin dashboard
* [ ] Add database integration
* [ ] Add authentication
* [ ] Add CMS for managing events
* [ ] Add automated HTML validation
* [ ] Add Lighthouse performance checks
* [ ] Add automated deployment notifications

---

# 🤝 Contributing

Contributions and suggestions are welcome.

### Contribution workflow

```text
Fork Repository
      ↓
Create Branch
      ↓
Make Changes
      ↓
Commit Changes
      ↓
Push Branch
      ↓
Create Pull Request
      ↓
Review
      ↓
Merge
```

For major changes, open an issue first to discuss the proposed modification.

---

# 📜 License

This project currently does not specify a separate open-source license.

Please contact the repository owner before redistributing or reusing the project commercially.

---

# 👨‍💻 Author

**Ashfaq Ahmed**

Computer Science & Engineering Student
President — C3 (Campus to Corporate Club)

GitHub:
https://github.com/ashfaq-ahmed02

---

## ⭐ C3

**Learn. Build. Grow.**

> Bridging the gap between **Campus and Corporate** — one student at a time.
