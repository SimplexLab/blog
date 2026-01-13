# AI Research Blog

A personal blog about AI research and ML theory, built with Jekyll and deployed via GitHub Pages.

## Local Development

### Prerequisites

- Ruby 3.x
- Bundler (`gem install bundler`)

### Setup

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve
```

Visit `http://localhost:4000/blog/` in your browser.

### Live reload

```bash
bundle exec jekyll serve --livereload
```

## Writing Posts

Create new posts in the `_posts/` directory with the naming convention:

```
YYYY-MM-DD-title-of-post.md
```

Each post needs front matter:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
categories: category1 category2
---

Your content here...
```

## Deployment

The blog is automatically deployed to GitHub Pages when you push to the `main` branch.

### First-time Setup

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under "Build and deployment", select **GitHub Actions** as the source
4. The workflow will automatically build and deploy on push to `main`

Your blog will be available at: `https://<username>.github.io/blog/`

## Configuration

Edit `_config.yml` to customize:

- `title`: Your blog's name
- `description`: Blog description for SEO
- `author`: Your name
- `url`: Your GitHub Pages URL (update `YOUR_GITHUB_USERNAME`)
- `baseurl`: Repository name (default: `/blog`)

## License

MIT
