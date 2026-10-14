# Harsha R – Portfolio

Personal portfolio website of **Harsha R**, a Computer Science and Engineering student at Presidency University, Bengaluru, graduating July 2027.

**Live site:** https://portfolio-mu-blush-23.vercel.app/

## About

A single-page portfolio that shows my background, projects, certifications and skills, and makes it easy for recruiters to contact me. I am currently open to work.

## Sections

| Section | What it shows |
|---|---|
| Intro | Name, "Open to work" badge, links to resume, GitHub and LinkedIn |
| About me | A short introduction and a summary of my software development skills |
| Experience and education | Development Intern at StaxTech (July 2025) and B.Tech in CSE |
| Projects | MindBridge, Form Builder Application, Online Quiz Web Application, Student Performance Prediction |
| Certifications | HackerRank skill certificates, each linked to its verification page |
| Skills | Languages, frameworks, databases and tools |
| Contact | Email, resume, LinkedIn and GitHub |

## Features

- Responsive layout that works on phones, tablets and desktops
- Light and dark themes, with a toggle that remembers your choice
- Clean bento-style layout with clearly separated sections
- No build step, frameworks or dependencies: one static HTML file

## Tech stack

| Part | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Behavior | Vanilla JavaScript (theme toggle) |
| Fonts | Space Grotesk and DM Sans from Google Fonts |
| Hosting | Vercel |

## Project structure

```
portfolio/
├── index.html   # the whole site: markup, styles and script
└── README.md
```

## Run locally

1. Clone the repository:
```bash
   git clone https://github.com/harsha9353-34/portfolio.git
```
2. Open the folder and double-click `index.html`, or serve it with any static server:
```bash
   npx serve .
```

## Deploy on Vercel

1. Push this repository to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Set the framework preset to **Other** and leave the build settings empty.
4. Click **Deploy**.

Every commit to the main branch redeploys the site automatically.

## Customize

All content is in `index.html`. Edit the text inside each `<section>` to update projects, skills or contact details. Theme colors are CSS variables at the top of the `<style>` block.

## Contact

- Email: harsha9353140091@gmail.com
- LinkedIn: https://www.linkedin.com/in/harsha-engineer9353
- GitHub: https://github.com/harsha9353-34
