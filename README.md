# Arrentic — v1 prototype

Clickable walkthrough of the Arrentic v1 rent-collection workflow.
**Live:** https://correojuanito-del.github.io/arrentic-prototype/

Arrentic is operator judgment delivered as software for Washington property
managers. This page is a design prototype: the data is illustrative, nothing is
sent to anyone, and no legal guidance here is verified. Arrentic drafts, you decide.

## Demo switches

- `?complianceBlocked=true` — draft review in the compliance-blocked state
- `?defaultDraftTab=en` — draft review opening on the English reference tab

## About this repo

`index.html` is **generated output**, published here only so GitHub Pages can
serve it. Do not edit it. The source of truth is the private `arrentic-v1`
repository: edit `arrentic-v1.dc.html` there, run `node tools/publish.mjs`, then
commit and push from this folder.
