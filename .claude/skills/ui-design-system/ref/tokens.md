# The tokens in plain words

A token is a named value. Change it once in `assets/tokens.css` and the whole page follows. Pages never use raw values, only token names.

## Colour (3 ideas: black, white, one orange)

| Token | Use it for |
|---|---|
| `--bg` | the page |
| `--surface`, `--surface-2` | cards and hover fills |
| `--line` | thin borders. `--line-strong` for emphasis |
| `--text` | headings and body |
| `--text-2` | supporting text. `--text-3` for captions (the lightest grey allowed) |
| `--accent` | the orange fill. Text on it is `--on-accent` (black) |
| `--accent-ink` | orange used as text on white |
| `--accent-soft` | pale orange wash for notes and selected rows |
| `--success`, `--danger` | status only, never decoration |

**Orange rules.** Orange is a pointer, not a paint. It marks the one thing to do, a small status, or a small detail. If more than about a tenth of the screen is orange, remove some.
**Why black on orange.** White text on this orange is too faint to read comfortably (contrast 3.1 to 1). Black passes (6.4 to 1).

## Type

One family (Hanken Grotesk) plus a mono for labels and numbers. Eight sizes cover everything: `--text-xs` 12, `--text-sm` 14, `--text-base` 16, `--text-lg` 20, `--text-xl` 24, `--text-2xl` 32, `--text-3xl` 48, and `--text-4xl` 64 for desktop heroes only. Use at most four different sizes on one screen. Big headings get tight tracking (`--tracking-tight`). Small uppercase labels get wide tracking (`--tracking-label`).

## Space

Steps of 4: `--space-1` 4, `-2` 8, `-3` 12, `-4` 16, `-5` 24, `-6` 32, `-7` 48, `-8` 64, `-9` 96. Related things sit close (`-2`, `-3`). Separate groups with `-5` or `-6`. Separate sections with `-8` or `-9`.

## Shape and depth

Radius: `--radius-sm` for inputs, `--radius-md` for buttons and cards, `--radius-lg` for big panels, `--radius-pill` for badges. Shadows are rare: `--shadow-1` barely there, `--shadow-2` on hover only.

## Dark mode

Add `data-theme="dark"` to `<html>`. Every token already has a dark value, so nothing else changes.

## Change the accent

Change four tokens together: `--accent`, `--accent-hover`, `--accent-ink`, `--accent-soft` (and the dark values). Then check contrast: `--on-accent` on `--accent` needs 4.5 to 1 or better, and `--accent-ink` on white needs 4.5 to 1.
