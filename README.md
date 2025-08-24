# ATM10 Sky - Sieve Recipes Visual Cheat Sheet

![screenshot](img/screenshot.png)

This is a **visual reference table** for sieve recipes in the modpack **All The Mods 10: To The Sky (ATM10:Sky)**. It’s designed to help players quickly look up what inputs produce which outputs across all mesh tiers — complete with images!

## 💡 Features

- Input/Output filtering with multi-select dropdowns
- Mesh tier breakdown in pivot table format
- Drop chance values clearly shown
- Visual icons for every item (where available)
- Dark theme for monitor-side reference
- Fully static (no backend), ready for GitHub Pages

---

## 🧰 How It's Built

- Recipes pulled from:
  - Default Ex Deorum `.jar` JSON files
  - KubeJS overrides in `exdeorum.js`
- PowerShell script merges and flattens recipes into `sieve_recipes.csv`
- PNG item textures extracted from `minecraft.jar` and mod `.jar` files
- Pivot table UI built using vanilla JS + PapaParse

---

## 🧱 Credit

- Built for **All the Mods 10: To the Sky**
- Powered by Minecraft modding community
- Built using open standards: HTML, JS, CSV, PowerShell

---

## 📜 License

This project is open for personal use and contributions, but respects the original mod authors and content licenses.
