# deepdiveintoabelsmind

My personal portfolio site. I'm a third-year Computer Science student at the University of Nottingham, and I'm looking for technology sales and consulting roles in London. The site shows who I am, what I've worked on and what I do outside of a screen.

**Live:** https://abelk10123.github.io/deepdiveintoabelsmind/

It's one static HTML page with inline CSS. There's no framework and no build step.

---

## Patch notes

The full history, newest first. Every version shipped as its own pull request.

### v1.0.0: Sprint 4, release (28 Nov 2026)

This is the first full release. Nothing new on the page. This sprint was a final check of everything from v0.1.0 to v0.3.0.

**Checked**
- Links: LinkedIn, GitHub, the mailto link, the CV PDF and the internship letter are all in place and point at the right addresses. GitHub answers. LinkedIn blocks automated checks, so I couldn't confirm that one by machine.
- My phone number isn't anywhere in the repo, including the text inside the CV PDF. The internship letter is a scan with no text layer, so that one needs a quick look by eye.
- The only email on the site is abelkokkattu@gmail.com.
- No links to private repos. The two university projects say the code is private and available on request.
- All 13 photos have alt text, a width and a height. None are over 1600px on the long side and none carry EXIF data.
- No tracked file mentions the tools I used to build it, and there are no hidden characters in the HTML or Markdown.

**Changed**
- Patch notes are now the full history, and the roadmap shows all four versions.

**Known issues**
- Travel photos have no captions yet. I'd rather show nothing than guess.
- The About me copy is still a draft.
- The CV PDF's own Hobbies line still lists the old hobbies. The site itself is right.
- I couldn't test the page in a browser at 1440, 390 and 320px, or read the console, during the release run. The mobile check in v0.3.0 still stands. Worth a quick look once it's live.

---

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

After merging, tag `v1.0.0` on `main`.

Every sprint ships as a pull request. Nothing reaches the live site until I've reviewed and merged it.
