# Family Table

A local-first, mobile-friendly family dinner planner designed for GitHub Pages.

## Features
- Search and filter saved recipes by cooking time, tried status, Ethan-friendly options, fiber/protein focus, and ingredients on hand.
- Add and edit recipes, including quantities, inline cooking instructions, substitutions, notes, and ratings.
- Plan seven dinners and automatically consolidate groceries by store and section.
- Check off shopping items and export/import a JSON backup.

## Run locally
Open `index.html` in a browser. No build step, server, dependencies, or API keys required.

## Publish to GitHub Pages
For GitHub Free, make the repository public when you are comfortable publishing the **source code**. In repository **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save. The site should appear at `https://ruthchang.github.io/family-table/` after deployment.

## Privacy and data
Your personal edits are saved in the browser's `localStorage` under `family-table-v1`. They are **not** committed to GitHub and do not sync across devices. Export a JSON backup regularly, especially before clearing browser data or switching devices. Do not commit exported backups if they contain private information.

## Starter recipes
The included dishes are **illustrative adaptations**, not imports of the user's original Notion recipes. Review ingredient quantities, cooking methods, and food safety before use. Replace them with your preferred tested recipes as needed.

## Notes
Ingredient consolidation sums quantities only when ingredient, unit, store, and section match. It does not convert units or adjust recipes by serving size. Grocery store assignments are editable per ingredient.
