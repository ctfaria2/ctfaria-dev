# ctfaria.dev

Personal website and blog built with Hugo.

## Stack

- [Hugo](https://gohugo.io/) static site generator
- [Archie](https://github.com/athul/archie) theme
- GitHub Pages (auto-deploy on push to `main`)

## Local development

```bash
# Start dev server with drafts
hugo server -D

# Build to ./public
hugo
```

## Linting

```bash
npm install        # First time only
npm run lint       # Check markdown
npm run lint:fix   # Auto-fix issues
```

## Creating content

```bash
# New post
hugo new posts/YYYY-MM-DD-title.md
```

Posts live in `content/posts/`. Front matter uses YAML:

```yaml
---
title: "Post Title"
date: 2026-01-28
draft: false
description: "Short description"
---
```

## Deployment

Push to `main` triggers GitHub Actions which builds and deploys to GitHub Pages.

## License

Content is personal. Theme is MIT licensed.
