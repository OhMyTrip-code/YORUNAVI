# YORUNAVI — Project Context

## What is YORUNAVI?
A premium English-language portal for foreigner-friendly adult entertainment venues in Tokyo.
Tagline: "Your Pleasure, Guaranteed."
Value: Every venue listed welcomes foreign visitors. No guesswork, no rejection.

## Tech Stack
- Framework: Astro 5 + React Islands (interactive parts only)
- Styling: Tailwind CSS 4
- Language: TypeScript
- Deploy: Vercel
- Fonts: Cormorant Garamond (headings) + DM Sans (body) via Google Fonts
- Data: Static JSON files in src/data/ (no backend for MVP)

## Design Tone
Premium dark × gold. Think: VIP lounge at an exclusive club.
Sexy but not vulgar. Immediately clear it's an adult site, but classy.
The polar opposite of cluttered Japanese fuzoku sites.

References: Pornhub Premium's dark+gold UI polish × high-end escort site elegance × luxury lingerie brand visuals.

Keywords: Seductive, Premium, Intimate, Exclusive

## Color Palette
- bg-primary: #0a0a0a
- bg-card: #1a1a1a
- bg-card-hover: #222222
- gold: #c9a84c
- gold-light: #e4cb78
- gold-dim: rgba(201,168,76,0.15)
- accent-rose: #8b2252
- accent-rose-dim: rgba(139,34,82,0.15)
- text-primary: #f0ece4
- text-secondary: #9a958c
- text-muted: #6a655d
- border: rgba(201,168,76,0.12)

## Site Structure (4 Pillars)
1. Girls & Shops (/shops/) — Browse venues and girls
2. Threads (/threads/) — Community forum
3. Blog (/blog/) — Guides and articles
4. Reviews (/reviews/) — User reviews

## 6 Categories
1. Delivery Health (デリヘル) — Outcall to hotel
2. Soapland (ソープ) — Incall bathhouse
3. Fashion Health (ヘルス) — Incall shop
4. Hotel Health (ホテヘル) — Semi-outcall designated hotel
5. Fuzoku Esthetic (風俗エステ) — Incall sensual salon
6. Men's Esthetic (メンズエステ) — Incall relaxation massage

## Key Rules
- ALL text in English (site targets foreign visitors)
- NO booking functionality — information only, users contact shops directly
- 18+ age gate on first visit
- Mobile-first responsive design
- Data stored as static JSON in src/data/ for MVP
- React Islands only for interactive components (filters, modals, forms)
