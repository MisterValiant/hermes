# Hermes 🛒

**Hermes** is a mobile-first family shopping basket with a soft retro-futuristic design. Organise shopping for everyone using one Google account, without changing the existing Chronos Firebase backend.

## Features

- Family groups with custom person icons and colours, plus a combined **Everyone** view.
- **Pin one default group per device**; the pin is saved locally and is never synced.
- Quick-add shopping items, quantities, categories, notes, priority stars and purchase history.
- Compare **reference** and **found** prices in Mauritian rupees (Rs).
- Review items every three months, keep them or move them to recoverable Trash.
- Undo, confirmation dialogs, backup export and careful cloud syncing.
- Mobile-friendly search and expandable filters, optional sound effects and gentle animations.
- Social sharing previews, phone home-screen icons and a web-app manifest.

## Deployment

Upload `index.html`, `manifest.webmanifest` and the entire `assets/` folder to the repository root. Enable **GitHub Pages** for your repository and sign in with the existing Google account.

The `assets/` files are important: without them, social previews and mobile home-screen icons may not display correctly. No backend changes or paid hosting are required for the frontend.

**Data note:** Hermes uses reserved records inside the existing Firestore document. The unchanged Chronos site still performs full-document saves, so simultaneous or stale editing sessions can overwrite newer Hermes data. Keep exports and avoid updating both apps at once. Live access also depends on your existing Firestore security rules.

---

Made with ❤ by **MisterValiant**.
