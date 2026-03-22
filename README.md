# 🏃 Run From 67

A browser-based arcade game where you run from **67** — the Steal a Brainrot Roblox character — for as long as you can.

## 🎮 Play

Just open `index.html` in any browser. No install, no dependencies, no server needed.

Or play it live via **GitHub Pages** (enable in repo Settings → Pages → deploy from `main` branch root).

---

## 🕹️ Controls

| Input | Action |
|-------|--------|
| `WASD` / Arrow Keys | Move |
| `ESC` | Close shop |
| Touch drag | Move (mobile) |

---

## 💰 Currencies & Shop

| Currency | Symbol | Used For |
|----------|--------|----------|
| Coins | 🪙 | Buy Shoes (speed boost) |
| Gems | 💎 | Buy Trails (speed boost + visual) |
| Crowns | 👑 | Buy Hats (slow down 67's speed gain) |
| OjiDollars | 💠 | Future use |

### 👟 Shoes
| Name | Cost | Speed |
|------|------|-------|
| Bare Feet | Free | Base |
| Sneakers | 15🪙 | +22% |
| Air Nikes | 40🪙 | +50% |
| Rocket Boots | 90🪙 | +88% |
| 👑 Owner Boots | Free | +180% |

### ✨ Trails
| Name | Cost | Speed Boost |
|------|------|-------------|
| Default | Free | +0 |
| Fire Trail 🔥 | 5💎 | +0.5 |
| Storm Trail ⚡ | 12💎 | +1.2 |
| Void Trail 🌀 | 25💎 | +2.0 |
| Divine Trail 🌟 | 50💎 | +3.5 |
| 👑 Owner Trail | Free | +5.0 |

### 🎩 Hats
| Name | Cost | 67 Speed Reduction |
|------|------|--------------------|
| No Hat | Free | 0% |
| Baseball Cap 🧢 | 8👑 | -20% |
| Top Hat 🎩 | 20👑 | -40% |
| Wizard Hat 🧙 | 45👑 | -60% |
| King Crown 💀 | 80👑 | -85% |
| 👑 Owner Crown | Free | -99% |

---

## ⚙️ Features

- Animated stickman player with equipped shoes on feet
- **67** drawn as the Steal a Brainrot Roblox character (blocky blue digit body, eyes, gloves, trainers)
- 67 gets faster every 20 seconds
- Persistent save data via `localStorage`
- Coin, Gem, Crown & OjiDollar collectibles on the map
- Owner-exclusive free items

---

## 🗂️ File Structure

```
run-from-67/
├── index.html   ← entire game (single file, no dependencies)
└── README.md
```

---

## 🚀 Deploy to GitHub Pages

1. Push this folder to a GitHub repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your game will be live at `https://yourusername.github.io/run-from-67/`
