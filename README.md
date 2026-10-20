# SignalLab

Browser-only BTC/USDT chart analysis tool (live Binance spot data). No backend, no build step.

**Not investment advice. Places no trades.**

## Deploy on GitHub Pages
1. Upload `index.html`, `.nojekyll` and `README.md` to the repo root.
2. Settings -> Pages -> Deploy from a branch -> `main` / `(root)` -> Save.
3. Open `https://<your-username>.github.io/<repo-name>/`.

## Notes
- Data comes straight from Binance public endpoints in each visitor's browser. If Binance is blocked in their country/network, no data loads.
- Accounts, watchlist and history are stored in each visitor's browser (localStorage) only. This is not real security.
- The optional "Ask AI" feature uses the visitor's own Groq key (console.groq.com/keys), saved in their browser. Never put a key in the code.
