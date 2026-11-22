# Page recipes

Pick one. Each lists sections in order. Use components from `assets/components.css`.

## Landing page (sell one thing)
1. Nav (logo, 3 links at most, one secondary button)
2. Hero: label, headline (under 10 words), one sentence, primary + secondary button
3. Proof: 3 or 4 stats in a row
4. Three cards: the reasons
5. Closing call to action: one headline, one primary button
6. Footer

## Dashboard (see what needs attention)
1. Nav
2. Page title and one sentence on what the page shows
3. Row of 3 or 4 stats (the numbers that matter most)
4. One main table or list, sorted by what needs action first
5. Badges carry status: success, accent (needs review), danger (blocked)

## Form (get information)
- One column. Labels above fields. One primary button at the bottom, full width on mobile.
- Ask only what you need. Group related fields. Show errors under the field in words that say how to fix it.

## List and detail
- Left: list with a search field. Right: details of the selected item.
- Selected row uses `--accent-soft` as its background.
- On mobile, show the list first, then the detail on its own screen.

## Settings
- Sections separated by hairlines. Each section: title, one sentence, then controls.
- Save button appears once, at the end. Dangerous actions sit last and use the danger style.

## Rules that apply everywhere
- One primary button per screen. Others are secondary or ghost.
- Cards are quiet: surface fill, hairline border. No heavy shadows.
- Numbers use `.num` so columns line up.
- Keep line length under 640px (`--read-max`).
- Whitespace is the luxury signal. When in doubt, add one space step.
