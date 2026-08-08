# NEXUS CECT Orientation

**Interactive New-Hire Training Experience for Hood Boss QA**

A production-grade, single-file interactive training module for CECT Documentation & Photo Standards. Built as a real working tool for field crews and as a portfolio demonstration of systems thinking + clean frontend engineering.

---

### Live Demo

Open `index.html` directly in any modern browser, or deploy to GitHub Pages / any static host.

---

### What This Is

A complete 15-slide interactive orientation deck covering:

- Why documentation standards matter (certification, liability, client trust)
- MyTechPix / Hood Boss portal workflow and color-code system (Blue / Green / Red)
- Before-work Blue Set protocol (required shots + narrative tags)
- Timestamp, metadata, and GPS discipline
- During-work interval rules and deficiency capture
- Red-outline deficiency protocol
- After-work Green Set mirroring
- Publish Gate final checklist
- Common failure modes that get flagged
- 30-second self-audit habit
- Session logging, QA feedback loops, and continuing education (CEUs)

Interactive features:

- Sidebar navigation with completion tracking
- Live protocol visualizer (Canvas) that changes color by stage
- Toggleable checklists
- Session timer
- Random knowledge-check quizzes
- Keyboard navigation (← → Space)
- Fully responsive (mobile + desktop)

---

### Tech Stack

- Vanilla HTML / CSS / JavaScript (zero build step)
- Tailwind CSS (CDN)
- Canvas 2D for the live protocol visualizer
- Inter + JetBrains Mono
- Strict NEXUS aesthetic: `#00ff87` · `#60efff` · `#ff0080` · `#ffcc00`

No frameworks. No dependencies beyond the CDN. Opens offline after first load of fonts/Tailwind.

---

### Why It Exists

Field technicians need non-negotiable documentation standards that protect the tech, the company, and the client. This module turns the policy deck into something people can actually practice and internalize — not just sit through.

It also serves as a portfolio piece showing:

- Ability to take real operational requirements and turn them into clean interactive systems
- Attention to both UX and domain accuracy
- Real Canvas work and state management without frameworks
- Production mindset (keyboard support, progress tracking, mobile readiness)

---

### Quick Start

```bash
# Clone
git clone https://github.com/AntManThePro/nexus-cect-orientation.git
cd nexus-cect-orientation

# Open locally
open index.html
# or
npx serve .
```

### Deploy to GitHub Pages

1. Push this repo
2. Settings → Pages → Source: Deploy from a branch → `main` / root
3. Your live URL will be: `https://antmanthepro.github.io/nexus-cect-orientation/`

---

### Project Structure

```
nexus-cect-orientation/
├── index.html          # Complete self-contained experience
├── README.md
├── LICENSE
└── .gitignore
```

---

### Author

**DoubleA / AntManThePro**  
Field Operations & QA · Building systems that make work clearer and measurable  
[github.com/AntManThePro](https://github.com/AntManThePro)

---

### License

MIT — free to use, adapt, and deploy for training or portfolio purposes.
