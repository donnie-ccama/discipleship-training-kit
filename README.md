# Discipleship training kit

Training materials for launching Christian discipleship groups (same-gender groups of 8 to 10) among the staff and volunteers of our non-profit.

## What's here

A small static website - plain HTML and one stylesheet, no build step:

- `index.html` - the model, what's in the kit, assumptions
- `pitfalls.html` - 12 common pitfalls of small discipleship groups, each with a guardrail and linked sources
- `training.html` - a six-session training plan for early adopters
- `toolkit.html` - weekly meeting rhythm, accountability questions, group covenant, case studies, facilitator checklist
- `sources.html` - the research behind the pitfalls
- `styles.css` - shared styling

## Editing

Every page is plain HTML. Text lives between tags like `<p>`, `<li>` and `<td>` - edit the words and leave the tags alone. GitHub's web editor (the pencil icon on any file) is enough for wording changes.

## Deploying on Vercel

This repo deploys as a static site with no build step:

1. In Vercel, import this repository.
2. Framework preset: **Other**. No build command, output directory `/` (the repo root).
3. Deploy - Vercel serves `index.html` and the linked pages as-is.

To use it as a section of the existing website instead of a standalone site, copy the `.html` files and `styles.css` into the main site repo (for example under `public/discipleship/` or an equivalent folder) and link to it from the site's navigation.
