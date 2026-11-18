# Gym Deal Scout

A single-page browser tool for finding student and membership deals at climbing gyms and regular gyms in any location.

Enter a city or ZIP, pick gym types and deal types, and it builds targeted search links for Instagram, Facebook, Reddit, TikTok, X, Google, Google Maps, Yelp, ClassPass and student discount sites. Each link opens in a new tab.

There's also a **deal log** for saving the deals you confirm. When the page is hosted outside claude.ai, the log is saved in your browser's localStorage. Use **Copy as CSV** to back it up.

## Run it

Open `index.html` in any browser. You don't need to build or install anything.

## Host on GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, go to **Settings → Pages**, set the source to **Deploy from a branch**, then choose `main` and `/ (root)`.
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Notes

- The "Ask Claude" panel and saving the log to an account only work when the page runs as a claude.ai artifact. On other hosts the panel stays hidden and the log falls back to localStorage.
- Instagram and Facebook search results need you to be logged in to those sites.
