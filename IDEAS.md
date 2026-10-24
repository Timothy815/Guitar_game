# Ideas for Guitar Game

Suggestions for making the site more fun and more useful, most valuable first.
Nothing here is scheduled yet.

Current state: Fretline has no sound, Flashcards does, and neither one listens to the guitar.

## Biggest wins

1. **Play the answer on your real guitar.** Use the microphone to detect which note is played. Instead of tapping the screen or typing a letter, you play the note and the game checks it. Works in both tools. Main challenges: noisy rooms and out-of-tune strings.
2. **Sound and ear training in Fretline.** Play each note when it lights up, and play both notes of an interval. Add an ear-training mode: hear a note or interval and find it on the neck without seeing its name.
3. **A shared home screen.** Both tools save their stats on the same site, so the launcher can read both. Show a combined daily goal and practice streak (e.g., "practiced 6 days in a row"), plus the weakest notes from both tools, like "slow on F# on the G string."

## More useful

4. **Install it like an app.** Add to a phone or iPad home screen; works offline in full screen.
5. **Back up your progress.** Stats live only in one browser on one device, so clearing browser data erases them. An export/import button protects history and moves it between devices.
6. **Weak spots carry over between tools.** Notes missed in Flashcards get extra practice in Fretline, and the reverse.
7. **Match the settings.** Fretline has 3 tunings and Flashcards has 2 (Standard, Drop D); share one tuning setting. Add a left-handed fretboard option to both.

## More fun

8. **Daily challenge.** One round per day that's the same for everyone, with a shareable score like Wordle's (e.g., "Fretline #42: 18/20, 1.4s avg").
9. **Badges and milestones**, such as "whole neck unlocked," "100 correct under 1 second," or "7-day streak."
10. **New drills on the same fretboard:** chord tones (find the 3rd of A), triad shapes, scale patterns, or a "key of the day" mode.

## Practical note

Each tool is a single exported bundle file, not regular source code. Additions that live in the launcher (`index.html`), like the home screen, backups and app install, are easy and don't touch the tools. Deeper changes, like adding the microphone or sound to Fretline, mean editing inside the bundles; changing the original projects and re-exporting would be cleaner.

**Suggested order:** #3 and #5 first (quick and safe), then #1 (biggest change to the experience).
