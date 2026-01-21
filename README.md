# Hugo's Website

Live at: https://flugan42.github.io/hugos-website/

## Adding a new post

1. Create a file in `_posts/` named `YYYY-MM-DD-title.md`

2. Add front matter at the top:
   ```yaml
   ---
   layout: post
   title: Your Title
   ---
   ```

3. Write content using:
   - Markdown for formatting
   - `$...$` for inline math, `$$...$$` for display math
   - `[^1]` for footnotes (define at bottom with `[^1]: Footnote text`)

4. Publish:
   ```bash
   git add . && git commit -m "Add post title" && git push
   ```

Site rebuilds automatically in ~30 seconds.

## Reference

See `_posts/2026-01-20-example-post.md` for syntax examples (hidden from site with `published: false`).
