# Portfolio Design Brief

Working notes on the look and feel of the site. Update as the direction evolves.

## Overall direction

Calm, polished, editorial. Midnight's structure and pacing: a dark gray gradient hero and footer bookending a clean white middle, with small moments of personality.

**References**
- askmidnight.com: structure, palette, scroll motion, two-tone headlines
- maxineancheta.com (pink version): hero text on a soft gradient wash, mono metadata
- Jacky Boehm: name set in italic within the intro sentence
- Elias Vorn: large editorial project images with numbered mono labels
- Iridescent 3D star: accent colors and hero object

## Color

| Role | Color | Notes |
|---|---|---|
| Hero + footer | Dark gray gradient on `#0E0E0F` | Soft, slowly drifting blur of near-black and dark grays |
| Content sections | White `#FFFFFF` | Everything between hero and footer |
| Text on dark | Cream `#F3EFE8` | Muted version at ~42% opacity for second sentences |
| Text on white | Near-black `#111113` | Muted version at ~42% opacity |
| Accent | Iridescent pink, lilac, butter yellow, periwinkle | Comes from the 3D gem only; no other color on the page |

Page rhythm: **dark hero → white content → dark footer.**

## Typography

- **Sans** for body and headlines (clean, like Public Sans or Geist)
- **Italic serif** for my name and a few highlighted words in the hero and headlines (candidates: Instrument Serif, Newsreader)
- **Mono, uppercase, small** for project metadata and labels (like Geist Mono)
- Two-tone headlines: first sentence dark, second sentence faded gray

## Hero

- Full-width intro text spanning the page, my name in italic serif
- Personality from special characters (for example ✦ ⊹), **no kaomoji**
- Dark gray gradient background
- One 3D holo heart (~90×90) above my name, left-aligned with the first letter
- Bottom row in mono: "Currently designing @ Alpha FMC" / "Previously @ Walt Disney World"
- No photo of me here

## Projects

- Large editorial images
- Mono label row per project, for example: `(001)  PROJECT NAME  CATEGORY • ROLE • YEAR  ↗`

## Motion

- Smooth scroll-triggered reveals, polished not flashy
- Subtle hover states (possibly an iridescent glow)
- 3D heart slowly spinning in the hero

## Copy

- Calm and clear overall
- A few playful lines (footer, about, small labels)

## Pages

- **Home:** hero, featured projects, footer
- **Work / [project]:** case study template
- **About:** bio, photo of me, links (LinkedIn, email, resume)

## Footer

- Dark gray gradient, matching the hero
- Big closing line with a playful touch, plus LinkedIn, email, resume links

## 3D assets

- `prototype/heart.html`, `star.html`, `flower.html` share one `three-d-stage.js`
- Transparent backgrounds, so they sit on any section

## Not doing

- Kaomoji
- Scrolling ticker
- Photo on the homepage

## Tech

- Astro, deployed on Vercel from this repo
- Custom domain (to connect after first deploy)
