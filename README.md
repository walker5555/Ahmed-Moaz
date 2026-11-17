# Walker · Security Field Notes

I’m Walker, a SOC analyst focused on digital forensics and incident response (DFIR). I write about Windows endpoint investigations, how to interpret forensic artifacts, and how endpoint telemetry can support detection and incident response.

[Read the blog](https://walker5555.github.io/Ahmed-Moaz/#recent-posts) · [Medium](https://medium.com/@ahmedmoaz2003) · [LinkedIn](https://www.linkedin.com/in/ahmed-moaz11/)

## What I write about

- **Windows telemetry and detection** — Event Tracing for Windows (ETW), forensic artifacts, and ways to assess the integrity of endpoint telemetry.
- **Windows forensic artifacts** — Volume Shadow Copies, NTFS alternate data streams, and Prefetch evidence of program execution.
- **Investigation write-ups** — Case-driven notes on examining Windows systems and interpreting the evidence.

## Add a post

Create `_posts/YYYY-MM-DD-your-title.md` for a post hosted on the site. The filename supplies the publication date. The homepage lists posts together under **Blog posts**.

```markdown
---
title: "Your article title"
description: "A short summary for the homepage."
---

Write your article here in Markdown.
```

To list a Medium article, add its title, original publication date, URL, and short summary to `medium_articles` in `index.html`.

## Publish

GitHub Pages builds the Jekyll site from `main` at `/(root)`. Commit changes to `main` to update the site.
