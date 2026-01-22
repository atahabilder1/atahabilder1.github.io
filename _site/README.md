# Anik Tahabilder - Portfolio Website

A modern, responsive portfolio website built with Jekyll for GitHub Pages.

**Live Site:** [atahabilder1.github.io](https://atahabilder1.github.io)

## Features

- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Dark/Light Mode** - Toggle between themes with preference persistence
- **Interactive Elements**
  - Typing animation with optional sound effects
  - Keyboard backlight-style glow animation on skill cards
  - Smooth scroll and navigation highlights
- **Sections**
  - Hero with social links
  - About Me
  - Research interests with project showcases
  - Publications with highlighted citations
  - Education timeline
  - Teaching experience
  - Technical skills with icon cards and star ratings
  - Awards and achievements
  - Contact information

## Tech Stack

- **Framework:** Jekyll (GitHub Pages)
- **Styling:** Custom CSS with CSS Variables
- **Icons:** Font Awesome 6
- **Fonts:** Inter (Google Fonts)
- **Animations:** Pure CSS keyframes
- **Audio:** Web Audio API for typing sounds

## Project Structure

```
.
├── index.html          # Main portfolio page
├── css/
│   └── style.css       # All styles
├── _config.yml         # Jekyll configuration
├── _posts/             # Blog posts (if any)
├── sitemap.xml         # SEO sitemap
└── README.md           # This file
```

## Local Development

1. **Prerequisites:** Ruby and Bundler installed

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run local server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open in browser:**
   ```
   http://localhost:4000
   ```

## Customization

- Edit `_config.yml` for site metadata
- Modify `index.html` for content changes
- Update `css/style.css` for styling adjustments
- CSS variables in `:root` control the color scheme

## Author

**Anik Tahabilder**
PhD Student, Wayne State University
Blockchain | Machine Learning | Data Science

- [Google Scholar](https://scholar.google.com/citations?hl=en&user=RzSbIO4AAAAJ)
- [LinkedIn](https://www.linkedin.com/in/aniktahabilder/)
- [GitHub](https://github.com/atahabilder1)
- [ORCID](https://orcid.org/0000-0002-9555-6727)

## License

This project is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to:
- **Share** - copy and redistribute the material in any medium or format
- **Adapt** - remix, transform, and build upon the material for any purpose

**Under the following terms:**
- **Attribution** - You must give appropriate credit, provide a link to the license, and indicate if changes were made. You must include a link to the original repository and mention the author's name.

See the [LICENSE](LICENSE) file for details.

---

**If you use this template, please provide attribution by linking back to this repository and mentioning Anik Tahabilder as the original author.**
