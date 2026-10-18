---
name: Tech Engineering Pathways
description: A beginner's field guide to tech engineering roles and the free skills trail that leads to each one.
colors:
  ground: "#F2F6F1"
  surface: "#FFFFFF"
  sunk: "#E6EEE7"
  ink: "#12231C"
  ink-2: "#465A50"
  rule: "#C9D7CD"
  rule-2: "#A9BDB0"
  band: "#0E3B2E"
  band-ink: "#F2F6F1"
  band-ink-2: "#B9D2C4"
  band-rule: "#2B5A4A"
  mark: "#A83519"
  mark-bg: "#FBE6DC"
  link: "#1D5E44"
  trail: "#D99A1E"
  trail-bg: "#FBF0D6"
  done: "#1E6B4A"
  dept-software: "#2450B8"
  dept-software-tint: "#E8EEFB"
  dept-cloud: "#0B6D92"
  dept-cloud-tint: "#E1F1F7"
  dept-ai: "#6A3DB5"
  dept-ai-tint: "#EEE8FA"
  dept-games: "#B02D68"
  dept-games-tint: "#FBE7F0"
  dept-business: "#8A5406"
  dept-business-tint: "#FAEED6"
  dept-health: "#0B6A5A"
  dept-health-tint: "#DAF1EA"
  dept-electronics: "#AD4A06"
  dept-electronics-tint: "#FAE8DA"
  dept-robotics: "#B02F2F"
  dept-robotics-tint: "#FAE3E3"
  dept-energy: "#44690F"
  dept-energy-tint: "#E8F1D6"
  dept-research: "#495E6D"
  dept-research-tint: "#E6ECEF"
typography:
  display:
    fontFamily: "Young Serif, Georgia, 'Times New Roman', serif"
    fontSize: "clamp(36px, 5.6vw, 64px)"
    fontWeight: 400
    lineHeight: 1.12
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Young Serif, Georgia, 'Times New Roman', serif"
    fontSize: "clamp(28px, 3.4vw, 40px)"
    fontWeight: 400
    lineHeight: 1.12
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Young Serif, Georgia, 'Times New Roman', serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.18
    letterSpacing: "-0.01em"
  lede:
    fontFamily: "'Atkinson Hyperlegible Next', 'Atkinson Hyperlegible', system-ui, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "'Atkinson Hyperlegible Next', 'Atkinson Hyperlegible', system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
    fontFeature: "tnum"
  body-small:
    fontFamily: "'Atkinson Hyperlegible Next', 'Atkinson Hyperlegible', system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  stage-label:
    fontFamily: "'Atkinson Hyperlegible Next', 'Atkinson Hyperlegible', system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0.06em"
  label-mono:
    fontFamily: "'Atkinson Hyperlegible Mono', ui-monospace, Menlo, Consolas, monospace"
    fontSize: "13px"
    fontWeight: 500
    letterSpacing: "0.02em"
rounded:
  swatch: "3px"
  plate: "4px"
  control: "8px"
  stop: "12px"
  panel: "14px"
  key: "16px"
  pill: "999px"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  section: "64px"
  chapter: "96px"
components:
  button-primary:
    backgroundColor: "{colors.band}"
    textColor: "{colors.band-ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "44px"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "44px"
  button-quiet:
    textColor: "{colors.link}"
    rounded: "{rounded.pill}"
    padding: "0 10px"
    height: "44px"
  chip:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "6px 14px"
    height: "40px"
  pill-next:
    backgroundColor: "{colors.mark-bg}"
    textColor: "{colors.mark}"
    rounded: "{rounded.pill}"
    padding: "2px 10px"
  key-option:
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "4px 12px"
    height: "34px"
  key-option-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.surface}"
    rounded: "{rounded.control}"
  specimen:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    padding: "20px 20px 18px"
  trail-stop:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.stop}"
    padding: "14px 16px"
  trail-stop-done:
    backgroundColor: "{colors.sunk}"
    textColor: "{colors.ink-2}"
  input-search:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "46px"
---

# Design System: Tech Engineering Pathways

## Overview

**Creative North Star: "The Field Guide"**

Tech Engineering Pathways reads like a naturalist's field guide that has been set for the screen. A forest-green band carries the masthead and hero. Below it, white plates sit on a pale sage ground, ruled with hairlines like a specimen sheet. Roles are specimens: each has a catalogue number, a name set in a warm display serif, a short description, and a "Grows from" line of field marks. A three-question identification key gets a beginner to a short list. Once they open a role, an ochre dashed trail leads stage by stage to it, and a single vermilion mark shows the next stop.

The density is that of a calm reference book. There is generous air between chapters (64 to 96px), tight hairline grids inside plates, and type sized for reading (17px body, 19px lede). Colour is held back. Green ink and green band do the structural work. One spot colour per department appears only where the department is named. Ochre belongs to the trail, and vermilion means "next" and nothing else.

The build rejects two visual models outright: the pan-and-zoom node graph and the generic dev-roadmap card grid. Plates are ruled grids with shared hairlines, not floating cards. Paths are a vertical trail, not a graph.

**Key Characteristics:**
- Forest-green band for the masthead, the hero and the finish banner. Pale sage ground, white plates.
- Hairline-ruled specimen plates. Cells share one border instead of each card having its own.
- Young Serif for names and headings. Atkinson Hyperlegible Next for everything read. Atkinson Hyperlegible Mono for catalogue numbers and key letters.
- One spot colour per department, used on swatches, tints and the department rule only.
- Progress is shown by marks (check, strikethrough, sunk fill, dashed border, pill, flag), never by a change of hue.
- Light and dark themes are both fully tokenized and follow the system preference.

## Colors

The palette is a restrained forest-and-paper system. Three narrow signal colours each have one job, and a spectrum of ten department spots is confined to swatches and tints.

### Primary
- **Forest Band** (band): Masthead, hero, primary button fill and the "trail complete" finish banner. It is the one large field of colour on any screen.
- **Fern Link** (link): Links, quiet buttons, disclosure summaries, focus rings (also `--focus`) and the mono key lettering. Green is the interactive colour.

### Secondary
- **Trail Ochre** (trail): The dashed trail line, the hollow stage rings, the resume flag and the summit icon on the finish banner. **Ochre Wash** (trail-bg) is the fill of "Try this" project boxes and of text selection.

### Tertiary
- **Vermilion Mark** (mark) on **Vermilion Wash** (mark-bg): Only for the "Next up" pill and the border and soft glow of the next trail stop.
- **Done Green** (done): The checked checkbox fill, the progress-meter fill, the "N done" count on specimens and the completed-skill chip border.

### Neutral
- **Sage Ground** (ground): The page background.
- **Plate White** (surface): Plates, the key, panels, stops, chips and inputs.
- **Sunk Sage** (sunk): Hover rows, completed stops, the meter track.
- **Forest Ink** (ink) / **Moss Grey** (ink-2): Primary text, and secondary text, captions and type marks.
- **Hairline** (rule) / **Strong Hairline** (rule-2): Plate grid lines and dividers, and control outlines and dashed empty states.
- **Band Ink / Band Ink 2 / Band Rule**: Text, secondary text and borders on the green band.

### Department spots
There are ten spot/tint pairs: Software blue, Cloud teal, AI violet, Games and design magenta, Business umber, Health green-teal, Electronics orange, Robotics red, Energy olive and Research slate. A page applies one pair through the scoped `--g` / `--gb` variables, set by a department class. The spot fills the 12px **swatch**, the 3px underline of a department section header and the field-mark bullets on a role page. The tint fills the role header band and the hover state of specimens and role rows.

### Named Rules
**The One Meaning Rule.** Vermilion means "Next up" and nothing else. Links, focus and key letters are forest green. Ochre is the trail. Done green is completion. If a new element needs emphasis, it does not get one of these hues.

**The Spot Colour Rule.** Department hues appear only on swatches, tints, the department header rule and field-mark bullets. They never colour text, buttons or links. Blue appears in the system only as the Software swatch.

**The Two Themes Rule.** Every colour token has a dark-theme counterpart, applied under `prefers-color-scheme: dark` unless `data-theme="light"` is set. New colours ship as a light/dark pair, or they do not ship.

## Typography

**Display Font:** Young Serif (with Georgia, Times New Roman)
**Body Font:** Atkinson Hyperlegible Next (with Atkinson Hyperlegible, system-ui)
**Label/Mono Font:** Atkinson Hyperlegible Mono, weight 500 (with ui-monospace, Menlo, Consolas)

**Character:** A sturdy, slightly old-fashioned serif names things, the way a field guide prints species names. A sans built for legibility carries every sentence a beginner has to read. Mono is reserved for numbers in the catalogue.

### Hierarchy
- **Display** (400, clamp(36px, 5.6vw, 64px), 1.12): The page h1 on the hero, role, skill and index pages. Role and skill pages use a 58 to 64px top end. Width is capped at 18 to 22ch. The phone hero is 34px.
- **Headline** (400, clamp(26–28px, 3–3.4vw, 34–40px), 1.12): Section h2s such as the plate header, the trail header, "Three places to start" and department sections.
- **Title** (400, 20 to 26px, 1.18): Specimen names (21px), the key heading (26px), panel and index headings.
- **Lede** (400, 19px, 1.55): The intro under a page h1, max 60ch, in ink-2 (band-ink-2 on the band).
- **Body** (400, 17px, 1.6, tabular numerals): Running text. Notes are capped at 70ch.
- **Body small** (15 to 16px, 1.5): Specimen descriptions, step notes and captions. Plate captions and the plate-header note are italic.
- **Stage label** (700, 15px, uppercase, 0.06em): Only the "Stage N" headings on a trail. It is the heading itself, not a label above one.
- **Label mono** (500, 13 to 14px): Specimen catalogue numbers ("No. 12"), couplet numbers, option letters, step counts and index counts.

### Named Rules
**The Serif Names Rule.** Young Serif is used only at weight 400, for headings and names. It never sets body copy, buttons or labels.

**The No Eyebrow Rule.** Headings stand alone. There are no small uppercase labels above them. Classification goes in a line under the name, such as the specimen's "Grows from" field marks, or in a working link.

## Layout

There is a single centred column of max 1240px. Side padding is 32px from 720px up, and 16px (respecting the safe area) below that. The home page's first viewport is a green hero band (40px top, 112px bottom padding). The **field** grid (a 360px key column plus a fluid plate) is pulled up 80px so that the key overlaps the band. From 960px the key is sticky at 84px from the top and scrolls internally. Below 960px the key and plate stack.

Specimen plates use `repeat(auto-fill, minmax(250px, 1fr))` with shared hairlines. Role and skill pages use an asymmetric two-column grid (1.25fr / 1fr, 40px gap) that collapses at 860px. The skill index is set in newspaper columns (`columns: 3 260px`). The trail is a single column indented 44px (36px on phones) for the dashed line and stage rings.

The spacing rhythm is 8 / 12 / 16 / 24 / 32 within components, 64px between sections and 96px before chapter breaks and the footer. The masthead is sticky on desktop and static under 720px, where the nav becomes a horizontal scroller and search takes a full row.

## Elevation & Depth

The system is flat and tonal. Plates, stops and panels sit on the sage ground, separated by hairlines and the shift from white to sage. Shadows are rare and soft, and each one marks a specific job: an element that floats over the band or over content, or the one next stop.

### Shadow Vocabulary
- **Key lift** (`box-shadow: 0 18px 40px -24px rgba(10,30,20,.35)`): Only on the identification key, which overlaps the band.
- **Popover** (`box-shadow: 0 12px 32px -8px rgba(10,30,20,.28)`): The search results dropdown.
- **Next glow** (`box-shadow: 0 10px 28px -18px var(--mark)`): The next trail stop, paired with its vermilion border.

### Named Rules
**The Hairline Before Shadow Rule.** Separate things with a 1px rule or a tonal step first. A shadow is allowed only when an element overlaps another layer, or to mark "next".

## Shapes

Corners follow function. Grids and plates are nearly square (4px), because they are printed sheets. Interactive objects are round: pills (999px) for buttons, chips, nav items, search fields and the Next up pill. Containers soften as they get more self-contained: 8px for checkboxes and key options, 12px for stops and empty states, 14px for panels, the resume bar and the finish banner, and 16px for the key. Swatches are 3px squares, stage markers are hollow 17px rings with a 3px ochre stroke, and the trail is a 3px dashed bar (10px dash, 6px gap). Rules have weights: 1px hairline as the default, 2px ink for index and "start" headers, 3px department spot for department section headers.

Type marks are told apart by outline shape, all in ink-2: skill is a circle, tool a rounded square, project a diamond, field a hexagon. Roles are a filled triangle in ink.

## Components

### Buttons
- **Shape:** full pill (999px), 44px tall, 600 weight 16px.
- **Primary:** forest band fill, band-ink text. On hover, brightness rises to 1.15.
- **Secondary:** white surface, strong-hairline border. On hover the border turns ink.
- **Quiet:** transparent, link green, 10px side padding, underlined on hover.
- **On the band:** inverted (band-ink fill, band text), 40px tall, used for "Continue" on the resume bar.

### Chips
- **Style:** a white pill with a strong-hairline border, 40px minimum height, 15px text, a type glyph or swatch on the left.
- **State:** on hover the border turns ink and the fill sunk. A completed skill gets a done-green border, not a fill change.

### Cards / Containers
- **Specimen plate:** a hairline grid on white with 4px outer radius. Each cell holds a mono "No. N" (its index in All roles), the serif name, a description, a "Grows from" field-marks line, and a meta row with the department tag, step count and done count. On hover the cell fills with its department tint.
- **Panels** (field marks, resume, finish): 14px radius. Field marks is white with a hairline border. Resume and finish sit on the band.
- **Empty state:** white with a dashed strong-hairline border and 12px radius.

### Inputs / Fields
- **Search:** a 42 to 46px pill. On the band it uses a translucent white fill, a band-rule border and a magnifier glyph inset at 14px. On the ground it is white with a strong-hairline border.
- **Focus:** a 2px link-green outline with a 3px offset everywhere (band-ink on the band).

### Navigation
- The masthead sits on the band: a brand mark (a ring with an ochre dashed trail), the serif wordmark, and a small sans subtitle. Nav items are pills in band-ink-2, 600 weight 15px. Hover adds an 8% white wash. The current page is inverted (band-ink fill, band text).

### Identification Key
The signature entry point. Three numbered couplets are separated by hairlines. Each option is a full-width row with an 8px radius and a mono letter in link green. Hover fills it sunk. When selected it is filled with ink and its text is surface-coloured, with a ring around any swatch. The footer shows the match count and a reset action.

### Trail
The signature path view. A dashed ochre line runs down the left with hollow ochre stage rings. Each stop is a white 12px card holding a 28px checkbox, the skill name, its type mark, a note, an "Easier after" line, and a "Show more" disclosure with an ochre-wash "Try this" box and resource links. Progress states are shown as marks: checked (done-green box), done (sunk fill and strikethrough), locked (dashed border), next (vermilion border, glow and "Next up" pill). A progress meter (10px pill bar, done-green fill) sits in the trail header. A forest-band finish banner closes the trail. The line draws on once per role per session (1.4s, `cubic-bezier(.16,1,.3,1)`). Under reduced motion the path is static.

## Do's and Don'ts

### Do:
- **Do** keep vermilion (mark) for "Next up" alone, and use link green for every link, focus ring and key letter.
- **Do** show progress with marks: a check, a strikethrough, the sunk fill, a dashed locked border, the Next up pill and the resume flag.
- **Do** number specimens "No. N" by their index in All roles and give each one a "Grows from" field-marks line.
- **Do** build grids as hairline-ruled plates with shared borders on white, on the sage ground.
- **Do** apply department colour through the `--g` / `--gb` pair, on swatches, tints and the department rule only.
- **Do** ship every new colour as a light and dark token pair.
- **Do** run the trail draw-on once per role per session, and give reduced motion a static path.

### Don't:
- **Don't** use a pan-and-zoom node graph or a generic dev-roadmap card grid.
- **Don't** put eyebrow labels or kickers above headings.
- **Don't** colour type marks. Skill, tool, project and field are all ink-2 and differ by shape.
- **Don't** use blue anywhere except the Software department swatch and tint.
- **Don't** signal progress by changing hue alone.
- **Don't** set Young Serif at any weight other than 400, or use it for body text or controls.
- **Don't** add shadows to plates or stops at rest. Depth is hairline and tone.
