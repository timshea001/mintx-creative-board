# Mint-X Organic Board v4 (2026-08-31)

19 organic post concepts, 1080x1350 (4:5), built on design system v1.1 (see `../../design-system/DESIGN-SYSTEM.md`, v1.1 addendum). Each concept runs a proven social format from the Foreplay experts swipefile inside the brand's visual lanes.

| File | Concept | Format | Pillar |
|---|---|---|---|
| p01_search_bar | Search Bar | Google-search / autocomplete | 4 Simple Switch |
| p02_text_thread | The Group Chat | Text-message thread | 1 Morning After |
| p03_crossout_rats | Rats Are Optional | Cross-out reframe | 3 Urban Rat |
| p04_tick_list | The Whole Resume | Tick list | 4 Simple Switch |
| p05_yes_no | Goodbye / Hello | Say goodbye / say hello | 4 Simple Switch |
| p06_ratings | 4.7 Stars | Ratings proof (real Amazon rating) | Credibility |
| p07_comparison | Spray vs Built-In | Comparison two-column | 2 Mechanism |
| p08_big_stat | 3 Million Rats | Big stat | 3 Urban Rat |
| p09_wanted_poster | Wanted Poster | Wanted-poster device | 1 Morning After |
| p10_comment_mint | Comment MINT | Comment-to-DM | Engagement |
| p11_retail_wall | Retail Wall | Retail availability | Lower funnel |
| p12_night_overlay | Porch Light | Text overlay on Lane A photo | 1 / brand |
| p13_before_after | Last Week / This Week | Before-after split | 1 Morning After |
| p14_built_in | Built In | Science static | 2 Mechanism |
| p15_epa_only | The Only One | EPA proof | Credibility |
| p16_cartoon_evicted | Evicted | Retro cartoon (Lane B, AI) | 1 Morning After |
| p17_cartoon_nope | Nope. | Retro cartoon (Lane B, AI) | 2 Mechanism |
| p18_ugc_switch | The Switch | UGC still (Lane C, AI base + overlay) | 1 / pet-safe |
| p19_family_usa | One Family | Founder story | Credibility |

- Board page: `index.html` (same file as `ads.html`) — phone mockups with IG/FB toggle on top, full-size render sheet below.
- Re-render: `python3 -m http.server 8471` in this folder, open `ads.html` via Playwright, `await document.fonts.ready`, screenshot each `.ad` element by id into `out/`, then `sips -c 1350 1080`.
- AI bases: `out/_p16/17/18_base.png` with sidecar prompt JSONs. AI spend this build: ~$0.38.
- Claims used are from the approved list (EPA-registered, patented, non-toxic, repels rats/mice/raccoons/squirrels, no application, Made in USA, 4.7/1,867 Amazon rating). "Only EPA-registered rodent repellent trash bag" is the brand's own claim (site + STATUS); legal confirm sits with client.
