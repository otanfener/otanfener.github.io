# ozantanfener.com

Personal website built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Development

```bash
# Start local development server
hugo server -D

# Build for production
hugo --minify
```

Visit http://localhost:1313/ to preview your site locally.

## Content Structure

```
content/
├── _index.md        # Home page
├── posts/           # Blog posts
└── about/           # About section
```

## Creating New Content

```bash
# Create a new blog post
hugo new posts/my-post.md
```

## Deployment

This site automatically deploys to GitHub Pages via GitHub Actions when you push to the `main` branch.

## Theme

Using [PaperMod](https://github.com/adityatelange/hugo-PaperMod) - a clean, fast, and feature-rich Hugo theme.

Configuration in `hugo.toml`.
