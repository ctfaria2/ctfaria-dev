# CLAUDE.md

Personal website and blog for ctfaria.dev built with Hugo.

## Stack
- **Hugo** static site generator (v0.154.5 in CI)
- **Theme**: Archie (git submodule in `themes/archie`)
- **Deploy**: GitHub Pages via Actions on push to `main`

## Commands
```bash
hugo server -D    # Local dev server with drafts
hugo              # Build to ./public
```

## Content
- Posts: `content/posts/*.md`
- Pages: `content/*.md` (e.g., about.md)
- Front matter uses TOML (`+++`) or YAML (`---`)

## Config
- `hugo.toml` - site config, menu, social links
- Theme supports `auto`, `light`, `dark` modes via `params.mode`

## Deploy
Push to `main` triggers `.github/workflows/hugo.yml` which builds and deploys to GitHub Pages.
