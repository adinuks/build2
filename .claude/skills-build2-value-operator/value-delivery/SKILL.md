---
name: value-delivery
description: Takes a concept to something a real person can use and judge. Builds a clickable HTML prototype (narrate the flow, structure, behaviour, look), iterates one precise change at a time, and audits a prototype or an existing product at the level the student sets (screen, workflow, feature, product, business) with Looks, Works and Hooks, using Nielsen heuristics and perception principles, rated red, amber and green. Use whenever someone wants to build, prototype, mock up, tweak, review or audit a product or screen, says "make this real", "build the flow", "is this any good", "what is broken here", or "audit this app". Use ui-design-system for the look. Run after value-creation.
---

# Value Delivery

Delivery makes the thinking tangible and testable. A prototype is a question, not an answer. Fidelity is not the point. Clarity is. If the student cannot narrate the flow, they are not ready to build.

## What do you want to achieve?

| I want to... | Do this | Read |
|---|---|---|
| Build a prototype of my concept | Narrate the flow, build v1 structure, v2 behaviour, v3 look, review | `ref/prototype.md` |
| Make it look clean and professional | Use the `ui-design-system` skill for tokens and components | the `ui-design-system` skill |
| Change one thing precisely | One named element, one token step, a new version | `ui-design-system`, `ref/iterate.md` |
| Audit my prototype or an existing product | Set the level, then Claude asks, records and changes: Looks, Works, Hooks, rated, one recommendation | `ref/audit.md`, `ref/audit-questions.md` |

## Rules for every mode

- **Narrate before you build.** Write the journey in plain words first: *They open the product and see ___. They tap ___ and get to ___. They do ___ and the product responds with ___. They leave feeling ___.*
- **Three screens at least,** from the problem moment to the resolution moment. No decoration. Someone should be able to use it without you explaining it.
- **Review against the Desire Profile, not personal taste.** Before sharing, ask: Does this solve the Problem Statement? Would the specific person in the Desire Profile actually use it? What is the one thing that feels wrong?
- **One change at a time.** Fix the one thing that feels wrong. One precise change beats ten vague ones.
- **New version every time.** `name-v1.html`, `name-v2.html`. Never overwrite.
- **Nothing invented.** Real copy and numbers from the student. Missing facts get a visible `[add number]`.
- Plain language. Short sentences. No em dashes.

## Gate before moving on

- Someone who has never heard of the concept can look at it and understand what it does.
- There is a clear moment where the problem gets resolved. If it cannot be found, the concept is not ready.
- The three review questions are answered in one short paragraph.

## Save and hand off

Write `prototype-notes.md` next to the HTML files, and `audit.md` if an audit was run. Add a three-line summary to `intent.md`: the prototype file, the resolution moment, the one change made. Then suggest `value-communication`.
