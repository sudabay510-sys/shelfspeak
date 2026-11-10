# ShelfSpeak — Brand identity

**Slug:** `shelfspeak`  
**Tagline:** A 30-day content calendar built for your shop — not a generic template.  
**Local port:** `5101`  
**Status:** Live. Payments processed by Gumroad (Monthly or Quarterly).

## Audience persona
Owners and managers of salons, cafes, clinics, contractors, and shops who know they “should post” but stall on what to say.

Primary personas:
- **Solo shop owner:** You wear every hat and need a week’s posts in one sitting.
- **Front-desk marketer:** You can publish — you just need angles that match the brand voice.
- **Multi-location lead:** You want a repeatable cadence staff can follow.

## Voice & tone
- Clear, encouraging, specific — never hype or fear.
- Honest about limits (No follower, viral, or booking guarantees — just a clear posting plan.).
- Short sentences on landing; checklist language in plans.

## Color palette
Defined in `static/brand.css` (`:root` variables). Accent drives CTAs; background stays calm for long reading.

## Fonts (Google Fonts)
Linked via `https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@…` in templates.

## Logo
`static/logo.svg` — simple wordmark-friendly monogram on rounded square. Use on white/light headers; keep clear space ≈ 0.25× logo height.

## Iconography / illustration
Prefer flat geometric icons, soft corners matching `--radius`, no stock-photo people with fake quotes. Plan peeks use list + accent dots.

## Sample copy lines
- Hero CTA: “Build my content calendar”
- Honesty: “No follower, viral, or booking guarantees — just a clear posting plan.”
- Paywall: “Start my plan” links to the Gumroad checkout URL.

## Do
- Show Monthly and Quarterly prices, plus the renewal sentence, before checkout.
- Save the customer’s email before sending them to Gumroad.
- Keep disclaimers visible near plans.
- Mobile-first quiz (one question per screen).

## Don’t
- Fake testimonials, stats, or press logos.
- Guarantee results (income, rankings, behavior, bookings).
- Fake urgency (“only 2 spots left”).
- Auto-edit third-party listings (SignMatch) or promise AI magic without saying plans are rule-based in this prototype.

## Explicit palette (hex)

| Token | Hex |
|-------|-----|
| Background | `#F7F1E8` |
| Alt background | `#EFE6D8` |
| Card | `#FFFBF5` |
| Ink | `#2A2118` |
| Muted | `#6B5B4B` |
| Accent | `#C45C26` |
| Accent hover | `#A3481B` |
| On-accent | `#FFF8F1` |

**Display font:** Fraunces  
**Body font:** Source Sans 3

## Logo file
`static/logo.svg`
