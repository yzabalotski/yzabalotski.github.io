---
date: '2026-07-16T00:01:43+03:00'
draft: false
title: 'How It Works'
---

Assume, you want to add a new post then you need to take next steps:
- hugo new posts/whatever.md
- fill, commit and push whatever.md to main branch (note, draft should be set to false, otherwise it wouldn't be shown)
- the hugo github workflow is triggered by the change
- the workflow builds updated html/css files and deploys them to GitHub Pages
