# Battle Traits Reference

Upload this whole folder to GitHub Pages.

## Important files
- `index.html` = main page only
- `assets/css/styles.css` = shared design for every page
- `traits/stormy-seas/index.html` = full Stormy Seas page
- `traits/_template/index.html` = copy this for a new trait page
- `images/stormy-seas/cards/` = Stormy Seas card images

## Add a new trait
1. Copy `traits/_template/`.
2. Rename the copied folder, for example `traits/star-shift/`.
3. Edit `traits/star-shift/index.html`.
4. Add this link card to `index.html`:

<a class="trait-card" href="./traits/star-shift/index.html">
  <span class="trait-name">Star Shift</span>
  <p class="trait-description">Short description here.</p>
  <span class="trait-action">Open full info →</span>
</a>
