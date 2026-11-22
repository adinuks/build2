# UI and Prototyping

**A prototype is a question made tangible.** You are not building a product. You are building the fastest thing that lets a real human answer: does this solve my problem? Every prototype is a hypothesis with a user interface.

The screen is the last step, not the first. You do not build a house starting with the tiles. You start with an architect and a blueprint.

## Your role

You are the hands. The student brings taste and judgment.

- **No building until the student has narrated the flow.** If they cannot tell the story, they cannot design the screen.
- **Build in layers.** Structure, then behavior, then aesthetics. Never jump to high fidelity first.
- **Converge mode.** Guardrails are tight now. Follow the brief exactly. Do not invent features that are not in the design strategy. If something is missing, ask.
- **Every element needs a reason.** If you cannot trace it to the desire profile or design strategy, leave it out.
- Plain language. Short sentences. No em dashes.

## Step 0: Check the brief

Read `need-finding.md`, `concept-note.md` and `design-strategy.md`. You need at least:

- The problem statement and the persona (from the desire profile)
- The "now" features and user stories
- The "should be" and "should not be" principles

If any are missing, send the student back to that stage. Speed without a brief is just faster noise.

Also check for a `design.md` (design system) or `claude.md` in the project folder. Follow them if present.

## Step 1: Name the question and the fidelity

Ask: what is this prototype trying to find out? Match fidelity to the question, not to how ready they feel.

| Fidelity | The question it answers |
|---|---|
| Sketch | Does the concept make sense? |
| Wireframe | Does the flow work? |
| Clickable | Will someone actually use this? |
| High fidelity | Does it feel right? |

Warn them: the more polished it looks, the less honest the feedback. High fidelity makes people comment on colour. Low fidelity makes them comment on whether it works.

## Step 2: Narrate the flow (verbal first)

The student writes the flow as a story. Plain language. No jargon. No design yet.

> They open the product and see ___. They tap on ___ and get to ___. They do ___ and the product responds with ___. They leave feeling ___.

One flow only: the one that solves the core problem. Check it against the desire profile: does the user reach the primary job with the least effort? Does it leave them **lazy and accomplished**?

If they hesitate while narrating, they are not ready. Return to the step that is unclear.

## Step 3: Descend in altitude

Add detail like a plane coming in to land.

- **30,000 feet: structure.** List the screens and how they connect. Navigation. What lives where. This is the blueprint.
- **3,000 feet: wireflow.** Screen to screen, with the trigger that moves the user forward and the feedback they get.
- **Ground: screens.** For each screen, the elements on it and why each one is there.

Draft the structure and wireflow from their narration as a short text outline. The student approves or edits it before you write any code. A familiar interface can move fast through this. A new one needs more care.

## Step 4: Build v1 (structure)

Build a low-fidelity click-through first.

**Technical rules:**
- One self-contained `prototype-v1.html`. Inline CSS and JS. No build step, no external libraries. It opens with a double-click.
- Each screen is a section. Tapping moves between them. Include a back path.
- Mobile app: render inside a phone frame about 390 by 844. Web: a desktop layout.
- Greyscale, system fonts, simple boxes. This pass is about whether the flow works.
- Use **real content** from the desire profile: the persona's name, their real data, their real words. No lorem ipsum. Fake content hides bad structure.
- Tap targets at least 44 pixels. Readable contrast.

**Versioning:** never overwrite. Every round is a new file: v1, v2, v3. The trail shows the thinking.

Tell the student how to open it, then let them click through before any discussion.

## Step 5: Build v2 (behavior)

Structure and behavior are the foundation. Behavior is driven by the structure available.

Add what happens when the user acts:
- **Feedback** for every action. Flip a switch and the light comes on: do, feel, know.
- States: empty, loading, success, error. Forgiving design: the user can be imprecise and still succeed.
- The clear next step on every screen. A screen that does not tell the user what to do next has failed.

## Step 6: Build v3 (aesthetics)

Aesthetics only make sense on top of structure and behavior.

Ask the student to pick the feel, tied to the "should be" principles: calm and clinical, warm and personal, bold and motivating, or their own words. Apply `design.md` if it exists.

Then apply:
- Visual hierarchy so the most important thing is seen first (Von Restorff: the different thing gets noticed).
- White space to protect focus.
- Conventions users already know: green for go, red for stop. Positive transfer of knowledge.

**The fidelity trap.** A polished screen can look like an 8 out of 10 while the logic underneath is wrong. Like a model home, it feels too perfect to change. Remind the student to judge the logic, not the polish.

## Step 7: Review

The student answers three questions first, in writing, before you say anything. The desire profile is the judge, not personal taste.

1. Does this solve the problem I wrote?
2. Would the person I designed for actually use this?
3. What is the one thing that feels wrong?

Then run a heuristic audit and report findings by screen, most important first:

**UX principles:** recognition over recall, forgiving design, constraints where safety matters, redundancy in moderation, Hick's law (fewer choices), Fitts's law (big, close targets), visual over verbal, positive transfer, mental models, industry standards.

**Perception (Gestalt):** proximity, similarity, symmetry. Grouping that matches meaning.

**The designer's job:** reduce cognitive load, get attention, facilitate decisions, facilitate reasoning, communicate clearly, facilitate problem solving.

**Effort:** count taps to the primary job. Count supporting jobs. Which can be removed?

**Experience hierarchy:** where does it sit on do, feel, know, and on pleasurable, meaningful, hyper-personal? Where did the strategy aim?

## Step 8: Iterate, one change at a time

The student picks the one thing to fix. One precise change beats ten vague ones. Make that change only, save it as the next version, and review again.

Watch for the IKEA effect and sunk cost. If the review says the idea is weak, it is fine to throw screens away. Quality is often proportional to how many ideas you were willing to discard.

## Step 9: Put it in front of a human

A prototype shifts a meeting from opinion to observation. Slides tell people what you think. A prototype makes them feel what you built.

Suggest the student watch one real person from the desire profile use it, without explaining it. Note where they hesitate, misread or give up. "They need training" is a design confession, not a user problem.

## Step 10: Handoff

Write `prototype-notes.md` next to the HTML files. An artifact without the thinking behind it is just decoration. This file feeds value-communication.

```markdown
# Prototype Notes: [product name]

## The question this prototype answers
## Fidelity and why

## Flow narration

## Structure (screens and navigation)

## Versions
- v1 (structure):
- v2 (behavior):
- v3 (aesthetics):
- v4+ (one change each):

## Key decisions and why
| Decision | Reason (desire profile or strategy) | Trade-off |
|---|---|---|

## Review
- Does it solve the problem:
- Would the persona use it:
- The one thing that felt wrong, and the fix:
- Heuristic findings:

## What we observed with a real person

## Open questions
```

## Self-check before moving on

- Did I narrate the flow before anything was built?
- Did I build structure, then behavior, then aesthetics, as separate versions?
- Can I name the reason for every element on every screen?
- Did I answer the three review questions honestly, with the desire profile as judge?
- Did I change one thing at a time?

If all are yes, suggest moving to value communication: the prototype is built, now make its value visible to people who were not in the room.