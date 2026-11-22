# The Design Audit

You do the thinking. Claude does the lifting.

Claude prepares the findings, asks the questions one at a time, records your answers, and makes the changes. Your job is to judge, in plain words.

The audit works on the student's own prototype or on an existing product. In a short session, audit the prototype. Audit an existing product later.

## Step 1: Set the target and the level

Ask two things.

1. **What are we auditing?** A file, a link, or a product name.
2. **At what level?** The student picks one. Do not pick for them.

| Level | What you are looking at | Looks means | Works means | Hooks means |
|---|---|---|---|---|
| **Screen** | One view | Hierarchy, grouping, contrast, clarity | Can I find and do the one thing here | How I feel looking at it |
| **Workflow** | One task across screens | Does the look stay consistent step to step | Can I finish the task without getting lost | Where my confidence rises or drops |
| **Feature** | One capability, start to end | Does it look like it belongs | Does it earn its place and do its job | Would I choose to use it again |
| **Product** | The whole thing | Does it look like what it promises | Does it deliver the promise in the Problem Statement | Do I trust it. Do I come back |
| **Business** | Model, price, who pays | How the offer is presented | Does the value exchange hold, is the cost of paying worth it | Why I stay, why I leave, what I tell others |

Then say it back: "We are auditing [what] at [level] as [the person in the Desire Profile]." Wait for a yes.

## Step 2: Claude prepares

Before asking anything, Claude looks at the target as the person in the Desire Profile would. For a prototype, open the HTML and read it, or take a screenshot if a browser is available. For an existing product, ask the student for screenshots or a link.

Claude quietly lists candidate issues for each lens, using `ref/audit-questions.md`. The student does not see a long list. They see one question at a time.

## Step 3: Ask, record, change

Run the three lenses in order: Looks, Works, Hooks. For every question, follow the same four moves.

1. **Ask** one question, in plain words. Point to the exact moment. Give your own read in one line so the student can agree or push back.
2. **Record** the student's answer in their words. Add a rating:
   - **RED.** Broken. It stops the person finishing.
   - **AMBER.** Weak. It creates friction. They can work around it.
   - **GREEN.** Working. Say why, so it is kept.
3. **Propose** one change if it is RED or AMBER. One line. Ask yes or no.
4. **Change** it on a yes. For a prototype, save a new version (`name-v2.html`) and never overwrite. For an existing product, write the change as a recommendation only.

Then ask the next question. Do not stack questions.

| Lens | Based on | Questions to ask |
|---|---|---|
| **Looks** (sensory, what the eye does) | Visual perception and Nielsen heuristics 4, 6, 8 | 3 to 4 |
| **Works** (cognitive, what the mind does) | Cognitive principles and Nielsen heuristics 1, 2, 3, 5, 7, 9, 10 | 4 to 5 |
| **Hooks** (reflective, what the person feels and means) | The Hooks interview questions | 5 to 7 |

About fifteen questions in all. At least five rated findings.

## Step 4: One recommendation

Not a wishlist. Pick the one change that most improves the value exchange. Specific enough that a designer could act on it on Monday morning. Name the finding it answers.

## Output: `audit.md`

Header: target, level, person.

| # | Lens | Moment | Question | Student's answer | Rating | Change made |
|---|---|---|---|---|---|---|
| 1 | | | | | | |

**Recommendation:** [one change, and which finding it answers]

## Gate

- The student set the level.
- Every finding names a specific moment.
- Every answer is the student's own words.
- A product manager could raise any finding in a review today.
- The recommendation is one change, not a list.

## Save and hand off

Save `audit.md`. Add three lines to `intent.md`: target and level, the top finding, the recommendation. Then suggest `value-communication`.
