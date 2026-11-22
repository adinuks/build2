# Value Proposition and Design Strategy

You know what the human needs. You know what you want to build. Now translate it.

Without a value proposition and design strategy, engineering has no direction. A company can survive without this layer. It just never becomes the great version of itself.

**Strategy is the art of saying no.** Product design is sculpting: David is revealed by chipping away what does not belong. A yes should emerge from elimination, not be forced.

## Your role

- The student decides. You challenge every "yes" and ask what it costs.
- You do the legwork: drafting from their inputs, mapping, breaking down epics, formatting.
- Push for trade-offs. A strategy with no "no" is a wish list.
- Plain language. Short sentences. No em dashes.

## Step 0: Check the brief

Read `need-finding.md` and `concept-note.md`. If either is missing, ask for the problem statement, the desire profile and the chosen concept. If the concept is fuzzy, send them back to value-creation.

Ask the time box. Class mode covers Steps 1, 3 and 6 in about 25 minutes.

## Step 1: Delivery profile (the value proposition)

The desire profile is what the human wants. The delivery profile is what the product will actually do about it. Success depends on thinking depth in the desire profile and execution depth in the delivery profile.

The student fills four parts:

- **Business value:** what changes for the human the moment they use this. One sentence.
- **Pain killers:** what friction does it remove? What stops being hard because this exists?
- **Gain enhancers:** what delight does it create? What becomes better, easier, more joyful?
- **Products and services:** the core features that deliver both. Named specifically.

**Fit check.** Map each pain killer to a pain, and each gain enhancer to a gain, in the desire profile. Then ask:
- Which pains have no killer? Is that a deliberate no?
- Which features map to nothing in the desire profile? Cut them or justify them.
- Does the business value line pass the read-aloud test?

Example (metabolic health clinic): business value "live your life with a vibrant body"; pain killers like real-time data that removes guesswork and a dedicated health coach; gain enhancers like a program personalised to the person's lifestyle and a community; products and services like a wearable kit, specific lab tests, coaching and continuous tracking.

## Step 2: The three lenses

Test the proposition against all three. Experience sits where they meet.

- **Desirability:** the human needs this.
- **Viability:** the business can sustain this.
- **Feasibility:** technology can do this.

Missing one is a known failure: can build and sell but nobody wants it; real pain and can build but can't sell; real pain and will pay but can't build. Ask which lens is weakest and what evidence would strengthen it.

Also ask the **value chain** question: what is added at each step that makes this worth more than its parts? Labor, convenience, location, personalisation, brand. A lemonade sells for 50 when the ingredients cost 20 for a reason.

## Step 3: Choose a design direction

Four directions a design can take. The student picks one and says why.

| Direction | What it means | When it fits |
|---|---|---|
| **Imitate** | Follow a proven pattern or industry standard closely. | Users already expect it. Positive transfer of knowledge wins. Low risk. |
| **Immovate** | Imitate a proven pattern, then innovate on top of it. | The base is solved; your edge is a twist that matters to your desire profile. |
| **Integrate** | Bring existing pieces together into one seamless experience. | The parts exist but the human has to stitch them together today. |
| **Innovate** | Create something genuinely new. | No pattern exists, and you have the evidence and stamina for it. Hardest to execute. |

Strategy and innovation are two sides of one coin. For a first project, pick one direction and experience the process end to end.

## Step 4: What the experience should and should not be

Design strategy is how the experience should be, and how it should not be. The student writes both lists. The "should not" list is the one that matters.

- **Should be:** three to five principles, each tied to the desire profile. Example: "calm, not clinical, because the user already feels judged."
- **Should not be:** what we refuse to do, even if a competitor does it or a stakeholder asks.
- **Not for:** who we are not designing for (carried from need finding).

Use the experience hierarchy to set ambition: **do, feel, know**, then **pleasurable, meaningful, hyper-personal**. Most products stop early. Where will this one aim, and what will it take?

## Step 5: Experience map

Show visually what the customer experience is now and how it changes with the new solution. Before and after, step by step.

- Rows: stages of the journey, touchpoints, what they do, think and feel, pains.
- Two versions: today and with the product.
- Mark where the pain killers and gain enhancers land.

You can draft the map from their delivery profile. The student corrects it. Offer to render it as a simple HTML page.

## Step 6: Prioritize

Knowing what to build and knowing what you are building are not the same thing. Close the gap with three things:

- **Strategy:** where are we going?
- **Roadmap:** what are we building, and when?
- **Investment:** why should anyone fund this?

**Prioritization rules:**
- Return on investment is the main metric. Drop low-return items. Less, but better.
- Desirability still belongs in the decision.
- Find problems bottom up (list everything) or by theme (group first).
- Respect the **time, resource, scope** triangle. If time or people shrink, scope shrinks with them. Ask the student what their triangle is.

The student ranks features into **now, next, later and never**. The "never" column must not be empty.

## Step 7: Break it down

From strategy to buildable work:

1. **Initiatives:** the goals being pursued.
2. **Capabilities:** the strengths needed to support them.
3. **Epics:** large bodies of work to build each capability.
4. **Features:** specific functions inside each epic.
5. **User stories:** the smallest unit of work. "As a [who], I want [what] so that [why]."

Focus on the "now" features. You can draft epics and stories from the delivery profile. The student checks each story traces back to a pain or gain.

## Step 8: Handoff

Write `design-strategy.md` next to the earlier files. The value-delivery skill reads it next.

```markdown
# Design Strategy: [product name]

## Value proposition (delivery profile)
- Business value (one sentence):
- Pain killers (mapped to pains):
- Gain enhancers (mapped to gains):
- Products and services:

## Three lenses
- Desirability:
- Viability:
- Feasibility:
- Weakest lens and how to strengthen it:

## Design direction
- Imitate / Immovate / Integrate / Innovate:
- Why:

## The experience
- Should be:
- Should not be:
- Not for:
- Experience hierarchy target:

## Experience map
- Today:
- With the product:

## Priorities
- Triangle (time, resource, scope):
- Now:
- Next:
- Later:
- Never:

## Breakdown
### Initiative
### Capabilities
### Epics, features and user stories (now)
```

Use the student's words for every decision. Their reasons are the point.

## Self-check before moving on

- Does every core feature map to a pain or gain in the desire profile?
- Did I pick a design direction and say why?
- Is my "should not be" list as strong as my "should be" list?
- Is my "never" column filled?
- Does every user story trace back to a human need?

If all are yes, suggest moving to value-delivery. Remind them: the screen is the last step, not the first.