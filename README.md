# AmbaZ: Homepage Redesign Concept

Animated redesign of the homepage of [ambaz.fr](https://www.ambaz.fr/), the real-estate asset management SaaS developed by **GESCEM**, produced during my 2026 internship there.

**Live page:** https://alaaeddinethr.github.io/ambaz/

## Brief

Modernise the site with motion design while keeping the AmbaZ brand identity (purple and orange, existing logo), and keep it credible for the target audience: property managers and facility directors of public and private organisations.

## What the page contains

- Hero with the value proposition, then the problem, the platform, the modules and the onboarding support
- Data security commitments, client references, resources and FAQ, demo request form
- Scroll-triggered animations (`IntersectionObserver`), pointer-reactive visuals, accessible skip link and keyboard navigation

## Technical choices

- One self-contained `index.html`: no build step, no external dependency, deployable on any static host
- Animations run on CSS transforms and opacity only, so they stay smooth on modest hardware
- The demo form is a front-end mock-up: it is not connected to GESCEM's CRM

---

Concept work for GESCEM, published with their agreement. Brand, logo and product content belong to GESCEM.
Built by Alaa Eddine Tahir · [LinkedIn](https://linkedin.com/in/alaaeddine-tahir)
