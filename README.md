# DevOps Portfolio Website

![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-21d26a?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Overview

This is **Project 1** of my DevOps learning journey — a personal portfolio website built and managed as a professional software project.

The goal was not just to build a website, but to practise the complete workflow a DevOps engineer uses daily:

- Working inside a **Linux environment** (Ubuntu WSL2)
- Managing code with **Git version control**
- Hosting a repository on **GitHub**
- Testing locally with a **Python web server**
- Writing professional **project documentation**
- Deploying publicly via **GitHub Pages**

**Live Site:** [https://AlabaJimoh.github.io/devops-portfolio-website](https://AlabaJimoh.github.io/devops-portfolio-website)

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling and layout |
| Git | Version control and change tracking |
| GitHub | Remote repository and collaboration platform |
| Ubuntu WSL2 | Linux development environment on Windows |
| VS Code | Primary code editor |
| Python 3 | Local web server for testing (`http.server`) |
| GitHub Pages | Free static site hosting |

---

## Project Structure

```
devops-portfolio-website/
│
├── index.html          # Main website page
├── style.css           # All website styling
├── README.md           # Project documentation (this file)


├── screenshots/        # Evidence the project works
│   ├── website-homepage.png
│   ├── vscode-project.png
│   ├── ubuntu-terminal.png
│   ├── git-log.png
│   └── github-repository.png




---

## Installation & Running Locally

### Prerequisites

- Ubuntu WSL2 (or any Linux environment)
- Git installed
- Python 3 installed
- VS Code (recommended)

### Steps

**Clone the repository:**
```bash
git clone https://github.com/AlabaJimoh/devops-portfolio-website.git
```

**Navigate to the project directory:**
```bash
cd devops-portfolio-website
```

**Start a local web server:**
```bash
python3 -m http.server 8000
```

**Open in your browser:**
```
http://localhost:8000
```

---

## Git Workflow Used

Every coding session followed this workflow:

```bash
# Check what has changed
git status

# Stage all changes
git add .

# Commit with a meaningful message
git commit -m "Describe what changed and why"

# Push to GitHub
git push
```

### Commit History Highlights

| Commit | Description |
|---|---|
| `feat: initial project structure` | Created folders, index.html, style.css |
| `feat: add homepage content and layout` | Built main HTML sections |
| `style: add CSS dark theme and skills grid` | Styled all components |
| `docs: add professional README` | Wrote full project documentation |
| `docs: add project screenshots` | Added visual evidence of working project |

---



---

## Key Concepts Demonstrated

**Git vs GitHub:**
Git is the local version control tool. GitHub is the remote platform that hosts the repository online.

**Why version control?**
Every change is tracked with a timestamp and message. If something breaks, I can see exactly what changed and revert it.

**Why branches?**
Branches let me experiment without touching the stable `main` branch. I created a `feature-homepage` branch for initial development.

**What is localhost:8000?**
Python's built-in HTTP server runs locally on port 8000, letting me test the website before pushing to GitHub.

---

## Lessons Learned

- Linux terminal navigation and file management
- Initialising and managing a Git repository from scratch
- Writing meaningful commit messages that explain *why*, not just *what*
- Connecting a local repo to GitHub with `git remote add origin`
- The difference between `git add`, `git commit`, and `git push`
- How GitHub Pages deploys a static site automatically from the `main` branch
- Writing professional README documentation

---

## Future Improvements

- Responsive mobile design with media queries
- Dark/light mode toggle with JavaScript
- Contact form with form submission handling
- Animated project cards
- Custom domain integration
- GitHub Actions CI/CD pipeline (→ Project 2)
- Docker containerisation (→ Project 3)

---

## Author

**Alaba Jimoh**
Aspiring DevOps Engineer

GitHub: [https://github.com/AlabaJimoh](https://github.com/AlabaJimoh)
Live Site: [https://AlabaJimoh.github.io/devops-portfolio-website](https://AlabaJimoh.github.io/devops-portfolio-website)
