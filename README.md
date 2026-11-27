# deepdiveintoabelsmind

My personal portfolio site. I'm a third-year Computer Science student at the University of Nottingham, and I'm looking for technology sales and consulting roles in London. The site shows who I am, what I've worked on and what I do outside of a screen.

**Live:** https://abelk10123.github.io/deepdiveintoabelsmind/

It's one static HTML page with inline CSS. There's no framework and no build step.

---

## Patch notes

### v0.3.0: Sprint 3, design (27 Nov 2026)

**Added**
- Open Graph and Twitter tags that point at the live site URL, plus a canonical link and a favicon.
- Width and height on every photo, so the page doesn't jump while images load.
- Section links now stop a little short of the top edge when you jump to them.

**Changed**
- Navigation is no longer hidden on phones. It wraps onto two lines at the top.
- "Preview my CV" is now a proper button, and the preview is shorter on small screens.
- Gallery photos react slightly on hover, and the text avoids single words on the last line.
- Portrait alt text is more descriptive, and the AK link says where it goes.

**Known issues**
- Travel photos still have no captions.
- The About me copy is still a draft.

---

### v0.2.0: Sprint 2, content (26 Nov 2026)

**Added**
- Projects rebuilt: the four current projects (two University of Nottingham modules, two personal) all marked "In progress". The coursework ones say the code is private and available on request.
- Travels gallery with 12 photos. They have no captions yet, so none are shown.
- CV as a PDF, with a preview on the page and a download link. My phone number is removed from it.
- Internship completion letter, linked from the Propmarker entry.
- New portrait photo on the landing page.

**Changed**
- Contact email is now abelkokkattu@gmail.com everywhere.
- Outside work is text only: Badminton, Table Tennis, Travelling, Meditation. The About me sentence matches.
- Removed the empty photo slots from About me and Outside work.
- Projects list is now the four current ones plus the EV platform and the OS simulator, which are on my CV. The Cyborg Platformer and SaaS quote calculator entries are gone because they aren't on my CV.

**Known issues**
- The About me copy is still a draft.
- Travel photos have no captions (waiting on `docs/travel-captions.md`).
- The CV's own Hobbies line still lists the old hobbies.

---

### v0.1.0: Sprint 1, skeleton (25 Nov 2026)

**Added**
- Magazine-style layout: large name, portrait, one accent colour, thin rules between sections.
- Sections for About me, Experience, Projects, Tech stack and Outside work.
- My profile photo on the landing page.
- Empty Travels and CV sections, ready for the content sprint.
- LinkedIn and GitHub links.

**Known issues**
- The About me copy is still a draft.
- Hobby and About photos show grey placeholders.
- The Travels and CV sections are placeholders.

---

## Roadmap

| Version | Sprint | Due | Scope |
|---|---|---|---|
| v0.1.0 | 1. Skeleton | Wed 25 Nov | Structure, pages and profile photo |
| v0.2.0 | 2. Content | Thu 26 Nov, 21:30 | Contacts, hobbies, projects, travel gallery, CV preview |
| v0.3.0 | 3. Design | Fri 27 Nov, 17:00 | Final design touches and an accessibility pass |
| v1.0.0 | 4. Release | Sat 28 Nov | Final checks and full patch notes |

Every sprint ships as a pull request. Nothing reaches the live site until I've reviewed and merged it.
