# Matteo Saporiti — personal site

A multi-page site — no build tools, no dependencies.

## Files

- `index.html` — home page, 4 category cards
- `essays.html` — list of essays
- `code.html` — list of code projects
- `websites.html` — list of websites
- `other.html` — list of anything else
- `styles.css` — shared styling for all pages

## Adding an item to a category

1. Open the relevant page (e.g. `essays.html`) on GitHub
2. Click the pencil icon to edit
3. Find the `<!-- TEMPLATE ... -->` comment near the top of the `<section class="list">` block — it shows you exactly what to paste
4. Copy that block, fill in the title, description, link, and year
5. Paste it right above `</section>` (and above the "No essays uploaded yet" line — you can delete that empty-state line once you have at least one item)
6. Commit changes — live in about a minute

Example of a finished item:

```html
<a class="list-item" href="https://link-to-your-essay.com">
  <h3>My essay title</h3>
  <p>A short description of what it's about.</p>
  <div class="year">2026</div>
</a>
```

Links now open in the same tab — clicking an item or "Back home" replaces the current page rather than opening a new one.

## Uploading files to link to

If an essay or project doesn't live elsewhere online, you can upload it directly to the repo (e.g. `my-essay.pdf`) and link to it as `href="my-essay.pdf"`.

## Getting it live on GitHub Pages

1. Repo must be named `mattesapo20-hub.github.io`
2. All these files go in the root of that repo (not in a subfolder)
3. Settings → Pages → Source: Deploy from a branch → main → / (root)
4. Site is live at `https://mattesapo20-hub.github.io`
