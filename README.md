# Tech Engineering Pathways

A free, beginner-friendly field guide to careers in tech engineering. If you are new to tech, or switching in from another field, it helps you work out which roles exist, which ones might suit you, and exactly what to learn to get there.

## What's inside

- **68 roles** across 10 departments: software and web, cloud and security, AI and data, games and design, product and business, health and biomedical, electronics and chips, robotics and automation, energy and materials, and research.
- **67 skills, 13 tools and 15 fields**, each explained in plain language with a small practice exercise and free places to learn it.
- **75 portfolio projects**, each tagged Starter, Intermediate or Advanced with a time estimate, numbered build steps and free guides.
- **A trail for every role:** the skills and projects it needs, grouped into stages so you always know what comes next.

Every trail starts from one of three starting points: **Programming basics**, **Math and physics**, or **Electronics basics**. You do not need all three, and anything you learn early gets reused later.

## How to use it

1. **Find a role.** On the home page, answer three short questions (what you would like to work on, which starting point suits you, how long a path you want). The list of matching roles updates as you answer.
2. **Open a role.** See what the job is, what a normal day looks like, and whether it might fit you.
3. **Follow the trail.** Work through the stages in order. Tick off each skill as you learn it. "Next up" always marks your next step, and the home page remembers where you stopped.
4. **Build the portfolio.** Each role ends with one to three projects. Finished projects are what show an employer you can do the work, so put each one on GitHub with a short write-up.

You can also browse **All roles**, **Projects** (filter by level and department) and **All skills** (an A to Z index), or use the search box at the top.

## Running it

Open `index.html` in any modern browser. That's it.

To serve it locally instead (for example while editing):

```bash
python -m http.server 8765
```

Then visit `http://localhost:8765/`.

To publish it, upload the file to any static host, such as GitHub Pages, Netlify or Vercel. Keep it named `index.html` so it loads as the home page.

On GitHub Pages: open the repository's **Settings → Pages**, set **Source** to **Deploy from a branch**, pick `main` and `/ (root)`, and save. The site appears at `https://<username>.github.io/<repository>/` within a minute or two.

## Good to know

- **Your progress stays on your device.** Ticked skills, your answers and your last trail are saved in your browser's local storage and are never sent anywhere. Clearing site data resets them. The only outside request the page makes is to Google Fonts for its typefaces; without internet it falls back to system fonts.
- **Every resource is free** as of October 2026. Courses and pages move, so if a link breaks, search for its title.
- **This is a general guide**, not the official curriculum of any university or employer. Use it to explore and plan, then adapt it to your own goals.
- **Accessibility:** works with a keyboard and screen reader, follows your system's light or dark mode, respects reduced-motion settings, and works on phones.

## Editing the content

All content lives in the `<script>` block of the HTML file:

- `RAW`: every skill, tool, field, project and role. Each row is `[id, type, name, prerequisites, note, practice or steps, resources, "Level|Time"]`. Type is `s` skill, `t` tool, `p` project, `f` field or `j` role. Project steps are separated by `; `.
- `INFO`: the longer description of each role (what it is, a normal day, who it fits).
- `GROUPS`: the 10 departments and which roles belong to each.

To put a skill or project on a role's trail, add its id to that role's prerequisites. Trails are worked out automatically from those links.

`PRODUCT.md` describes who the guide is for and its principles. `DESIGN.md` documents the visual design system.
