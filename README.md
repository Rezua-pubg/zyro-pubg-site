# ZYRO PUBG — multi-page clan website

Responsive multi-page static website for GitHub Pages.

Pages:
- `index.html` — Home
- `ratings.html` — Metro Royale / Classic / Ultimate leaderboard tabs (demo data)
- `news.html` — announcement cards (demo data)
- `clan.html` — clan roster and principles
- `apply.html` — join and appeal forms
- `style.css` — shared black-and-gold theme
- `site.js` — rating tab interactions

## Publish on GitHub Pages
Upload all files to the root of the `zyro-pubg-site` repository (keep filenames and structure). In Settings → Pages, select `Deploy from a branch`, branch `main`, folder `/ (root)`.

## Important
- Ratings and news are demo/static content and do not yet read from Supabase.
- Forms use the current FormSubmit endpoint from the previous site; test delivery after publishing.
- Do not expose Supabase secret/service-role keys in these files.
