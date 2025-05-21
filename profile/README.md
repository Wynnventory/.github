# Wynnventory Organization

Welcome! First of all, thanks for your interest in contributing to Wynnventory. Our organization is dedicated to building a powerful, community-driven toolset for Wynncraft players, consisting of two complementary components:

* **Wynnventory Web (API)**
* **Wynnventory (Minecraft Mod)**

---

## 📡 Wynnventory Web (API)

**Repository:** [Wynnventory/WynnVentory\_Web](https://github.com/Wynnventory/WynnVentory_Web)

**Stack:**

* Python / Flask
* MongoDB

### What it does

* Defines and implements all API endpoints for reading and writing data to/from our website and the Wynnventory Mod.
* Uses MongoDB to store crowd‑sourced pricing and reward‑pool data.
* Provides protected access: all endpoints require an API key.

> **Need an API key?** We have dedicated development keys. DM @Aruloci or @Sirop to request yours. **Keep it secret** and use it only for development!

### How to contribute

1. **Fork & Clone** the repo.
2. **Open an Github Issue** describing the feature or bug you want to tackle.
3. **Create a branch** using the Github Issue.
4. **Implement and test** your changes.
5. **Open a PR** targeting the `test` branch.
6. We’ll review, provide feedback, and merge when ready! 🙌

---

## 🎮 Wynnventory (Minecraft Mod)

**Repository:** [Wynnventory/WynnVentory\_Mod](https://github.com/Wynnventory/WynnVentory_Mod)

**Stack:** Java

### Overview

Wynnventory is your ultimate Wynncraft loot companion, bringing real-time data and powerful in‑game tools straight to your inventory screen. When you hover over items in the trademarket or check rewards chests, anonymized data is sent to our API to power tooltips, notifications, and analytics.

### Key Features

* **Price Tooltips**: Hover over any item (even boxed items!) to see historic trademarket prices from the last 7 days, crowdsourced from all players.
* **In-Game Raid & Lootrun Screen**: Press `N` to open a full-screen view of current raid and lootruns rewards without leaving the game.
* **Favorite Notifier**: Mark items as “favorites” and receive instant alerts when they appear in the active reward pools.
* **Material & Ingredient Tooltips**: Get price trends and demand insights for crafting materials and brewing ingredients.
* **Aspect Tooltips**: Hover over raids in the party finder to see mythic aspects, then browse the full list to pick your perfect challenge.

### How It Works

1. **Data Collection**: Every time you view the trademarket or inspect raid/lootruns, your client sends anonymized data to our backend.
2. **Crowdsourcing**: This data powers both the in‑game tooltips and our website analytics.
3. **Customization**: Open the config menu (hotkey or `Esc → Mods → Wynnventory`) to choose which stats, tooltips, and notifications you want.

### How to contribute

1. **Fork & Clone** the repo.
2. **Open an issue** describing the feature or bug you want to tackle.
3. **Create a branch** using the Github Issue.
4. **Implement and test** locally.
5. **Open a PR** against the `master` branch for review.
6. We’ll test, tweak, and merge—it’s that simple!

---

## 🌐 Learn More

For deep dives into price histories, trend charts, and community analytics, visit our website: **[wynnventory.com](https://wynnventory.com)**

Thank you for helping make Wynnventory better for everyone! 🙏
