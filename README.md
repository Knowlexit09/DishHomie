# DishHomie 🍲

**Your Daily Dish Helper — Pick • Spin • Plan • Cook**

A mobile-first Filipino dish picker, recipe guide, roulette and weekly lunch/dinner planner.

## Features
- Monday–Sunday with 10 default dishes per day (70 recipes).
- Choose Lunch or Dinner first. Each meal has a separate confirmed pick.
- Radio-button dish list with image/illustration, ingredients and cooking steps.
- Roulette: Spin, Try Again, View Recipe, or confirm a winner; no auto-accept.
- Friday Monggo and other nonbinding suggested day themes.
- Add, edit, delete, move, reorder, search and favorite recipes.
- Weekly grocery list from selected lunch and dinner dishes.
- Local browser autosave and JSON backup export/import.

## How to use
Open `index.html` in a browser, or visit the GitHub Pages website after deployment. No build step, account, API key or server is required.

## Publish with GitHub Pages
1. Repository: [Knowlexit09/DishHomie](https://github.com/Knowlexit09/DishHomie).
2. Open **Settings → Pages**.
3. Under Build and deployment select **Deploy from a branch**.
4. Choose **main** and **/(root)**; click **Save**.
5. Wait for publishing. Expected URL: https://knowlexit09.github.io/DishHomie/ ; confirm it in Pages settings.

## Storage and privacy
All custom recipes, favorites, picks and grocery checkmarks live in your current browser's `localStorage`, not in GitHub, and **do not sync between devices**. Export a JSON backup before clearing browser data. The storage key is preserved from the previous Ano'ng Ulam version to avoid discarding existing saved data. DishHomie imports both the new and previous backup formats.

## Food photos
25 default recipes now show individually matched, AI-generated DishHomie food photos embedded locally in `index.html` as compressed WebP data; 45 remaining default recipes show intentional emoji placeholders instead of unrelated food photos. No remote third-party/stock photos are used in default content. [AI image mapping and provenance](CREDITS.md). User-provided HTTPS photo URLs are optional and should only be used with appropriate permission.

## Files
- `index.html` — complete site, recipes, JavaScript and styles
- `README.md` — usage and setup
- `CREDITS.md` — image attribution
- `.nojekyll` — GitHub Pages helper

## Limitations
Recipe amounts are approximate and generally intended for 3–4 servings. There are currently no user accounts, cloud storage or cross-device sync; 45 default dishes still need their own matched images.

This is a public-source website. No open-source software license is granted by default. Third-party assets have separate licensing requirements.

<!-- GitHub Pages redeploy trigger: 2026-10-20; nonfunctional documentation change. -->
