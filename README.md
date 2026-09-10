# Senior Frontend Interview Prep

A comprehensive, three-page static website for preparing for Senior Frontend / UI Engineer interviews. Covers 189 Q&A topics, 35 deep-dive teaching concepts, flashcards, an interview simulator, and more — all in plain HTML with zero dependencies.

## Pages

### 1. Reference Guide (`interview-prep.html`)

189 questions with detailed answers, code examples, comparison tables, and interview tips.

| Section | Count | Topics |
|---|---|---|
| React | 10 | Virtual DOM, reconciliation, hooks, Context vs Redux, optimization |
| JavaScript | 20 | Closures, event loop, promises, prototypes, event delegation, async/await |
| TypeScript | 5 | Types vs interfaces, generics, union/intersection, typing React |
| Coding Challenges | 15 | Debounce, throttle, Promise.all, curry, flatten, memoization, component builds |
| CSS & HTML | 12 | Flexbox/Grid, specificity, positioning, responsive design, accessibility |
| Performance | 12 | Re-renders, React.memo, code splitting, lazy loading, virtualization |
| Frontend System Design | 15 | Dashboard, component library, micro-frontends, offline-first, i18n |
| Dashboard Deep Dive | 14 | RBAC, multi-tenant, caching, real-time updates, pagination |
| Advanced React | 7 | Fiber, Server Components, state management trade-offs, hydration |
| Web Fundamentals | 6 | CORS, SSR/SSG/CSR, browser rendering pipeline, reflow vs repaint |
| Advanced JavaScript | 5 | WeakMap/WeakSet, garbage collection, V8 engine, large datasets |
| Advanced TypeScript | 3 | Mapped types, conditional types, typing dynamic forms |
| Advanced CSS | 2 | CSS-in-JS trade-offs, legacy frontend improvement |
| Authentication | 6 | Cookies vs sessions, JWT, protected routes, auth vs authz |
| State Management | 7 | Context API, Redux Toolkit, Context vs Redux, decision framework |
| React Perf Mastery | 7 | Diagnosing re-renders, React.memo pitfalls, state colocation |
| Production Debugging | 5 | Memory leaks, slow APIs, error boundaries, senior debugging framework |
| Next.js Deep Dive | 3 | Next.js vs React, App Router, ISR rendering strategies |
| Senior Architecture | 5 | Separation of concerns, feature-based architecture, URL state |
| Process & Strategy | 6 | Feature lifecycle, tech debt, performance budgets, testing strategy |
| Interview Frameworks | 3 | Quick-fire answers cheat sheet |
| Core Web Vitals | 4 | LCP, CLS, INP vs FID, production monitoring setup |
| SEO for React | 4 | SPA SEO, SSR vs pre-rendering, Open Graph/meta tags, common pitfalls |
| SCSS & CSS Preprocessors | 2 | SCSS features, 7-1 folder structure with BEM |
| CI/CD & DevOps | 3 | Pipeline setup, quality gates, environment builds & feature flags |
| Git & Collaboration | 2 | Branching strategies, effective code reviews |
| Agile & Estimation | 2 | Vertical slicing & estimation, balancing features vs tech debt |
| Enterprise B2C | 3 | A/B testing, analytics & performance, white-label architecture |
| REST API Patterns | 2 | Robust API layer design, API versioning & adapter pattern |

### 2. Tutor Mode (`tutor-mode.html`)

35 concepts taught through an 8-step teaching flow per concept:

1. Intuition — build mental model with analogy
2. Deep Dive — technical details with code
3. Pattern — when and how to apply
4. Story — real-world scenario
5. Recap — key points summary
6. Questions — test understanding
7. Curveballs — tricky interview follow-ups
8. Flashcards — quick recall cards

**Phases covered:**
- Phase 1: JavaScript Internals (10 concepts)
- Phase 2: React Internals (8 concepts)
- Phase 3: Design Patterns (9 concepts)
- Phase 4: System Design (8 concepts)

### 3. Practice Mode (`interview-game.html`)

Four interactive practice modes:

- **Flashcards** — 83 cards across 13 categories, flip to reveal answers
- **Interview Simulator** — Timed 2-minute sessions, 10 random questions per round
- **Story Bank** — 12 STAR-format behavioral stories (performance, architecture, conflict, debugging, leadership, process)
- **Depth Drill** — 27 drill chains, each with a base question + 2 progressively harder follow-ups

## Getting Started

No build step, no dependencies. Just open any HTML file in a browser:

```bash
# Clone and open
open interview-prep.html

# Or serve locally
npx serve .
# Then visit http://localhost:3000
```

## Features

- **Dark/Light mode** — Respects system preference, manual toggle available
- **Sidebar navigation** — Jump to any section instantly
- **Expand/Collapse all** — Quickly scan or deep-read
- **Responsive** — Works on desktop, tablet, and mobile
- **Offline-ready** — Static HTML, works without internet after first load
- **Print-friendly** — Clean output when printed or saved as PDF

## Target Role

Designed for **Senior Frontend / UI Engineer** interviews at product companies, covering:

- React.js, TypeScript, JavaScript (ES6+)
- HTML5, CSS3, SCSS, responsive & mobile-first design
- State management (Redux, Redux Toolkit, Context API, Zustand)
- Core Web Vitals & web performance optimization
- SEO, lazy loading, code splitting, SSR/SSG/ISR
- REST API consumption patterns
- CI/CD pipelines, Git workflows, Agile practices
- Enterprise B2C patterns (A/B testing, analytics, white-labeling)
- System design, architecture, and technical leadership

## Content Stats

| Metric | Count |
|---|---|
| Reference Q&A | 189 |
| Tutor concepts | 35 |
| Flashcards | 83 |
| Behavioral stories | 12 |
| Depth drill chains | 27 |
| **Total unique topics** | **300+** |

## License

This project is licensed under **CC BY-NC 4.0** ([Creative Commons Attribution-NonCommercial](https://creativecommons.org/licenses/by-nc/4.0/)).

- You **can** share, fork, and adapt it
- You **must** give credit to [Veeresh Kawalgi](https://github.com/veereshkawalgi) and link back to this repo
- You **cannot** use it commercially (no selling, paywalling, or monetizing)

See [LICENSE](./LICENSE) for full terms.

Copyright (c) 2024-2026 Veeresh Kawalgi.
