# How to iterate and tweak with precision

## The loop

1. **Look.** Open the current version. Squint at it. What is the first thing you see? Is it the right thing?
2. **Name one problem.** One. Not "make it better".
3. **Say it precisely.** Use the formula below.
4. **Build the next version.** `name-v2.html`. The old one stays.
5. **Compare.** Open v1 and v2 side by side. Keep the better one. Go again.

Small steps win. Ten tiny changes, each judged, beat one giant redo that nobody can judge.

## The formula for a precise tweak

**Where + what + which direction + how much.**

- "On the hero, make the headline one size smaller (`--text-2xl`)."
- "Between the cards, increase the space one step (`--space-5` to `--space-6`)."
- "The Send button label should be sentence case."
- "The table rows feel tight. Add one step of padding."

"How much" is always one step on a scale. One step is small enough to see and big enough to matter. If it is not enough, take another step.

## The five knobs

| Knob | Token family | Turn it when |
|---|---|---|
| Space | `--space-*` | it feels cramped or loose |
| Size | `--text-*` | the order of importance is unclear |
| Weight | `--weight-*` | headings do not stand out from body |
| Colour | `--text-2`, `--accent` | the eye goes to the wrong place |
| Shape | `--radius-*` | it feels too sharp or too soft |

## Translate how it feels into a knob

| You feel | Try |
|---|---|
| Cramped, busy | more space, one step up |
| Plain, flat | bigger gap in size between heading and body |
| Not premium | fewer colours, more space, smaller body text, tighter big headings |
| Everything shouts | make secondary text `--text-2`, remove one orange thing |
| Hard to read | raise body text colour to `--text`, check contrast |
| Eye lands in the wrong place | make the right thing bigger or orange, the wrong thing quieter |

## Global versus local

- Change a **token** when you want every page to change (all cards get rounder).
- Change a **class or one element** when you want only that thing to change (this card only).
Ask yourself: "Do I want this everywhere?" If yes, token. If no, that element.

## When Claude goes off track

Say it plainly and point to the rule:
- "Use tokens only. Replace the raw colour with a token."
- "That adds a second accent colour. Keep one orange."
- "Change only the hero. Leave the rest as it was."
- "Go back to v2 and make just this one change."
