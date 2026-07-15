---
date: '2026-07-16T00:01:43+03:00'
draft: false
title: 'How It Works'
summary: 'The steps to add a new post and how it gets built and deployed to GitHub Pages.'
---

Assume, you want to add a new post then you need to take next steps:

1. `hugo new posts/whatever.md`
2. Fill, commit and push `whatever.md` to the main branch (note, `draft` should be set to `false`, otherwise it wouldn't be shown).
3. The Hugo GitHub workflow is triggered by the change.
4. The workflow builds updated HTML/CSS files and deploys them to GitHub Pages.
