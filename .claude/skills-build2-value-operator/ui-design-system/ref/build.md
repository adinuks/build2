# How to design the build

Good UI starts with a decision, not a colour. Five lines of planning save five rounds of fixing.

## Step 1: the brief (ask, then write it back)

1. **Who is it for?** One person, in a few words. ("A busy sales manager.")
2. **What is the one job of this screen?** ("See which deals need attention today.")
3. **What is the one action they take?** ("Open a deal.") This becomes the single primary button or main link.
4. **What do they need to see?** Three to five things, in order of importance.
5. **What should it feel like?** Three words. Default: calm, sharp, confident.

Write the brief back in five lines. Wait for a yes or a correction. If the user does not know an answer, suggest one and ask them to confirm.

## Step 2: pick a recipe

Choose from `ref/recipes.md`: landing page, dashboard, form, list and detail, or settings. Say which one and why in one sentence.

## Step 3: build in this order

1. **Structure.** Sections and layout with real words, no styling beyond the tokens. Check the order matches the brief's "what they need to see".
2. **Content.** Real copy and real numbers from the user. No lorem ipsum. If you lack a fact, leave a visible `[add number]`.
3. **Style with tokens.** Use components from `assets/components.css`. Page CSS only arranges things (grid, spacing) using tokens.
4. **States.** Hover, focus, empty, error. Every button and input needs them.
5. **Mobile.** Check at 390px wide. Nothing should scroll sideways.

## Step 4: show and ask

Save as `name-v1.html`. Run `ref/checklist.md`. Report in the closing format from SKILL.md. Open a screenshot if the tools allow, so the user judges with their eyes.

## Hierarchy in one idea

Every screen needs one thing the eye lands on first, a second thing next, and everything else quiet. You make hierarchy with size, weight and space, not with more colour. If three things shout, none of them is heard.
