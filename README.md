# Voidborne

**Voidborne** is a fast-paced, multiplayer-inspired agar.io-style browser game set in a cosmic void.  
Consume stardust, outmaneuver other players (and clever bots), use powerful affinity abilities, avoid deadly gravity wells, and become the largest cosmic entity in the arena.

Live demo (if hosted):  
→ https://yourusername.github.io/voidborne/  
(or replace with Netlify / Vercel / GitHub Pages link once deployed)

<p align="center">
  <img src="https://via.placeholder.com/800x450/0c0a15/8b5cf6?text=Voidborne+Gameplay+Screenshot" alt="Voidborne Gameplay" width="800"/>
  <br/>
  <em>Early gameplay screenshot – cosmic chaos in progress</em>
</p>

## ✨ Features

- **Five unique Affinities** with different playstyles  
  - **Comet** – explosive Starfall Dash  
  - **Bastion** – temporary invulnerability (Harden)  
  - **Phantom** – invisibility / stealth phase  
  - **Graviton** – create slowing gravity wells  
  - **Leech** – passive mass drain from nearby smaller players  

- **Core Agar.io-style mechanics** + modern twists  
  - Split / recombine cells  
  - Eject mass (W key)  
  - Feed gravity wells → launch deadly projectiles  
  - Dynamic zoom camera  

- **Environmental hazards & events**  
  - Nebulas (slow movement, partial camouflage)  
  - Gravity Wells (shatter large cores)  
  - Supernova zones (massive stardust rain)  
  - Bounty system – hunt the #1 player for huge rewards  
  - Rare **Golden Stardust** drops  

- **Responsive controls**  
  - Desktop: mouse + keyboard (Space / W / E)  
  - Mobile/touch: virtual joystick + big action buttons  

- **Polish & feedback**  
  - Screen shake, particle effects, parallax starfield  
  - Cooldown UI, energy bar, leaderboard  
  - Announcements (supernova, bounty, etc.)  
  - Pause menu, death screen, how-to-play guide  

- Single-file HTML5 game (~zero dependencies)

## 🎮 How to Play

| Action              | Desktop             | Mobile              |
|---------------------|---------------------|---------------------|
| Move                | Mouse               | Drag joystick       |
| Split cells         | Space               | Split button        |
| Eject mass          | W                   | Eject button        |
| Use ability         | E / click icon      | Ability button      |
| Pause               | Esc                 | — (menu button planned) |

**Objective**  
Grow bigger than everyone else by eating **stardust** and smaller players.  
Avoid being eaten by anything larger than you.

**Tips**  
- Use **Phantom** + nebula = very hard to spot  
- Feed gravity wells with **W** → turn defense into offense  
- Claim the **bounty** on #1 for instant mass & energy boost  
- **Leech** shines in crowded late-game fights

## 🚀 Quick Start (Local)

1. Clone or download the repository

```bash
git clone https://github.com/yourusername/voidborne.git
cd voidborne
```
2. Open the game

Just double-click Voidborne2.3.html
(or drag it into any modern browser: Chrome, Firefox, Edge, Safari)</br>
No build step. No server required.

## 🛠️ Tech Stack
- HTML5 Canvas – rendering & game loop
- Pure Vanilla JavaScript (ES6+)
- CSS (Tailwind-inspired utility classes + custom dark cosmic theme)
- Touch + mouse event handling
- No external libraries / frameworks

## 📂 Project Structure

```text
voidborne/
├── Voidborne2.3.html     ← complete single-file game (this is the one!)
├── README.md             ← you're reading it
└── (future)
    ├── assets/           ← sounds, better background, icons...
    ├── index.html        ← cleaner entry point (planned)
    └── server/           ← potential multiplayer version
```
## 🗺️ Planned / Possible Future Features

- Real multiplayer (WebSocket / Node.js / PeerJS)
- Sound effects & background music
- More affinities / upgrades
- Daily challenges / achievements
- Skin / color customisation
- Spectator mode
- Better mobile UX (pinch zoom, better joystick)
Contributions welcome — especially for multiplayer or audio!

---
## ⚖️ License
MIT License

Feel free to fork, modify, learn from, or use parts of the code in your own projects.

---
## 🙌 Acknowledgments

Inspired by classics:
- agar.io
- slither.io
- Diep.io

