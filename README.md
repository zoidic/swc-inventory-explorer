# SWC Inventory Explorer

A browser tool for Star Wars Combine faction inventory exports: ships, vehicles, NPCs, droids, items and facilities, linked by what is inside what, and checked against an Equipment loadout sheet to show what needs to be requisitioned.

**Live:** https://zoidic.github.io/swc-inventory-explorer/

- Drop the inventory exports (.csv) and the Equipment loadout (.xlsx), or a whole folder of them. Files are read in the browser; nothing is uploaded unless you sign in.
- **Sign in to sync** (email + password) stores the loaded files and mapping choices in your own account, so they appear on your other devices. Each account can only read its own data.
- No faction data is part of this page or repository.

Single file (`index.html`), no build step. Sync uses Firebase Authentication and Cloud Firestore.
