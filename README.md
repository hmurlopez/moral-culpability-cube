# The Moral Culpability Cube

A private, browser-based **reflection tool** for honest self-examination.

Not all wrongs weigh the same. The same act can sit anywhere from a passing
failing to a grave betrayal — it depends on **what you intended**, **what you
did**, and **who you owed**. This tool helps you locate something on your
conscience along those three axes, understand *why* it weighs what it does, and
think concretely about doing better.

## How it works

1. **Three guided questions** translate plain-language answers into a position
   on the cube:
   - **Agency (Y)** — your will: *Premeditated → Impulsive → Negligent → Accidental*
   - **Cause (X)** — your hand: *Direct cause → Facilitated → Failed to prevent → Failed to perceive*
   - **Relationship (Z)** — your bond: *Sworn duty → Natural bond → Incidental → Stranger*
2. Your three answers land you on **one of 64 cells**, each with a culpability
   **score from 0 (least) to 9 (most)**.
3. You get a **reckoning** (which axis drove the weight up or down), **growth
   prompts** toward doing better, and a space for **private reflection**.
4. You can **see your cell glow** on the interactive 3D cube (drag to rotate,
   pinch/scroll to zoom, explode to spread the cells apart).

## Two framings

A toggle on the home screen switches between:

- **Scriptural** — an examination of conscience drawing on the Hebrew and
  Christian scriptures the framework grows from (Ezekiel's watchman, the laws of
  Exodus, the Good Samaritan, the Psalms of self-searching).
- **Universal** — the same moral framework with the scripture hidden, for any
  user regardless of faith.

## Privacy

Everything stays **in your browser, on your device** (`localStorage`). There is
no account, no server, and nothing is ever sent anywhere. Clearing your browser
data erases your saved reflections.

## Running it

It's a single self-contained file — just open `index.html` in any modern
browser. The only external dependencies (three.js, web fonts) load from CDNs,
so an internet connection is needed for the 3D view and typography.

To publish it for others, enable **GitHub Pages** on this repository (Settings →
Pages → deploy from the default branch); the tool will be served at the Pages
URL with no build step.

## A note on intent

This cube measures **culpability, not the worth of a person**. The lightest cell
still asks something of us; the heaviest still leaves room to turn back. It is a
mirror for reflection — not a verdict.
