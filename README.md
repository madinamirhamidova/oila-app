# 🏡 Oila — Family Management Telegram Mini App

A lightweight Telegram Mini App that helps families plan healthy meals and track household finances, built for the Uzbek market.

![Platform](https://img.shields.io/badge/platform-Telegram%20Mini%20App-2AABEE)
![Stack](https://img.shields.io/badge/stack-Vanilla%20JS-F7DF1E)
![Languages](https://img.shields.io/badge/languages-UZ%20%7C%20EN-2ea66f)
![Backend](https://img.shields.io/badge/backend-none-lightgrey)

---

## ✨ Features

### 🍽 Healthy Family Menu
- **42 curated recipes** across Uzbek 🇺🇿, Turkish 🇹🇷 and International 🌍 cuisine
- Five categories: breakfast, soup, main course, salad, dessert
- Each recipe includes calories per serving, cooking time, ingredients, steps and a "why it's healthy" note
- **Daily menu generator** with per-dish reshuffle
- **Weekly plan** with no repeated dishes
- **Auto-generated shopping list** from the weekly plan
- Favourites, search, and cuisine and category filters

### 💰 Household Finance
- Income and expense tracking in UZS (so'm)
- Local categories, including weddings and gifts (to'y / sovg'a)
- Entries tagged by family member
- Month-by-month view with balance, income and expense totals
- Monthly budget with a progress bar
- Spending breakdown by category

### 📱 Native Telegram Experience
- Follows the user's Telegram light or dark theme
- Native back button and haptic feedback
- Bilingual interface: O'zbekcha / English
- Data synced across devices through Telegram CloudStorage

---

## 🛠 Tech Stack

| Layer | Choice |
|---|---|
| Frontend | Single-file HTML, CSS and vanilla JavaScript |
| Telegram SDK | [Telegram Web Apps API](https://core.telegram.org/bots/webapps) |
| Storage | Telegram CloudStorage (chunked), localStorage fallback |
| Backend | None (v1) |
| Dependencies | Zero |

---

## 📂 Project Structure

```
.
├── index.html   # The entire Mini App: UI, recipe data, logic
└── README.md
```

---

## 🗺 Roadmap

- [x] Healthy menu planner with weekly plan and shopping list
- [x] Income and expense tracking with budget
- [ ] Shared family budget (backend + family invite code)
- [ ] Fiscal receipt QR scanning (soliq.uz receipts) for automatic expense entry
- [ ] Bank card notification parsing (Humo / Uzcard) via the bot
- [ ] Bank statement import (Excel / PDF)
- [ ] Bot reminders: daily menu, monthly finance report
- [ ] AI-generated menus based on available ingredients
