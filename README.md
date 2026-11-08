# Hermes 🛒

**Hermes** is a mobile-first family shopping list with a warm, retro-futuristic design. Keep everyone's shopping needs organised in one basket, using a single Google account.

## Features

- **Family groups:** Switch between individual lists or view everything together.
- **Priority items:** Star essentials to keep them at the top.
- **Shopping tracker:** Add quantities, categories and notes; mark items as purchased.
- **Price reference:** Compare a saved reference price with a newly found price in Mauritian rupees (Rs).
- **Three-month cleanup:** Review older items in batches, keep them for another three months, or move them to Trash.
- **Safer editing:** Confirm destructive actions, undo changes and restore trashed items.
- **Cloud sync:** Sign in through the existing Chronos Firebase configuration, with local caching and basket export.

## Getting started

Upload `index.html` to your GitHub repository and enable **GitHub Pages**. Open the deployed site and sign in with the same Google account used for Chronos.

Hermes is a standalone frontend and does **not** require backend modifications. It uses reserved records in Chronos's existing Firestore document. **Note:** Chronos still performs whole-document saves, so edits from a stale Chronos session could overwrite newer Hermes data. Avoid simultaneous editing and export backups periodically.

---

Made with ❤ by **MisterValiant**.
