# Project brief — _TODO_ site name

> What the agent writes from. Anything still `_TODO_` is unknown: the agent asks
> rather than inventing content, contact details, prices or claims. Fill it in
> yourself, or answer the questions in chat and let the agent write the answers
> in. Delete sections that don't apply.
>
> If this is a test/demo site with invented content, say so here — the agent
> then marks fictional details as fictional and uses reserved values (e.g.
> example.com e-mail, ACMA/Ofcom/NANP fictional phone ranges).

## Business

| | |
|---|---|
| Name | _TODO_ |
| Tagline | _TODO_ |
| What it does | _TODO_ — one or two sentences |
| Location / service area | _TODO_ |
| Founded / key facts | _TODO_ |
| Currency, pricing basis | _TODO_ (e.g. AUD, per person, inc. GST) |

### Products / services

_TODO_ — a table of what is sold or offered, with the facts pages will need
(name, price, duration, key features). If this data will live in a custom post
type, say so: the agent builds it as Meta Box data + Bricks query loops.

### People

_TODO_ — names and roles the site may mention (or "none").

## Audience

- **Who:** _TODO_
- **Want:** _TODO_
- **Worry about:** _TODO_
- **Decide by:** _TODO_

## Voice

- _TODO_ — tone in three or four words (e.g. warm, direct, expert)
- _TODO_ — spelling (e.g. Australian English) and person ("you", "we")
- Avoid: _TODO_ — words, clichés or tones that are off-brand

## Pages

| Page | Purpose | Main sections |
|---|---|---|
| Home | _TODO_ | _TODO_ |
| _TODO_ | _TODO_ | _TODO_ |

Header and footer are Bricks templates; navigation follows
`standards/navigation.md` (a WordPress menu by default).

## Calls to action & forms

- **Primary CTA:** _TODO_ (label → destination)
- **Secondary CTA:** _TODO_
- **Forms:** _TODO_ — fields, and where submissions are e-mailed

## Contact details

| | |
|---|---|
| Email | _TODO_ |
| Phone | _TODO_ |
| Address | _TODO_ |
| Hours | _TODO_ |
| Social | _TODO_ |

## Proof

_TODO_ — testimonials, reviews, awards, logos, stats (with permission to
publish). Never invented for a real business.

## Colour scheme

**Theme:** **Dark** (dark page, light text). Applied by `init-brxprod` on
2026-10-27.

Per AGENTS.md › Changing colours: only root values are set (variants are
generated); only the neutral `base` / `surface` sits at 50% HSL lightness; text
uses the `--brxp-a11y-*-text` tokens.

| Role | Name | Value | Use |
|---|---|---|---|
| Primary | Navy | `#0B1320` | Buttons, CTAs, Surface 4 accent blocks |
| Secondary | Orange | `#F58220` | Navigation, links, headings, accents |
| Surface / base | Navy grey | `hsl(217, 15%, 50%)` (agent proposed: Primary's hue, desaturated) | Page background and text |
| Extra `brxp-…` (if any) | none | | |

Contrast (WCAG 2): Primary takes white text at 18.6:1. Secondary on white is
only 2.6:1, but on the dark Surfaces it is 7–9:1. Orange as text on a light
background needs a dark shade (~`-d-3` or darker).

Surfaces (dark theme):

| Surface | Background | Text | Link | Contrast text / link |
|---|---|---|---|---|
| 1 page / section | `--brxp-surface-d-9` | `--brxp-a11y-surface-d-9-text` | `--brxp-secondary-l-2` | 16.7 / 8.3 |
| 2 raised card | `--brxp-surface-d-8` | `--brxp-a11y-surface-d-8-text` | `--brxp-secondary-l-2` | 14.5 / 7.2 |
| 3 inset well | `--brxp-surface-d-10` | `--brxp-a11y-surface-d-10-text` | `--brxp-secondary-l-2` | 18.0 / 9.0 |
| 4 accent block | `--brxp-primary` | `--brxp-a11y-primary-text` | its own text colour | 17.1 / 17.1 |

Both site-wide theme styles (BRXProd, brxwireframes) take the page background,
body and heading text, and links from Surface 1; link hover is
`--brxp-secondary-l-4`.

**Open question:** buttons use Primary navy on a near-black page, so they stand
out poorly (low UI contrast). Decide whether buttons should move to Secondary
orange, get an orange/light border, or stay as they are.

More spec colours than roles? Map them per the `design-system` skill ›
*Mapping a brief's colours to the roles*.

## Typography

- **Headings:** _TODO_ (or "agent to propose")
- **Body:** _TODO_

## Motion

**GSAP** — effects adapted from the GSAP Prompt Library
(https://gsap.brxprod.com/), loaded only by BRXProd's `gsap-loader` snippet
(see AGENTS.md › Motion). _TODO_ — note any effects the design calls for.

## Imagery

- **Style:** _TODO_
- **Source:** _TODO_ — client photos, stock (which library), or placeholders.
  The agent asks before downloading each batch and records credits.

## Design inspiration

_TODO_ — screenshots or URLs, and whether they are inspiration only or a
design to match.

## Content sources

_TODO_ — existing site, documents, or "write from this brief".
