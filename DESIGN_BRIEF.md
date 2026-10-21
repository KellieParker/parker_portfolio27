# Portfolio Design Brief

Working notes on the look and feel of the site. Update as the direction evolves.

## Overall direction

Calm, polished, editorial. Midnight's structure and pacing, with a soft pink gradient hero (inspired by Maxine Ancheta's pink version) and small moments of personality.

**References**
- askmidnight.com: structure, palette, scroll motion, two-tone headlines
- maxineancheta.com (pink version): hero text on a soft gradient wash, mono metadata
- Jacky Boehm: name set in italic within the intro sentence
- Elias Vorn: large editorial project images with numbered mono labels
- Iridescent 3D star: accent colors and hero object

## Color

| Role | Color | Notes |
|---|---|---|
| Background | Cream `#F3EFE8` | Main page background |
| Surface | White `#FFFFFF` | Cards, alternating sections |
| Dark | Navy `#07172A` | Dark sections, footer, primary text |
| Muted text | Gray | Second half of two-tone headlines |
| Hero wash | Soft pink gradient | Blurred, atmospheric, behind hero text |
| Accent | Iridescent pink, lilac, butter yellow, periwinkle | Used sparingly: 3D objects, glows, hover states |

Sections alternate between light (cream/white) and dark (navy gradient) to set the rhythm as you scroll.

## Typography

- **Sans** for body and headlines (clean, like Public Sans or Geist)
- **Italic serif** for my name and a few highlighted words in the hero and headlines (candidates: Instrument Serif, Newsreader)
- **Mono, uppercase, small** for project metadata and labels (like Geist Mono)
- Two-tone headlines: first sentence dark, second sentence faded gray

## Hero

- A few sentences about who I am, with my name in italic serif
- Personality from special characters (for example ✦ ⊹ ↗ ◐), **no kaomoji**
- Soft pink gradient wash behind the text
- Small animated 3D object (I have these as HTML + JS files)
- No photo of me here

## Projects

- Large editorial images
- Mono label row per project, for example: `(001)  PROJECT NAME  CATEGORY • ROLE • YEAR  ↗`

## Motion

- Smooth scroll-triggered reveals, polished not flashy
- Subtle hover states (possibly an iridescent glow)
- 3D object gently animated in the hero

## Copy

- Calm and clear overall
- A few playful lines (footer, about, small labels)

## Pages

- **Home:** hero, featured projects, footer
- **Work / [project]:** case study template
- **About:** bio, photo of me, links (LinkedIn, email, resume)

## Not doing

- Kaomoji
- Scrolling ticker
- Photo on the homepage

## Tech

- Astro, deployed on Vercel from this repo
- Custom domain (to connect after first deploy)
