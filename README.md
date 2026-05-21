<div align="center">

# NurseCloze

### Lecture slides to flashcards in 60 seconds

AI-powered study tool that turns your professor's lecture slides into active recall flashcards — not generic textbook content.

[![nursecloze.com](https://img.shields.io/badge/nursecloze.com-Visit%20Site-blue)](https://nursecloze.com)
[![Free Lab Values Deck](https://img.shields.io/badge/Free-Lab%20Values%20Deck-green)](https://nursecloze.com/blog/nursing-lab-values-anki-deck)

</div>

---

## What it does

Nursing students spend 30+ minutes after every lecture manually creating flashcards. Most stop after a few weeks because the workflow is too slow. They fall back to re-reading slides and highlighting — which feels productive but doesn't build recall.

NurseCloze automates the part that wastes time. Upload a PDF or text file of your lecture slides. The AI extracts every testable concept, generates one-concept-per-card flashcards with source tracking back to the exact slide, and exports to spaced repetition apps.

One upload. Under 60 seconds. Every concept covered.

## How it works

1. **Upload your slides** — PDF or TXT from any lecture
2. **AI generates cards** — one concept per card, cloze-deletion format, source-tracked to the originating slide
3. **Preview and edit** — review every card before you commit
4. **Export and study** — one-click download, import into any spaced repetition app

## Tech stack

| Layer | Stack |
|---|---|
| Frontend (app) | SvelteKit, TypeScript, Tailwind CSS v4 |
| Marketing site | SvelteKit (static), mdsvex, Tailwind CSS v4 |
| Backend | Go, Gin REST API |
| Shared UI | Svelte component library (`@nursecloze/ui`) |
| Auth | Firebase Authentication |
| Payments | Stripe |
| Analytics | PostHog |
| Infrastructure | Cloudflare, SvelteKit adapter-static |

## Repository structure

```
packages/
├── frontend/          SvelteKit app — the product (app.nursecloze.com)
├── marketing/         SvelteKit static site — marketing + blog (nursecloze.com)
├── go-backend/        Go + Gin REST API (api.nursecloze.com)
└── ui/                Shared Svelte UI components
```

## Free resources

No signup required:

- [Nursing Lab Values Flashcard Deck](https://nursecloze.com/blog/nursing-lab-values-anki-deck) — 62 cards covering CBC, CMP, ABGs, coagulation, lipids, and HbA1c. Aligned to OpenStax Fundamentals of Nursing.

## For students

- [Get Started Free](https://nursecloze.com) — 7-day trial, no credit card required
- [Pricing](https://nursecloze.com/pricing) — $8.99/mo or $59.99/yr
- [Blog](https://nursecloze.com/blog) — study methods, course-specific guides

## License

All rights reserved. The source code in this organization is not available for public use, modification, or distribution unless explicitly stated otherwise in a repository's license file.

<div align="center">

Built for nursing students carrying 4+ lecture-heavy courses per semester.

</div>
