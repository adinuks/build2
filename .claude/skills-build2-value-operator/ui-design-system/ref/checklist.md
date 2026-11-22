# Check before you show

Run all ten. Fix what fails. Then report in three lines: what passed, what you fixed, what to look at.

1. **One job.** Can you say what this screen is for in one sentence?
2. **One primary button.** Exactly one orange button on the screen.
3. **Squint test.** Blur your eyes. The first thing that stands out should be the most important thing.
4. **Orange count.** Orange appears in a few small places, not as big areas.
5. **Four sizes at most.** No more than four different text sizes on the screen.
6. **Tokens only.** In the page's own CSS, no hex colours and no raw pixel values for space, size or radius. Everything is a token.
7. **Contrast.** Body text is `--text` or `--text-2`. Captions are never lighter than `--text-3`. Orange text on white is `--accent-ink`. Text on orange is black.
8. **States.** Every button and input has hover and focus. Forms show an error state. Lists and tables show an empty state.
9. **Phone.** At 390px wide, nothing scrolls sideways and buttons are at least 44px tall.
10. **Real words.** No lorem ipsum, no "Click here". Buttons say what happens ("Send message").

## Report format

> **Checked:** 10 of 10 passed. (or: 8 of 10. Fixed 6 and 8.)
> **Fixed:** the second orange button is now secondary.
> **Look at:** the table on a phone.
