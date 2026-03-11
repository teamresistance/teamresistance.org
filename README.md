# Team Resistance Site

Website for Team Resistance, built with Hugo.

## Local Development

1. Install Hugo: `brew install hugo` (macOS) or see [Hugo installation docs](https://gohugo.io/installation/)
2. Run development server: `hugo server -D`
3. View site at <http://localhost:1313>

## Building

```bash
hugo --minify
```

Output will be in the `public/` directory.

## Deployment

This site is configured for Cloudflare Pages deployment:

- **Build command**: `hugo --minify`
- **Build output directory**: `public`
- **Root directory**: `/`

## Adding Content

Create new pages in the `content/` directory:

```bash
hugo new content/page-name.md
```

Edit the markdown file and set `draft = false` when ready to publish.

## Project Structure

- `content/` -- Markdown content files
- `layouts/` -- HTML templates
- `static/` -- Static assets (CSS, images, favicon)
- `hugo.toml` -- Site configuration
