# portfolio-dashboard-live

A static mirror of the upstream project [xbtgodxd/portfolio-dashboard](https://github.com/xbtgodxd/portfolio-dashboard), deployed as a public site via GitHub Pages.

**Live site:** https://coattails-droid.github.io/portfolio-dashboard-live/

**Source:** https://github.com/xbtgodxd/portfolio-dashboard
**Upstream commit copied:** `f7cb2105f48bb0158818053dbe38ecceba35b7e7`
**Copied on:** 2026-09-24

This mirror contains the app's `index.html` (self-contained, no build step required) and the upstream `LICENSE` verbatim. No changes were made to the app itself. License: MIT (copyright xbtgodXD, 2026) — see LICENSE.

## What this is

A client-side crypto portfolio dashboard: a single HTML file using browser `localStorage` and free public price feeds (CoinGecko, Binance, Yahoo via an allorigins relay, Derive.xyz, open.er-api.com). No backend, no API keys, no build step.

## Product caveats (know before you use it)

- **~5 MB localStorage cap:** browser storage is limited (~5 MB per origin in most browsers); the app itself surfaces a storage warning when it gets close.
- **Browser data loss wipes data:** clearing site/browser data deletes everything stored in `localStorage`. Use the app's one-click backup/export feature regularly — there is no server-side copy.
- **Free feeds can rate-limit:** price data comes from free public APIs; under heavy use they can throttle or fail, and quotes may be stale or missing.
- **Not financial advice:** a dashboard is not a recommendation engine. Verify prices independently before acting on them.

## ⚠️ Adoption risk

The upstream repo is **new (created July 2026), maintained by a single person, with ~50 commits and essentially no adoption** (0 stars at time of copy). That means: no community review, no security audit, bugs are likely, and the project could be abandoned at any time. Treat this as an experimental, unproven tool — inspect the code before trusting it with real portfolio data, and keep independent records of anything important.

## Updating the mirror

This is a manual static mirror. To refresh it from upstream later: re-download `index.html` from the upstream commit you want, replace the file here, and push. There is no CI syncing it automatically.
