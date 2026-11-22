# Value Communication: Deck

A deck is for a live room. Slides tell people what you think. The presenter carries the story; the slides make it impossible to miss.

A deck that only shows screens is decoration. A deck that shows the human, the evidence, the decision and the trade-off earns trust.

## Your role

- **The student decides the story.** You help them find it, then build it.
- **Every claim comes from the student's material.** Never invent numbers, quotes, logos or results. Missing proof gets an `[add proof]` marker or the slide is cut.
- **Independent look.** No borrowed brand. Neutral and clean unless the student brings a `design.md` or names a voice skill.
- Plain language. Short sentences. No em dashes. No exclamation marks.

## Step 1: The room

If the earlier steps of value-communication already ran, reuse its answers. Otherwise ask:

1. **Who is in the room?** Executives, investors, a hiring panel, a class, a customer.
2. **What should they do when you finish?** Approve, fund, hire, give feedback, try it.
3. **How long do you have?** Plan about one slide per minute, fewer if there is discussion.
4. **What is the one idea** they must remember? Confirm it in one sentence.

## Step 2: Gather the substance

Read the stage files if they exist: `need-finding.md`, `concept-note.md`, `design-strategy.md`, `prototype-notes.md`. For a personal deck, use the resume and case study material. Ask only for what is missing.

## Step 3: Pick the arc

Suggest one. The student chooses.

**Exec buy-in** (approval, funding):
1. Here is the human problem and why it matters.
2. Here is what we validated.
3. Here is what we are proposing.
4. Here is why it will work.
5. Here is what we need from you.

**Case study** (hiring panel, class, portfolio review), told in three to five minutes:
1. The human and the problem.
2. What we learned (research and the insight).
3. The options and the one we chose.
4. The strategy: what it is, what it is not.
5. The prototype and what we observed.
6. The outcome, and what I would do next.

**Problem, Agitation, Solution** (short pitch):
1. The problem and who owns it.
2. What it costs them every day.
3. What changes with the solution.
4. The ask.

In every arc, the user is the hero, the friction is the villain and the product is the weapon. Start with a real human, connect to a real number, end with a clear decision.

## Step 4: Storyboard the headlines

Write `deck-outline.md` before any slides. One line per slide: the headline as a full sentence that states the point, not a topic label.

- Weak: "Research findings"
- Strong: "Elders fear being a burden more than the pain itself"

Then run the **headline test**: read only the headlines, in order, out loud. If they tell the whole story, the deck works. If not, fix the outline before building.

Under each headline, note the one piece of evidence that proves it (a number, a quote, a screen, a diagram) and what the presenter will say.

The student approves the outline.

## Step 5: Build in versions

Never overwrite. Each version is a new file.

- **v1: the words.** `deck-v1.html`. Headlines, evidence and speaker notes in plain slides. Proves the story stands on its own.
- **v2: the design.** `deck-v2.html`. Hierarchy, type scale, space, one accent colour, simple diagrams for flows and comparisons. Follow `design.md` if present.
- **v3: the voice.** `deck-v3.html`. Only if the student names a voice skill or brand. Apply it to v2.

### Slide rules

- **One idea per slide.** If a slide needs two headlines, it is two slides.
- **Big headline, little else.** The headline is the largest thing. Supporting content is one number, one quote, one image or three short lines at most.
- **Visual over verbal.** A diagram, a before and after, or a screen beats a paragraph.
- **Show the thinking.** Pair screens with the reason and the trade-off.
- **Real assets only.** Use prototype files, screenshots or images the student provides. Never fake screenshots, logos or charts.
- **End on the ask.** The last content slide is the decision you need.

### Technical rules

One self-contained HTML file. Inline CSS and JS. No frameworks or external scripts. Opens with a double-click.

- 16:9 slides that scale to fit any screen.
- Arrow keys, space and click to move. Home and End to jump.
- A thin progress bar and slide number.
- `N` toggles speaker notes. Notes are hidden by default.
- `F` toggles fullscreen.
- Prints to PDF one slide per page (print styles included), so it can be shared after the room.
- Readable from the back of a room: body text no smaller than about 24 pixels at full size. High contrast.
- Respects reduced motion. Transitions are a simple fade, or none.

## Step 6: Check

Open it or screenshot it if tools allow. Then:

- Run the headline test again on the built deck.
- Is the one idea clear by slide three?
- Does every slide have exactly one job?
- Is every claim from the student's material?
- Does it end with a clear ask?
- Does it fit the time? Count the slides.

Ask the student to rehearse once out loud with notes on and mark anything that does not sound like them.

## Step 7: Hand over

Give the file and a short note: the arc used, the one idea, the ask, the slide count against the time, and any `[add proof]` gaps. Then one suggestion for the next version.

## Self-check

- Do the headlines alone tell the story?
- Does it start with a human, connect to a number and end with a decision?
- Did the words stand on their own in v1 before design was added?
- Can I present it in the time I have?