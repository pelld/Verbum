# Verbum

A small, mobile-first vocabulary trainer for English, French and Spanish.

## What it does

- Shows one word at a time with the definition hidden initially.
- Uses advanced English vocabulary and intermediate/upper-intermediate French and Spanish.
- Lets the learner rate each word: **Didn't know**, **Nearly**, or **Knew it**.
- Stores progress locally in the browser; no account or backend required.
- Brings weaker words back sooner using simple spaced repetition.
- Occasionally reverses the prompt so the learner must recall the word from its definition.
- Includes a compact recent-word history and counts learned/due words.

## GitHub Pages

This site is deliberately a single `index.html`, so deployment is simple. Enable GitHub Pages from the `main` branch and `/(root)` in **Settings → Pages**.

The site will then be available at `https://pelld.github.io/Verbum/`.

Progress is stored using `localStorage`, so it stays on the same browser/device but does not automatically sync between devices.
