# Ahmed Moaz · Security Field Notes

Jekyll blog for GitHub Pages.

## Publish

Put these files in the root of the repository's `main` branch. Under **Settings → Pages**, set **Deploy from a branch**, select `main` and `/(root)`, then save.

## Add a post

Create `_posts/YYYY-MM-DD-your-title.md`. Use `dfir`, `threat-analysis`, or `soc` as a category. The file date controls ordering, and the homepage updates after deployment.

```markdown
---
title: "Your article title"
description: "A short summary for the homepage."
categories: [dfir]
---

Write your article here in Markdown.
```
