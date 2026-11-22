# Value Communication: Website

A website is value communication that works while you sleep. It sells one thing to one audience and asks for one action.

What it sells is the student's choice. Sometimes it is **themselves**: a portfolio, a personal brand, a career move. Sometimes it is a **product**: a concept, a prototype, a case study. Same spine, different substance.

Substance beats looks. A beautiful site with nothing to say is decoration. Most of the work is finding the material, not designing the page.

## Your role

- **The student decides what to sell.** You interview until the substance is clear.
- **You draft and build.** Copy, structure, HTML.
- **Every claim comes from the student.** Never invent numbers, clients, testimonials, results or quotes. Missing proof gets an `[add proof]` marker or the section is cut. Keep claims as exact as the source: "more than 20 years" becomes "20+ years", never "20 years".
- Plain language. Short sentences. No em dashes. No exclamation marks.

## Step 1: What are you selling?

If the earlier steps of value-communication already ran, reuse its answers. Otherwise ask:

1. **What are you selling?** Yourself or a product?
2. **To whom?** Hiring manager for a named role, founders, clients, customers, investors, a class.
3. **What should they do?** Contact you, book a call, try the prototype, join a waitlist, download a case study.

Then confirm the **one idea** in one sentence. Everything on the page serves it.

## Step 2: Interview for substance

Pick the mode. Ask one question at a time. Push for specifics: names, numbers, moments.

### Mode A: Selling yourself

Start from their resume if they have one. Then go deeper. People are often surprised how much they do not know about themselves.

- **Destination.** What role or opportunity is this for? (A target role sharpens everything. "Agentic PM" is better than "PM".)
- **Signals.** Brands, institutions, scale, domains. What makes a stranger take you seriously in five seconds?
- **Proud moments.** Three to five moments where you created real value. For each: the situation, what you did, what changed, and a number if one exists.
- **Demonstrable skill.** What can you show, not just claim? Case studies, prototypes, writing, talks. A case study should be tellable in three to five minutes.
- **Learning portfolio.** What have you built or learned recently, especially outside your job? Breadth matters: a hundred different things done once beats one thing in a hundred flavours.
- **Competence.** Core skills, auxiliary skills (storytelling, negotiation), and meta skills (learnability, figure-out-ability).
- **Gaps.** Between who you are today and the destination role, what is missing? The site can show how you are closing it.
- **Voice.** How do you want to sound? Three words.

### Mode B: Selling a product

Read the stage files if they exist: `need-finding.md`, `concept-note.md`, `design-strategy.md`, `prototype-notes.md`. Pull from them before asking anything. Then fill the gaps:

- **Who it is for**, and who it is not for.
- **The problem** in the user's words, and what it costs them today.
- **What changes** when they use it. The business value line.
- **The 3 core things** it does.
- **Proof.** Research numbers, quotes from real users (with consent), prototype screens, early signups. If there is none yet, say so honestly.
- **The action.** Try it, join, contact, fund.

## Step 3: Write the copy first

Write `site-copy.md` before any HTML. The layout exists to give each line room to land. Show it to the student and get approval.

Copy rules:
- **Hero headline:** six words or fewer, a short declarative. One sub-line under it that says who it is for and what changes.
- **One idea per section.** Each section has exactly one job.
- **Benefits before features. People before parts. A number beats an adjective.**
- **Problem, Agitation, Solution** for product pages. **Proof, then promise** for personal pages.
- No jargon, no hedging, no stacked superlatives ("passionate, world-class, results-driven"). Replace with a fact.

### Section patterns

**Selling yourself:**
1. Hero: who you are, in one line, aimed at the destination.
2. Signals: brands, scale, years, domains. A strip, not a paragraph.
3. Proud moments: three to five, each with situation, action, change.
4. Work: case studies or projects, each with the thinking (problem, decision, trade-off, outcome), not just a picture.
5. Learning: what you are building now.
6. How you work: principles or skills, briefly.
7. Action: one clear way to reach you.

**Selling a product:**
1. Hero: what changes, for whom.
2. The problem and its daily cost.
3. How it works: the 3 core things.
4. Proof: research, prototype, early evidence.
5. Who it is for (and not for).
6. FAQ: the hard questions, honestly answered.
7. Action: one clear call to action.

Cut any section that has no real substance. A shorter honest page beats a longer padded one.

## Step 4: Build in versions

Never overwrite. Each version is a new file. The slow reveal teaches what each layer adds.

- **v1: the words.** `site-v1.html`. Approved copy in clean semantic HTML. System fonts, black on white, generous spacing. Proves the content stands on its own.
- **v2: the design.** `site-v2.html`. Layout, hierarchy, type scale, space, one accent colour. Follow `design.md` if the project has one. Alternate section backgrounds to pace the scroll. Large type for the one idea.
- **v3: the voice.** `site-v3.html`. Only if the student asks for a named voice. Run that voice skill (for example apple-brand-voice) on v2, or apply their `design.md` brand rules.

Technical rules for every version:
- One self-contained HTML file. Inline CSS and minimal inline JS. No frameworks, no external scripts.
- Works on a phone: no horizontal overflow at 375 pixels, hero fits in one to three lines.
- Readable contrast. Tap targets at least 44 pixels. Respects reduced motion.
- Real images only if the student provides them. Never fake screenshots, logos or headshots.
- Opens with a double-click. No hosting needed.

## Step 5: Check

Open it or screenshot it if tools allow. Then check:

- Is the one idea obvious in five seconds?
- Would the named audience take the action?
- Is every claim from the student's material?
- Does every section have one job?
- For a person: does it show thinking and proof, not just adjectives?
- For a product: does it start with the human, connect to a number and end with a decision?

Ask the student to read it aloud and mark anything that does not sound like them.

## Step 6: Hand over

Give the file and a short note:

| | |
|---|---|
| Selling | yourself or product |
| One idea | ... |
| Audience | ... |
| Action | ... |
| What v2 added | ... |
| What is still missing | the `[add proof]` markers, in a list |

Then one suggestion for the next version.

## Self-check

- Did I decide what I am selling and to whom before writing anything?
- Is every line backed by something real?
- Did the copy stand on its own in v1 before design was added?
- Is there exactly one action?