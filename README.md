# neo-brutalism

A complete neo-brutalist website demonstrating historical research, contemporary design principles, and human-AI collaboration.

## 🔗 Live Site
**https://wg99nj.github.io/neo-brutalism/**

## 📊 Performance Metrics (Lighthouse)
- ✅ **Performance:** 100/100
- ✅ **Accessibility:** 92/100
- ✅ **Best Practices:** 100/100
- ✅ **SEO:** 100/100

## 📁 Project Structure
```
neo-brutalism/
├── index.html              # Main history page
├── collaboration.html      # Human-AI partnership story
├── contact.html           # Contact form page
├── css/
│   └── styles.css         # Complete design system
├── docs/
│   ├── README.md          # Documentation index
│   └── process.md         # Complete process notes
└── research/
    └── sources.md         # 20 curated sources with URLs
```

## 🎨 What This Project Demonstrates

This website is both **about** neo-brutalism and **built with** neo-brutalist principles, creating a cohesive demonstration of the style's philosophy and application.

---

## Overview

This document collects research and practical guidance about "neo‑brutalism" — a contemporary, digital adaptation of the architectural New Brutalism movement — and how to apply its principles when building a standout portfolio site.

Use cases: creative portfolios, agency landing pages, experimental art/music sites, or any work that benefits from a bold, confrontational presentation.

## Historical context

- Origins: New Brutalism emerged in the 1950s–1970s in architecture as a reaction to ornamentation and as an expression of structural honesty (often associated with reinforced concrete, raw materials, and visible systems).
- Key ideas: material honesty, functional expression, repetitive modular forms, and large-scale, monumental gestures.
- Digital revival: From the 2010s onward, designers adapted those principles to web and graphic interfaces — translating raw materials into stark typography, visible layout skeletons, and intentionally 'unfinished' UI.

## Common visual & interaction characteristics

- Minimal ornamentation; emphasis on structure and layout
- Strong, often monochrome or limited palettes with one accent color
- System or neutral fonts (no heavy custom typefaces) and large, unapologetic typography
- Exposed UI chrome (visible borders, default scrollbars, raw form elements)
- Grid-first layouts, asymmetry, and unapologetic white/negative space
- Minimal or no drop shadows and no softening effects
- High-contrast states and bold CTAs
- Small, restrained animations or immediate hover states rather than refined, fluid transitions

## How neo‑brutalism is commonly used in portfolios

- To create a strong personal brand voice: the aesthetic communicates confidence and an anti‑design stance.
- To emphasize work over decoration: the raw presentation foregrounds content and craftsmanship.
- To target niche audiences (experimental art, underground fashion, creative technology) where striking visuals are valued.

But: the style can be harsh or alienating for broad, corporate, or accessibility‑sensitive audiences if applied without care.

## Practical guide: using neo‑brutalism for a portfolio

Contract (what the portfolio should do):
- Inputs: projects (images, descriptions, links, case studies), personal profile, contact details, optional demos.
- Outputs: a fast, distinctive site that surfaces your best work and encourages contact or hiring.
- Success criteria: clear hierarchy, fast load times, discoverability (SEO), accessible navigation, and distinct visual voice.

Design tokens & palette (starter):
- Primary palette: Black (#000) / White (#FFF)
- Accent: vivid color (e.g., Electric Cyan #00E5FF or Safety Orange #FF6A00) used sparingly
- Borders: 1–2px solid, high contrast (often black/white)
- Type: System stack (Inter/fallbacks or system fonts); headings large and bold; body text 16–18px for readability

Component rules & layout ideas:
- Hero: oversized project title, small subheading, large call-to-action; deliberate empty space.
- Project grid: cards with visible borders, minimal overlay, quick link to case study.
- Case study template: problem → approach → deliverables → visuals (raw screenshots, code snippets), with an optional short video or interactive demo.
- Navigation: simple top bar (left: name/logo, right: links) or vertical left rail; visible focus states and keyboard shortcuts for power users.

Accessibility checklist (non‑negotiable):
- Maintain adequate color contrast for body text and interactive elements.
- Ensure keyboard navigation and visible focus outlines (don't hide default outlines without replacing them).
- Use semantic HTML and ARIA where needed (landmarks, roles for complex widgets).
- Provide alt text for images and transcripts/captions for multimedia.
- Avoid relying on color alone to convey meaning.

Performance & progressive enhancement:
- Favor static rendering (HTML/CSS) where possible; lazy‑load large images and use optimized formats (WebP/AVIF).
- Keep JavaScript minimal; use JS for enhancement only (e.g., interactive demos, filtered project lists).

SEO & content strategy:
- Make sure each project has its own page with descriptive headings, meta tags, and crawlable content.
- Use readable URLs (/projects/awesome-site) and structured data for portfolio entries if applicable.

## Technology & workflow suggestions

- Starter approaches:
	- Plain static HTML & CSS (fastest, easiest to control aesthetic)
	- Static site generator (Eleventy, Hugo, Astro) for content scalability
	- React/Next.js or SvelteKit if you want client interactivity and SSR
- CSS approach: small, explicit component CSS or utility classes; central CSS variables for tokens; avoid heavy frameworks that fight the raw aesthetic.
- Hosting: Vercel, Netlify, or static hosts for fast deploys and previews.

## Example folder structure (simple static site)

- /index.html
- /projects/
	- /projects/project-1.html
- /styles/
	- main.css
- /assets/

## Edge cases and tradeoffs

- Readability vs. expression: large display typography can hinder scanning; balance headline scale with readable body sizes.
- Accessibility vs. strict aesthetic: visible focus states and clear controls may soften the 'raw' look — treat accessibility as a design constraint, not a compromise.
- Branding vs. versatility: a strongly brutalist portfolio can polarize; consider a neutral resume/CV mode for client-facing contexts.

## Next steps and recommendations

1. If you want, I can scaffold a minimal starter (plain HTML/CSS or an Eleventy site) in this repo showing:
	 - a hero, project grid, and one case study page styled in a neo‑brutalist manner
	 - responsive behavior and accessibility checks
2. I can also gather 6–10 reference portfolio examples and annotate what works/doesn't work in each.

Tell me which of the following you'd like next: a starter scaffold (and which stack), a curated example set, or a compact style guide (CSS tokens + components) to include in the repo.

## Further reading & resources

- New Brutalism / Brutalist architecture (encyclopedias and architecture histories)
- [Brutalist Websites](https://brutalistwebsites.com) - The definitive directory
- [Brutalist Web Design Manifesto](https://brutalist-web.design) - Design philosophy
- Design commentary on neo‑brutalism from industry blogs and design publications (Smashing Magazine, Awwwards, 99designs, etc.)

---

## 🤝 Project Credits

**Built through Human-AI Collaboration:**
- **Human (wg99nj):** Creative vision, design direction, quality assessment, user experience insights
- **AI (GitHub Copilot):** Code implementation, research synthesis, documentation, technical architecture

**Timeline:** November 8-9, 2025  
**Repository:** [github.com/wg99nj/neo-brutalism](https://github.com/wg99nj/neo-brutalism)  
**License:** Open for learning and educational use

---

## 🚀 Key Achievements

1. **Perfect Performance:** 100/100 Lighthouse score with zero dependencies
2. **Accessible Design:** 92/100 accessibility with WCAG AA compliance
3. **Responsive Excellence:** 3 breakpoints (desktop/tablet/mobile) with touch-friendly targets
4. **Comprehensive Research:** 20 curated sources with clickable URLs
5. **Transparent Process:** Full documentation of human-AI collaboration

Visit [collaboration.html](https://wg99nj.github.io/neo-brutalism/collaboration.html) to see the full story of how this project was built.

--
Append or edit this file as you like; if you want I can commit a starter template next.

