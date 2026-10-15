# Diego Corsino - Portfolio Website

A personal portfolio website designed and developed to showcase my software engineering projects, technical skillset, leadership experience, and background in a clean, elegant, and professional manner.

## 🎯 Purpose

This repository hosts the source code for my personal portfolio. It serves as a centralized, interactive hub to highlight my work to prospective employers, collaborators, and recruiters, presenting:
- In-depth breakdowns and case studies of technical projects.
- Academic background and leadership achievements as a Computer Science student and Club President.
- Practical experience in software development, IoT cybersecurity, and teamwork.
- Direct access to my resume, GitHub repositories, and contact information.

---

## 🌟 Featured Projects

- **Pokedex App**  
  A full-featured Pokémon application showcasing comprehensive data visualization, Android/mobile development, UI/UX design in Figma, and software engineering best practices including Git branching workflows and quality assurance testing.

- **Hydroficient IoT Cyber Defense Externship**  
  A comprehensive IoT security project focused on building, auditing, and securing IoT infrastructure. Highlights include STRIDE threat modeling, simulated cyberattacks (packet spoofing, replay attacks, unauthorized control), insecure MQTT pipeline analysis, and implementing TLS/mTLS defenses alongside real-time monitoring dashboards.

---

## 🧭 Sections & Features

- **Home / Hero**: Introduction, current availability status ("Open to work"), quick resume download, and navigation call-to-actions.
- **Work Samples**: Grid of featured project cards with technology tags, summaries, and links to detailed project case studies.
- **Project Deep Dives**: Multi-step project breakdowns with interactive accordions, architectural overviews, deliverable links (Google Colab, Google Docs), and outcomes.
- **About Me**: Professional biography, education history (Muhlenberg College), professional experience, and technical skill tags.
- **Contact**: Fast access to email, LinkedIn, and GitHub profiles.

---

## 🛠️ Built With

- **HTML5**: Semantic, accessible markup.
- **Tailwind CSS (v3.4 CDN)**: Modern styling with custom color tokens and warm palette theme.
- **Google Fonts**: Typography pairing featuring *DM Serif Display* for headings and *Inter* for body text.
- **Vanilla JavaScript**: Lightweight client-side hash routing (`#home`, `#works`, `#about`, `#work-...`), interactive accordion cards, and mobile responsive navigation drawer.

---

## 🚀 Running Locally

This project is a static site with no external build steps required.

1. Clone the repository:
   ```bash
   git clone https://github.com/Pikalyx/Portfolio-Website.git
   cd Portfolio-Website
   ```

2. Open `index.html` directly in your web browser:
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # Or serve using Python's built-in HTTP server:
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser.

---

## 🌐 Deploying to GitHub Pages

Since this portfolio is a static site with `index.html` at the project root, it can be hosted directly on GitHub Pages with zero build configuration:

1. **Push code to GitHub**:
   ```bash
   git add .
   git commit -m "Update portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Navigate to your repository on GitHub: [`Pikalyx/Portfolio-Website`](https://github.com/Pikalyx/Portfolio-Website).
   - Click the **Settings** tab at the top.
   - In the left sidebar under **Code and automation**, click **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Under **Branch**, select `main` and the `/ (root)` folder, then click **Save**.

3. **Access the live site**:
   - GitHub Actions will automatically run the Pages deployment workflow (viewable in the **Actions** tab).
   - Once deployed, your site will be live at:
     ```
     https://pikalyx.github.io/Portfolio-Website/
     ```

---

## 📬 Contact & Links

- **Email**: [diegocorsino12@gmail.com](mailto:diegocorsino12@gmail.com)
- **LinkedIn**: [linkedin.com/in/diego-corsino](https://linkedin.com/in/diego-corsino)
- **GitHub**: [github.com/pikalyx](https://github.com/pikalyx)

