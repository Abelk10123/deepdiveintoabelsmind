# Portfolio v2: short design (approved 2026-11-19)

**Intent.** A personal, non-generic portfolio for tech sales / consulting roles in London. It should show hiring teams a real person with a technical stack, experience and skills. v1 looked AI-generated.

**Goals.** A light theme, simple to read, an About me section and a hobbies section, with room for Abel's own photos. LinkedIn and GitHub linked.
**Non-goals.** Dark mode, frameworks, a build step, animations beyond simple hover states.
**Anti-goals.** A template or AI look (tag pills everywhere, card grids, gradient accents), invented facts, the phone number, links to private repos.

**Approaches considered.**
- A. Scrapbook letter: very personal but informal.
- **B. Magazine profile (picked by Abel):** large name and large portrait, one accent, editorial rules.
- C. Quiet single column: most readable, but less visual.

**Build.** One `index.html` with inline CSS, plus `images/`. Hosting target: GitHub Pages via `Abelk10123/portfolio-site`.

**Look.** White ground, near-black ink, one burnt-orange accent, a bold sans for headings and a readable body face. Thin black rules between sections.

**Order.** Hero (name, pitch, links, portrait) → About me (first-person draft, 2 photos) → Experience → Projects (sales projects first, honest status) → Tech stack (compact list) → Outside work (5 hobby photos with captions) → footer.

**Photo slots.** `images/portrait.jpg`, `about-1.jpg`, `about-2.jpg`, `boxing.jpg`, `music.jpg`, `calisthenics.jpg`, `yoga.jpg`, `travel.jpg`. Each slot shows a neutral box until the file exists.

**Left to the builder.** Exact fonts, spacing, and the draft copy (Abel rewrites the About section).

**Done when.** Content matches the CV; the page reads well at 1440 and 390px with no sideways scroll; it passes a Web Interface Guidelines review; it contains no phone number.
