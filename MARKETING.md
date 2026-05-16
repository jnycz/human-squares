# Human Squares — Marketing & Brand Playbook

> **One pen. One square. One mind. Infinite expression.**

---

## 1. The One-Liner

**Human Squares is a global creative network where people draw freely on a single square — and the world votes, analyzes, and celebrates what comes out.**

## 2. The 30-Second Pitch

Most "art apps" are filters. We're the opposite. Human Squares ships you a stack of premium square pads and a Sharpie — at cost — then gives you a beautifully fast, AI-powered platform to upload your drawings, get them analyzed, ranked, and voted on by a worldwide community of creators. No subscriptions. No filters. No algorithms predicting what you should draw next. Just you, a square, and a pen. We believe the smallest format produces the most honest art — and we built the cleanest, fastest, most modern way in the world to share it.

## 3. Brand Pillars

| Pillar | What It Means |
|---|---|
| **Honesty** | One pen, one color, one square. No undo. No filters. Pure intent. |
| **Accessibility** | Kit shipped at cost. Free to upload. No paywalls on creativity. |
| **Intelligence** | AI doesn't generate the art — it *understands* it. Analysis, not creation. |
| **Community** | Up votes, down votes, curated sets, daily features. The crowd decides. |
| **Performance** | Sub-second uploads. Zero bloat. Cutting-edge tech, invisible to the user. |

## 4. Tagline Variants (Use Across Channels)

- **One Square. Infinite Souls.**
- **Draw it. Ship it. The world decides.**
- **The smallest canvas. The biggest signal.**
- **Honest art lives in a square.**
- **Pen. Paper. People. Proof.**
- **What can you say in a square?**

## 5. Voice & Tone

- **Confident, not loud.** We don't shout features. We let the work speak.
- **Minimal, never cold.** We use whitespace like we mean it.
- **Human, never corporate.** Real artists. Real squares. Real names.
- **Earned, not hype.** No "revolutionize", no "disrupt". The product proves itself.

## 6. Visual Identity Direction

- **Logo:** A single black square. Sometimes outlined, sometimes filled. That's the wordmark.
- **Type:** Editorial serif (think GT Sectra / Tiempos) for headlines. Geometric mono (Berkeley Mono / JetBrains Mono) for UI.
- **Color:** Off-white paper (`#F8F6F1`). Sharpie black (`#0A0A0A`). One accent — electric red (`#FF2D2D`) used sparingly for CTAs and live states.
- **Motion:** Squares snap. They don't fade. Hard edges, hard timing, no easing soup.
- **Photography:** Hands. Ink. Imperfection. Always shot on real paper, never composited.

## 7. Target Audiences

1. **The Pen Tribe** — illustrators, tattoo artists, graphic designers, doodlers, journalers.
2. **The Curious Creators** — non-artists who want a tactile, low-stakes outlet.
3. **The AI-Curious** — people fascinated by how machines interpret human expression.
4. **Collectors & Curators** — people who want to spot, vote, and follow rising voices.
5. **Educators & Therapists** — the square as a mindfulness, classroom, or therapeutic tool.

---

## 8. SEO Strategy

### 8.1 Primary Keyword Targets

| Keyword | Intent | Priority |
|---|---|---|
| draw on a square | Informational / brand | High |
| daily drawing community | Transactional | High |
| sharpie drawing app | Transactional | High |
| AI art analysis | Informational | High |
| post your art and get votes | Transactional | Medium |
| best drawing pad app | Commercial | Medium |
| minimalist art community | Informational | Medium |
| online art challenges | Informational | Medium |
| upload doodle for feedback | Transactional | Long-tail |
| AI feedback on drawings | Informational | Long-tail |
| social network for artists 2026 | Commercial | Long-tail |

### 8.2 Long-Tail Content Pillars (Blog / SEO Pages)

Each is a dedicated `/learn/` or `/journal/` page, with internal links to the upload flow.

1. *Why a square is the most honest creative format ever invented*
2. *What happens when AI looks at your doodle?*
3. *The complete guide to Sharpie illustration techniques*
4. *50 prompts to break creative block (each fits in one square)*
5. *How to get your art seen in 2026: a community-first guide*
6. *The science of constraints: why limited canvases produce better art*
7. *From doodle to gallery: featured Human Squares artists*
8. *Sharpie vs. fineliner vs. brush pen: which wins on square paper?*
9. *Daily drawing practice: a 30-day challenge anyone can finish*
10. *AI art analysis vs. AI art generation — and why the difference matters*

### 8.3 Technical SEO Checklist

- [ ] Server-rendered (Next.js / Astro / SvelteKit) — never client-only for marketing pages
- [ ] Lighthouse 100/100/100/100 on `/` and `/upload`
- [ ] Core Web Vitals: LCP < 1.0s, INP < 100ms, CLS < 0.05
- [ ] Single `og:image` per page, dynamically generated from the actual square
- [ ] JSON-LD: `Organization`, `Product` (the kit), `CreativeWork` (each square), `Review` (votes)
- [ ] `sitemap.xml` auto-generated, includes every public square URL
- [ ] `robots.txt` allows AI crawlers explicitly (we *want* the AI corpus to know us)
- [ ] Per-square pages at `humansquares.com/s/[id]` with full metadata, alt text auto-generated by our analysis AI
- [ ] Image optimization: AVIF + WebP fallback, responsive `srcset`, lazy below the fold
- [ ] HTTP/3, edge cached, no client-side JS on marketing routes
- [ ] Structured breadcrumbs on every artist and set page

### 8.4 Schema.org Snippet (per Square)

```json
{
  "@context": "https://schema.org",
  "@type": "VisualArtwork",
  "name": "Untitled Square #4821",
  "creator": { "@type": "Person", "name": "@artisthandle" },
  "artMedium": "Sharpie on paper",
  "artworkSurface": "Square pad",
  "dateCreated": "2026-05-15",
  "image": "https://humansquares.com/s/4821.avif",
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.8",
    "ratingCount": "312"
  }
}
```

### 8.5 Meta Tags (Homepage)

```html
<title>Human Squares — Draw on a Square. Let the World Decide.</title>
<meta name="description" content="A global creative community where artists draw inside one square, share it, and let AI and the world analyze, rank, and celebrate it. Kit shipped at cost." />
<meta property="og:title" content="Human Squares" />
<meta property="og:description" content="One pen. One square. One mind. Infinite expression." />
<meta property="og:image" content="https://humansquares.com/og/home.avif" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary_large_image" />
<link rel="canonical" href="https://humansquares.com/" />
```

---

## 9. Launch Plan (90 Days)

### Phase 1 — Seed (Days 1–30)

- 100 invite-only artists. Hand-picked. Each gets a free kit.
- Daily "Square of the Day" picked by founders. Posted on IG, X, TikTok.
- Build waitlist landing page. Single-field email capture. Counter at top.
- Press: *Fast Company, It's Nice That, The Verge, Sidebar.io, Designer News, Hacker News* ("Show HN: Human Squares").

### Phase 2 — Open (Days 31–60)

- Public launch. Kit goes on sale at cost.
- Launch the AI analysis feature. Every upload gets a free read.
- Daily themed prompts ("Draw silence", "Draw your last lie", "Draw 4am").
- First **Square Set** competition: 9 squares, one theme, community votes the winners.
- Partner with 3 art schools for a "100 Squares" student showcase.

### Phase 3 — Compound (Days 61–90)

- Open API for the AI analysis layer (free tier).
- Launch artist profiles with vote-weighted reputation.
- Announce **Square of the Year**. Cash prize, gallery show, kit named after them.
- Begin SEO content engine: 2 long-form articles/week, all internally linked.

---

## 10. Channel Playbook

| Channel | Format | Cadence | Goal |
|---|---|---|---|
| Instagram | Single square + creator quote | Daily | Brand discovery |
| TikTok | Time-lapse of a square being drawn | 3×/week | Viral reach |
| X/Twitter | "Today's top square" + commentary | Daily | Community pulse |
| YouTube | "Square Stories" — 4-min artist mini-docs | Weekly | Depth & SEO |
| Pinterest | Square boards by theme | Bulk | Long-tail SEO |
| Newsletter | "The Weekly Square" — top 9 + AI insight | Sundays | Retention |
| Reddit | r/art, r/sketch, r/AskArtists (organic, never spam) | Ongoing | Trust |
| HN / PH | Launch posts, milestone posts | Quarterly | Tech audience |

---

## 11. Sample Marketing Copy

### Homepage Hero

> # Draw on a square. The world will respond.
>
> Human Squares is the simplest, fastest, most honest way to share your art. One pen. One square. AI that reads it. A community that votes on it. A pad and a Sharpie shipped to your door at cost.
>
> **[ Get the kit → ]   [ Upload a square → ]**

### Product Page (The Kit)

> ## The Square Kit. Shipped at cost.
>
> 50 premium square pads. One black Sharpie. Zero markup. We don't make money on the kit — we make it because the kit makes the work better.
>
> - Heavy 200gsm bleed-resistant paper
> - True square (5" × 5") — no rectangles allowed
> - Recyclable kraft sleeve
> - Ships flat in 48 hours
>
> **$ at-cost · Free shipping over $25 · No subscriptions, ever.**

### Email Capture

> ### Be one of the first 1,000 squares.
>
> The kit drops in 14 days. The first 1,000 sign-ups get free shipping forever and a numbered Founders Square.
>
> [ your@email.com ]   [ Reserve my square → ]

### Instagram Caption Template

> Square #[N] · @[handle]
>
> ↑ [up votes] votes · 🧠 AI says: "[one-line analysis]"
>
> What does it say to you?
>
> #HumanSquares #DailyDrawing #SharpieArt #MinimalArt #DrawDaily

### Press Boilerplate

> **About Human Squares**
> Human Squares is a creative platform and physical kit company built on a single idea: the most honest art happens inside a small, hard constraint. Founded in 2026, the company ships drawing kits at cost and operates a community where every uploaded square is read by AI, voted on by the public, and added to a growing global archive of human expression. Learn more at humansquares.com.

---

## 12. Founding Principles (Anti-Roadmap)

We will **never**:

- Add filters, brushes, or in-app drawing tools. The pen is the pen.
- Run banner ads or sell user data.
- Use AI to *generate* art. Only to *understand* it.
- Charge a subscription for uploading.
- Allow rectangular uploads. It's called Human Squares.

We will **always**:

- Ship the kit at cost.
- Pay featured artists. Real money. Every time.
- Open-source the AI analysis prompts and weights.
- Credit every artist on every share. Forever.

---

*Marketing v0.1 — drafted for the founder. Iterate freely.*
