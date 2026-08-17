# Chronicles of Nihiloros — DM Campaign Tool

A single-file DM screen for the Chronicles of Nihiloros campaign, hosted on GitHub Pages
so that YouTube ambience links and embeds work (they don't from a `file://` page).

## Editing

`index.html` is the whole thing. Edit it, then:

```bash
git add -A && git commit -m "Session 13 prep" && git push
```

The live site updates about a minute after the push.

## Notes

- Every session's prep is a commit, so the full history is browsable under the repo's
  Commits tab, and any past version can be restored.
- Local preview: open `index.html` in a browser directly, or run
  `python3 -m http.server 8000` in this folder and visit http://localhost:8000.
