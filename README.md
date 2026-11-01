# Afonso Hust ($TICKER) 🍌

Meme coin site for Afonso, the crowned macaque of the jungle. One static page, zero build steps.

## Deploy
Host this folder anywhere that serves static files (GitHub Pages, Vercel, Netlify). `index.html` plus the images is all you need.

## Configure
Everything editable lives in the `CONFIG` block at the top of the `<script>` in `index.html`: ticker, contract address, supply and the pump.fun / Telegram / X / Dexscreener links.

## Notes
- The global "Kings of the Jungle" leaderboard only works on the published claude.ai artifact version; self-hosted builds show the local best score instead.
- Replace `banner.png` / meme images freely — the gallery auto-loads `meme1.webp` … `meme8.webp`.
