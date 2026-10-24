# Guitar Game

Two guitar practice tools in one site, with a tab bar to switch between them.

**Live:** https://timothy815.github.io/Guitar_game/

- **Fretline** (`fretline.html`): fretboard note-finding game
- **Chromatic Flashcards** (`flashcards.html`): chromatic note flashcards

`index.html` is the launcher. Each tool runs in its own iframe and stays loaded,
so switching tabs (or pressing Alt+1 / Alt+2) keeps your place in both.
Links like `.../#flashcards` open a specific tool directly.

To add or update a tool, drop its HTML file in the repo root and add a tab + iframe in `index.html`.
