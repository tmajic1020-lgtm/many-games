# many-games

A collection of small, self-contained browser games. Each game is a single HTML file —
open it directly, no build step and no server.

## Games

| Game | File | About |
| --- | --- | --- |
| 🍞 **BREAD CLICKER** | [`bread-clicker.html`](bread-clicker.html) | A modern idle/clicker game. Click the loaf, build 22 kinds of tower, level and prestige them, catch wanderers, then ascend and spend Starter Yeast on a permanent perk tree. 239 upgrades, 98 achievements, 24 perks. Progress saves to local storage. |

### BREAD CLICKER at a glance

- **The loaf** — inline SVG, spring click animation, crumb particles, and an embedded
  `click.wav` played through the Web Audio API so rapid clicks overlap.
- **Combos** — chained clicks build a multiplier that drains on a live meter.
- **Towers** — 22 buildings, bought ×1/×10/×100/MAX. Each levels 50 times, then prestiges
  so future levels hit far harder.
- **Upgrades** — 239 of them, spawning from what you do: click counts, buildings owned,
  synergies between towers, combos, wanderers and ascensions.
- **Wanderers** — Golden Loaves, Wheat Sprites and Yeast Blooms drift across the screen
  for lump sums and buffs.
- **Ascension** — bank a run for Starter Yeast and spend it in the Starter Vault on a
  four-branch perk tree (Hands, Hearth, Fortune, Legacy) that survives every reset,
  including an auto-clicker and two autobuyers.
- **Panels** — Stats (with a live production graph), Achievements, Ascension and Options
  on the left; upgrades, Production and Towers on the right. Both collapse, and stack
  top/bottom on mobile.
