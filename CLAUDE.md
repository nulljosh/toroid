# Toroid (ex-Conway)

Game of Life on a wrapping grid. Ships as **Toroid** on the App Store (ASC 6806324937) and at toroid.jaybulb.com. The bundle id and the Cloudflare Pages project keep the conway name (`conway`, deploy with `scripts/deploy.sh`).

- `life.js` + `index.html` / `play.html` web, `ios/`, `macos/`, `watchos/` (standalone companion), `kmp/` for Android and desktop, `functions/` for /api and /mcp
- No accounts, no network, no storage. Do not add any
- Ship: `asc workflow run ship-ios VERSION:x.y.z`. Metadata in `metadata/`
- `asc versions list --app 6806324937` is the truth on versions
