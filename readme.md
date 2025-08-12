# Ritwik Joshi Personal Website

Welcome to the official repository for [Ritwik Joshi's personal website](https://ritwikjoshi.github.io). This project is built using GitHub Pages and showcases Ritwik's portfolio, blog, and contact information.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation & Local Setup](#installation--local-setup)
- [Directory Structure](#directory-structure)
- [Usage Guide](#usage-guide)
- [Development Guidelines](#development-guidelines)
- [Deployment Instructions](#deployment-instructions)
- [Troubleshooting & FAQ](#troubleshooting--faq)
- [Contribution Guidelines](#contribution-guidelines)
- [Contact](#contact)
- [License](#license)

---

## Project Overview

This repository hosts the source code for Ritwik Joshi’s personal website. It is designed to provide information about Ritwik’s professional background, blog posts, projects, and ways to get in touch. Built as a static website, it leverages GitHub Pages for easy hosting and deployment.

---

## Features

- **Homepage:** Personal introduction and highlights.
- **Portfolio:** Showcase of selected projects with descriptions and links.
- **Blog:** A series of posts on technical topics and personal reflections.
- **About:** Background, skills, and resume information.
- **Contact:** Email, social media, and a contact form.
- **Responsive Design:** Mobile-friendly and accessible.

---

## Technology Stack

- **HTML5**: Markup for structure.
- **CSS3**: Styling and layouts; possibly with frameworks like Bootstrap or custom styles.
- **JavaScript**: Interactive components; may include libraries like jQuery or vanilla JS.
- **(Optional) Jekyll**: If enabled, for templating and blog management.
- **GitHub Pages**: Hosting and automatic deployment.

---

## Installation & Local Setup

### 1. Prerequisites

- [Git](https://git-scm.com/) for version control.
- Modern web browser (Chrome, Firefox, Edge, etc.).
- (Optional, for advanced editing) [Node.js](https://nodejs.org/) and [npm](https://npmjs.com/) for frontend tooling.
- (Optional, if using Jekyll) [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/).

### 2. Clone the Repository

```sh
git clone https://github.com/Ritwikjoshi/ritwikjoshi.github.io.git
cd ritwikjoshi.github.io
```

### 3. Local Preview

#### Static HTML/CSS/JS
- Open `index.html` in your web browser to preview the site.

#### Jekyll (if enabled)
```sh
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```
- Visit [http://localhost:4000](http://localhost:4000) in your browser.

### 4. Editing

- Use a code editor like [VS Code](https://code.visualstudio.com/) or [Sublime Text](https://www.sublimetext.com/) for editing files.

---

## Directory Structure

```
ritwikjoshi.github.io/
├── index.html           # Main landing page
├── assets/              # Images, CSS, JavaScript files
│   ├── css/
│   ├── images/
│   └── js/
├── _posts/              # Blog posts (if using Jekyll)
├── about.html           # About page
├── contact.html         # Contact page
├── README.md            # Project documentation
├── CNAME                # Custom domain configuration (if used)
└── ...                  # Other files (e.g., resume.pdf, robots.txt)
```

**Note:** The structure may vary based on your setup. Update as necessary.

---

## Usage Guide

### Viewing the Website

- Visit [https://ritwikjoshi.github.io](https://ritwikjoshi.github.io) for the live site.
- Navigate between pages using the site menu.

### Adding Blog Posts

- If using Jekyll, add Markdown files to the `_posts` directory.
- Filename format: `YYYY-MM-DD-title.md`
- Example front matter:
  ```markdown
  ---
  title: "My First Blog Post"
  date: 2025-08-12
  tags: [web, github]
  ---
  Content goes here...
  ```

### Updating Portfolio

- Edit the relevant HTML or Markdown files within the project directory.
- Add images to `assets/images/` and link them in your portfolio section.

### Customizing Styles

- Modify CSS files in `assets/css/` for layout, fonts, and colors.

---

## Development Guidelines

### Coding Standards

- Use semantic HTML tags for structure.
- Keep code readable and well-commented.
- Follow accessibility best practices (alt text for images, ARIA roles).

### Best Practices

- Organize assets logically.
- Test changes locally before committing.
- Use descriptive commit messages (e.g., `fix: update contact form validation`).

### Version Control

- Create feature branches for new additions.
- Submit changes via pull requests if collaborating.

---

## Deployment Instructions

### Automatic Deployment (GitHub Pages)

- **Default Branch:** The `main` branch is published automatically by GitHub Pages.
- **Update Site:** Commit and push changes to `main`—no manual deployment needed.

### Custom Domain

- Add your domain name to the `CNAME` file.
- Configure DNS settings as per [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

---

## Troubleshooting & FAQ

### Site Not Updating?

- Check GitHub Pages build status in repository settings.
- Ensure commits are pushed to the correct branch (`main`).
- Wait a few minutes; builds can be delayed.

### Broken Images or Styles?

- Verify file paths and case sensitivity.
- Ensure files are tracked by Git.

### Adding/Updating Blog Posts (Jekyll)?

- Confirm post files are in `_posts/` with correct front matter.

### Custom Domain Not Working?

- Review DNS setup and `CNAME` file.
- Check for propagation delays.

---

## Contribution Guidelines

### How to Contribute

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and test locally.
4. Submit a pull request with a clear description.

### What to Contribute

- Bug fixes.
- New features (portfolio, blog posts, UI enhancements).
- Documentation improvements.

### Code of Conduct

- Be respectful and collaborative.
- Follow the repository’s [Code of Conduct](CODE_OF_CONDUCT.md) if present.

---

## Contact

For questions, feedback, or collaboration:

- GitHub Issues: [Open an issue](https://github.com/Ritwikjoshi/ritwikjoshi.github.io/issues)
- Email: [YOUR_EMAIL_HERE]
- Twitter: [YOUR_TWITTER_HANDLE]
- LinkedIn: [YOUR_LINKEDIN_PROFILE]

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

*Feel free to customize and enhance this documentation as your website evolves!*