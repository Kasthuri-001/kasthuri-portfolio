# Kasthuri | Personal Portfolio

A personal portfolio website showcasing my projects, skills, and experience in **cybersecurity, AI/ML, and software development** — built with a cybersecurity-themed dark UI and dynamically pulls live project data from GitHub.

🔗 **Live Site:** [Add deployed link here]
🔗 **GitHub:** [Kasthuri-001](https://github.com/Kasthuri-001)

## Features

- 🌑 **Cybersecurity-Themed Design** — dark background with pastel accent colors for a modern, security-focused aesthetic
- ⚡ **Live GitHub Integration** — pulls repository details (name, description, stars, languages) directly from the GitHub API, so featured projects always stay up to date
- 📱 **Responsive Design** — optimized for desktop, tablet, and mobile
- 📄 **Resume/CV Download** — quick access to my latest resume
- 🧭 **Smooth Navigation** — single-page layout with smooth scrolling between sections
- 📬 **Contact Section** — direct way to reach out via email or social links

## Sections

- **Home** — introduction and quick overview
- **About** — background, education, and interests
- **Skills** — technical skills across cybersecurity, AI/ML, and full-stack development
- **Projects** — dynamically fetched from GitHub, including:
  - Phishing URL Detector (Node.js/Express, ML-based detection)
  - Android Static Analysis Framework (Python, APK vulnerability analysis)
  - Secure Chat Application (Java sockets, end-to-end encryption)
- **Certifications** — professional certifications earned
- **Experience** — internship history (Java Developer, AI Intern)
- **Contact** — form/links to connect

## Tech Stack

| Layer         | Technology                          |
|----------------|--------------------------------------|
| Frontend        | HTML, CSS, JavaScript (or React, if used) |
| Styling          | Custom CSS / Tailwind (update as applicable) |
| Data              | GitHub REST API                      |
| Hosting            | GitHub Pages / Vercel / Netlify (update as applicable) |

## Getting Started

### Prerequisites

- Node.js (if using a JS framework/build tool)
- A GitHub personal access token (optional, for higher API rate limits)

### Installation

```bash
git clone https://github.com/Kasthuri-001/portfolio.git
cd portfolio
npm install
```

### Configuration

Update the GitHub username in the config file to pull your own repositories:

```js
const GITHUB_USERNAME = "Kasthuri-001";
```

### Run Locally

```bash
npm start
```

The site will be available at `http://localhost:3000` (or the port configured in your project).

### Build for Production

```bash
npm run build
```

## Project Structure

```
portfolio/
├── public/               # Static assets (images, favicon, resume PDF)
├── src/
│   ├── components/       # Reusable UI components (Navbar, ProjectCard, etc.)
│   ├── pages/             # Page-level sections (About, Projects, Contact)
│   ├── api/                # GitHub API integration
│   └── styles/             # CSS/theme files
├── package.json
└── README.md
```

## Deployment

This site is deployed via [GitHub Pages / Vercel / Netlify — update as applicable]. Every push to `main` automatically triggers a new deployment.

## Future Improvements

- [ ] Add dark/light mode toggle
- [ ] Add blog/writing section
- [ ] Add project filtering by tech stack
- [ ] Add analytics for visitor insights

## Author

**Kasthuri**
B.Tech Information Technology, VSB College of Engineering Technical Campus
GitHub: [Kasthuri-001](https://github.com/Kasthuri-001)

## License

This project is open source and available under the [MIT License](LICENSE).
