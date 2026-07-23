# Surf Prep Tracker

A simple, single-page training tracker for a 12-week home workout program built around resistance bands and bodyweight exercises — designed to build the strength, mobility, and conditioning needed to learn to surf.

**Live app:** https://brotheranderson.github.io/surf-prep-tracker/

## What it does

- Walks through a 12-week, 4-day-a-week program (48 sessions total), one session at a time
- Automatically loads the next session once you mark the current one complete
- Supports a "Minimum Viable Day" (MVD) mode — a reduced version of each session for low-motivation or low-time days, so a bad day becomes a short session instead of a skipped one
- Built-in Exercise Guide with plain-language descriptions of every movement in the program
- Lets you jump to any week/day manually, or reset progress entirely
- Keeps a running history log of completed sessions

## How it works

This is a single self-contained `index.html` file — no build process, no external dependencies, no backend. It's plain HTML, CSS, and JavaScript. Progress is saved locally in the browser using `localStorage`, so it persists on whichever device/browser you're using it from, but doesn't sync across devices.

## Usage

Open the live link above on your phone and use **Add to Home Screen** in Safari for an app-like experience. No installation needed.

## Status

This is a personal training tool, built for one person's specific program. Feel free to fork it and adapt the exercise list, phases, or styling to your own program if it's useful as a starting point.

## License

See [LICENSE](./LICENSE.md).
