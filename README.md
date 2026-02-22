# Aastha Setia — Personal Portfolio Website

A clean, modern, and fully responsive personal portfolio website built with pure HTML, CSS, and vanilla JavaScript. Designed to showcase Aastha Setia's background in Data Science, Analytics, and Mathematics.

---

## 🌐 Live Preview

Open `index.html` in any modern browser to view the portfolio locally.

---

## 📁 Project Structure

```
portfolio/
│
├── index.html        # Main portfolio file (all-in-one: HTML + CSS + JS)
└── README.md         # Project documentation
```

> The entire portfolio is a **single self-contained HTML file** — no build tools, no dependencies, no frameworks required.

---

## ✨ Features

- **Fully Responsive** — adapts gracefully to mobile, tablet, and desktop screens
- **Smooth Scroll Navigation** — fixed navbar with active section highlighting
- **Scroll-Reveal Animations** — sections animate in as you scroll using IntersectionObserver
- **Hero Entry Animations** — staggered fade-up/fade-left effects on page load
- **Noise Texture Overlay** — subtle grain effect for a refined editorial feel
- **Google Fonts** — Playfair Display, DM Mono, and Jost loaded via CDN
- **Zero Dependencies** — no JavaScript libraries, no npm, no build step

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Name, tagline, credential badges, key stats (LinkedIn followers, CRM data, SEO results) |
| **About** | Personal summary, LinkedIn stats, open-to-work status |
| **Skills** | Three-panel grid: Technical, Interpersonal, and Soft Skills |
| **Experience** | Timeline of all roles: Youth Action Hub, Eat My News, Marquee Fellowship, Direction Educare, Younity.in |
| **Certifications** | Oracle OCI Data Science Professional + AI for ALL (Intel/MoE), with skill tags |
| **Education** | MCA at JIMS IPU + BSc Mathematics Hons at University of Delhi |
| **Awards & Volunteering** | SIH Certificate, Self-Defence Training, CRY, UNCTAD Youth Hub |
| **Activities & Interests** | Extracurricular roles and personal interests |
| **Contact** | Call-to-action with email link and LinkedIn profile link |

---

## 🎨 Design System

### Color Palette

| Variable | Hex | Usage |
|---|---|---|
| `--cream` | `#f5f0e8` | Background, cards |
| `--ink` | `#1a1208` | Text, dark sections |
| `--warm` | `#c8a96e` | Accents, highlights |
| `--rust` | `#b84c2b` | Primary accent, labels |
| `--muted` | `#8a7d6b` | Secondary text |

### Typography

| Font | Usage |
|---|---|
| **Playfair Display** | Headings, names, section titles |
| **DM Mono** | Labels, tags, navigation, metadata |
| **Jost** | Body text, descriptions |

---

## 🚀 Getting Started

### Option 1 — Open Directly
Just double-click `index.html` — it opens in your browser instantly.

### Option 2 — Local Server (recommended)
```bash
# Using Python
python -m http.server 8000

# Then visit:
http://localhost:8000
```

### Option 3 — Deploy Online (free)
- **GitHub Pages** — push to a repo, enable Pages in Settings
- **Netlify** — drag and drop the `index.html` file at netlify.com/drop
- **Vercel** — import the repo and deploy in one click

---

## ✏️ Customisation Guide

### Update Contact Email
Find this line in the Contact section and replace the placeholder:
```html
<a href="mailto:aastha@example.com" class="btn-light">
```
Replace `aastha@example.com` with your actual email address.

### Update LinkedIn URL
```html
<a href="https://www.linkedin.com/in/aastha-setia-3476b6255/" target="_blank" class="linkedin-link">
```

### Add a New Experience Entry
Copy the block below and paste it inside `.exp-timeline`:
```html
<div class="exp-item reveal">
  <div class="exp-meta">Month Year – Month Year · Location</div>
  <h3 class="exp-company">Company Name</h3>
  <div class="exp-role">Your Role Title</div>
  <ul class="exp-achievements">
    <li><strong>Achievement:</strong> Description here.</li>
  </ul>
</div>
```

### Add a New Certification
Copy the block below and paste it inside `.certs-grid`:
```html
<div class="cert-card reveal">
  <div class="cert-issuer">Issuing Organisation</div>
  <div class="cert-name">Full Certification Name</div>
  <div class="cert-date">Issued Mon YYYY</div>
  <div class="cert-skills">
    <span class="cert-skill-tag">Skill 1</span>
    <span class="cert-skill-tag">Skill 2</span>
  </div>
</div>
```

### Change Accent Color
Update `--rust` in the `:root` block to any hex color:
```css
:root {
  --rust: #b84c2b; /* change this */
}
```

---

## 📱 Browser Support

Works in all modern browsers:
- Chrome / Edge (Chromium) ✅
- Firefox ✅
- Safari ✅
- Mobile browsers (iOS Safari, Android Chrome) ✅

---

## 📄 Content Sources

Portfolio content was compiled from:
- Resume / CV (`.doc`)
- LinkedIn profile: [linkedin.com/in/aastha-setia-3476b6255](https://www.linkedin.com/in/aastha-setia-3476b6255/)

---

## 👩‍💻 Built For

**Aastha Setia**  
Research Intern · Data Science & Analytics · MCA Candidate  
📍 Ganganagar, Rajasthan, India  
🔗 [LinkedIn](https://www.linkedin.com/in/aastha-setia-3476b6255/)

---

*Built with HTML, CSS & vanilla JavaScript. No frameworks. No fuss.*
