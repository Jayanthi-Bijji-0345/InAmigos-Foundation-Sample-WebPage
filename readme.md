# InAmigos Foundation — Official Awareness Website
 
> **"Creating Change, Inspiring Hope"**
> A responsive, single-page awareness website built for [InAmigos Foundation](https://inamigosfoundation.org.in), a Section 8 non-profit based in Bilaspur, Chhattisgarh, working across education, women's empowerment, animal welfare, environmental care, and livelihood development.
 
---
 
## 🌐 Live Preview
 
Open `index.html` directly in any modern browser — no build step required.
 
---
 
## 📸 Screenshots
 
| Hero Section | Projects Grid | Impact Section |
|---|---|---|
| ![Hero](https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&q=70) | _Projects grid with 6 initiative cards_ | _Impact stats + visual layout_ |
 
---
 
## 🗂️ Project Structure
 
```
inamigos-foundation-website/
│
├── index.html          # Complete single-file website (HTML + CSS)
└── README.md           # Project documentation
```
 
All styles are embedded in `<style>` tags within `index.html`. No external CSS frameworks, no JavaScript dependencies, no build tools needed.
 
---
 
## ✨ Features
 
- **Sticky Navigation** — Frosted-glass navbar with smooth scroll links and a "Join Us" CTA
- **Hero Section** — Full-viewport banner with gradient overlay, headline, and dual action buttons
- **Stats Bar** — Floating card showcasing key impact numbers (50K+ meals, 30K+ interns, 20K+ saplings, etc.)
- **About Section** — Two-column layout with image, certification pills (Section 8, 80G, 12A, NITI Aayog, ISO 9001:2015)
- **Projects Grid** — Six responsive cards for SEVA, Bachpanshala, Udaan, Prakriti, Jeev, and Vikas
- **Impact Section** — Side-by-side layout with a structured bullet-point impact narrative
- **Gallery** — CSS Grid-based photo gallery with a spanning tall-card layout and hover zoom effect
- **Get Involved Banner** — Full-width CTA section with four action cards (Volunteer, Donate, Spread the Word, Partner)
- **Footer** — Brand info, quick links, social media links, and contact details
- **Responsive Design** — Mobile-first breakpoints at 768px; nav links hidden on mobile, grids collapse to single column
---
 
## 🎨 Design System
 
| Token | Value | Usage |
|---|---|---|
| `--green-dark` | `#0F6E56` | Primary brand color, nav, headings |
| `--green-mid` | `#1D9E75` | Hover states, accent dots |
| `--green-light` | `#E1F5EE` | Pill backgrounds, section tags |
| `--amber` | `#E8A020` | Primary CTA buttons |
| `--amber-light` | `#FDF3DC` | Card accents |
| `--text` | `#1A1A1A` | Body text |
| `--text-muted` | `#5A5A5A` | Secondary text |
| `--bg` | `#FAFAF8` | Page background |
 
**Typography:**
- Headings — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (serif, 400 / 700)
- Body — [DM Sans](https://fonts.google.com/specimen/DM+Sans) (sans-serif, 300 / 400 / 500 / 600)
Both loaded via Google Fonts CDN.
 
---
 
## 🚀 Getting Started
 
### Open Locally
 
```bash
git clone https://github.com/<your-username>/inamigos-foundation-website.git
cd inamigos-foundation-website
# Open index.html in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```
 
## 🏢 About InAmigos Foundation
 
| Detail | Info |
|---|---|
| **Founded** | September 23, 2020 |
| **Founder** | Mr. Govind Shukla |
| **Type** | Section 8 Non-Profit |
| **HQ** | Bilaspur, Chhattisgarh — 495555 |
| **Phone** | +91 626 730 9902 |
| **Email** | inamigosfoundation@gmail.com |
| **Website** | [inamigosfoundation.org.in](https://inamigosfoundation.org.in) |
 
### Six Core Projects
 
| Project | Focus Area |
|---|---|
| **SEVA** | Food & clothing distribution — 50,000+ beneficiaries |
| **Bachpanshala** | Education & digital literacy for underprivileged children |
| **Udaan** | Women's empowerment & vocational skill development |
| **Prakriti** | Environmental conservation — 20,000+ saplings planted |
| **Jeev** | Animal welfare — 50+ stray animals fed daily |
| **Vikas** | Internship & livelihood programs — 30,000+ interns trained |
 
---
 
## 🛠️ Technologies Used
 
- **HTML5** — Semantic structure
- **CSS3** — Custom properties (variables), CSS Grid, Flexbox, `clamp()`, `backdrop-filter`, `clip-path`, smooth scroll
- **Google Fonts** — Playfair Display, DM Sans
- **Unsplash / Foundation CDN** — Open-licensed imagery
No JavaScript. No frameworks. No package manager. Pure HTML + CSS.
 
---
 
## 📱 Responsive Breakpoints
 
| Breakpoint | Behavior |
|---|---|
| `> 768px` | Two-column grids for About and Impact; three-column gallery; horizontal nav |
| `≤ 768px` | Single-column layout; nav links hidden; gallery collapses to two columns; footer stacks vertically |
 
---
 
## 🤝 Contributing
 
This website is maintained as part of an internship project at InAmigos Foundation. Contributions, suggestions, and bug reports are welcome.
 
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add: description of change"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request
---
 
## 📄 License
 
This project is created for **InAmigos Foundation** — a registered non-profit. The code is open for reference and educational use. Please do not reuse branding, logos, or content without permission from the Foundation.
 
---
 
## 🙏 Acknowledgements
 
- **InAmigos Foundation** for their impactful social work across India
- [Unsplash](https://unsplash.com) for open-licensed photography
- [Google Fonts](https://fonts.google.com) for typography
---
 
*Built with 💚 by the InAmigos Web Team · Bilaspur, Chhattisgarh*
