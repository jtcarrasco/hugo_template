# hugo_template

Hugo static site template with minimal custom layouts and demo content.

## Stack

- Hugo (latest)
- No external theme — layouts are in `layouts/`
- Markdown content

## Commands

```bash
hugo server -D     # Dev server at http://localhost:1313 (-D includes drafts)
hugo build         # Build to public/
hugo new posts/my-post.md   # Create new post
```

## Structure

- `content/` — Markdown content (mirrors URL structure)
- `layouts/` — Go HTML templates
- `static/` — Static assets (CSS, images, JS)
- `hugo.toml` — Site config

## Adding a Post

```bash
hugo new posts/my-post.md
```

Edit `content/posts/my-post.md` and set `draft: false` to publish.
