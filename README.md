# lab

Micro app concepts by [Martin Etchegaray](https://martinetchegaray.com). Each folder is one project, published with GitHub Pages.

## Projects

### AI Access Panel

A look under the hood of a concept micro app. On the surface, AI Access Panel is a single web page showing whether AI systems are allowed to read public posts on LinkedIn, Reddit, YouTube, X, Instagram and Facebook. Underneath, it's a process: public sources are read, checked and recorded, then shown on the page and passed on to other systems, such as a content calendar or an AI agent. The page lays that process out part by part, and shows the page itself. The app isn't built yet.

- Page: https://martin-wrtr.github.io/lab/ai-access-panel/
- Embed version: https://martin-wrtr.github.io/lab/ai-access-panel/embed.html

The statuses shown are sample data, not live checks.

## Files

```
ai-access-panel/
  index.html   full page
  embed.html   version for embedding in another site
```

Each page is a single HTML file with no build step. Fonts load from Google Fonts.
