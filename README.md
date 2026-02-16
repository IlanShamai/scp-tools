# SCP Tools

Interactive study aids for SCP shiurim — צ״ד (Dairy Ladle in Meat Pot)

## Tools

- **Siman 94 — Ladle & Pot**: Interactive Sugya on Shulchan Aruch vs. Rama regarding ladles and pots
- **Siman 96 — Davar Charif**: Study aid for cutting sharp foods with meat or dairy knives

## GitHub Pages

This site is built with [Jekyll](https://jekyllrb.com/) and deploys automatically to GitHub Pages.

### Local development

Requires Ruby 3.0+.

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000. GitHub Pages builds automatically on push using its own environment.

### Deployment

- **GitHub Pages**: Enable Pages in repo settings (Source: Deploy from a branch). Jekyll builds automatically.
- **Netlify**: Configured in `netlify.toml` — runs `bundle exec jekyll build` and publishes `_site`.
