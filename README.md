# 🌍 ClimateAct — SDG 13 Climate Action Website

A multi-page, responsive website built as a group coursework project for **UN Sustainable Development Goal 13: Climate Action**. The site combines an animated splash screen, an interactive Action Impact Simulator, individual research content pages, a feedback form, a team showcase, and a user profile builder — all sharing one consistent HTML/CSS template.

> Built for **Web Design & Development (4COSC011W)**, University of Westminster, 2025/26.

---

## 🔗 Live Pages

| Page | File | Description |
|---|---|---|
| Splash Screen | `splash.html` | Animated welcome screen with a 4-second auto-redirect and skip button |
| Home | `home.html` | Hero video banner, key climate stats, mission cards, content gallery preview |
| Gallery | `gallery.html` | Visual gallery of climate-related media |
| Action Simulator | `ais.html` | Interactive tool where users pick real-life actions and see their estimated impact |
| Feedback | `feedback.html` | Program directory + validated feedback form with a live character counter |
| Team | `team.html` | Hover/keyboard-expandable cards introducing each team member's contributions |
| Profile | `profile.html` | Step-by-step interactive profile builder with a progress indicator |
| Sitemap | `sitemap.html` | Interactive SVG sitemap of the whole site |
| Content Pages | `content_ST1–4.html` | Each student's individual research page on a climate sub-topic |
| Page Editors | `pageEditor_ST1–4.html` | Per-student technical write-ups explaining HTML/CSS/JS decisions |
| Validation Pages | `validation_ST1–4.html` | Per-student W3C Markup Validator evidence and reflections |

---

## 🧑‍🤝‍🧑 Team & Contributions

| Student | Name | ID | Contribution |
|---|---|---|---|
| Student 1 | Dipak Kumar Raut | w2121999 | Shared template & global CSS, Home page, Gallery page |
| **Student 2** | **Tirth Raj Bhatta** | **w2121964** | **Splash screen (loader + countdown), Action Impact Simulator** |
| Student 3 | Aryan Pratap Singh | w2121988 | Feedback & Program Directory, Team page, Content page (Sustainable Transport) |
| Student 4 | Himanshu Narayan Shrestha | w2122002 | User Profile, SVG Sitemap, Content page (Food & Climate) |

Each student also authored their own **content page** (individual research), **page editor** (technical documentation), and **validation page** (W3C compliance evidence).

---

## 🌱 Topics Covered

- The science of climate change
- Renewable energy solutions
- Sustainable transport
- Food & climate

---

## 🛠️ Built With

- **HTML5** — semantic structure shared via one common template
- **CSS3** — a single global stylesheet (`style.css`) with CSS custom properties for a shared colour palette, spacing, and typography, plus page-specific `<style>` blocks
- **Vanilla JavaScript** — no frameworks; used for the splash screen countdown, form validation, live character counters, the Action Impact Simulator's calculations, the interactive profile builder, and expandable team cards
- **Inline SVG** — the sitemap page

No build tools, package managers, or frameworks are required — the site is pure static HTML/CSS/JS.

---

## ▶️ Running Locally

Since this is a static site, no installation is required:

1. Clone the repository
2. Open `splash.html` in a browser (or `home.html` to skip the intro)
3. Optionally serve it locally for a smoother experience, e.g.:
   ```bash
   npx serve .
   ```
   or
   ```bash
   python3 -m http.server
   ```

---

## ✅ Accessibility & Standards Compliance

Every page was validated against the **W3C Markup Validation Service** (validator.w3.org), with results and reflections documented on each student's individual validation page. Accessibility features across the site include:

- Semantic HTML5 sectioning elements and a consistent heading hierarchy
- ARIA roles and labels (e.g. `role="button"`, `role="progressbar"`, `aria-live`)
- Keyboard-accessible interactive elements (`tabindex`, focus states)
- Descriptive `alt` text on all images
- A dedicated accessibility statement link in the footer of every page

---

## 📁 Project Structure

```
├── splash.html              # Landing/intro screen
├── home.html                 # Homepage
├── gallery.html               # Media gallery
├── ais.html                   # Action Impact Simulator
├── feedback.html              # Feedback form & program directory
├── team.html                  # Team page
├── profile.html                # User profile builder
├── sitemap.html                # SVG sitemap
├── content_ST1.html ... ST4.html      # Individual research pages
├── pageEditor_ST1.html ... ST4.html   # Individual technical write-ups
├── validation_ST1.html ... ST4.html   # Individual W3C validation evidence
├── style.css                  # Shared global stylesheet
├── climate-bg-video.mp4        # Hero background video
└── images/                    # Site images, logos, validator screenshots
```

---

## 📜 License

This project was created for academic coursework purposes and is not licensed for commercial use.