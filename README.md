# Dino Run

A dinosaur runner for a round screen: jump over cacti, duck under birds, 10 levels.

**Play Dino Run:** https://oorhuri.github.io/Dino-run/
**Play Tabodi Run** (same game, its own cast of original characters): https://oorhuri.github.io/Dino-run/tabodi/

- **Solo** — clear a set number of obstacles to pass each level.
- **Online race (up to 8 players)** — the host creates a room and shares the 4-letter code; everyone else joins. All players race the same course; hitting an obstacle freezes you for a moment. Each level awards points by finishing order (10, 8, 6, 5, 4, 3, 2, 1) and after 10 levels the player with the most points wins (ties broken by 1st places, then 2nd, then 3rd). Uses PeerJS for direct browser-to-browser connections; if it fails on mobile data, try Wi-Fi.

- **Family game** — the host can switch it on in the race lobby. Every level, each player wins a different prize (fastest, most careful, jump king, highest jump, most time in the air, ducking champ, closest shaves, longest streak, bravest, enjoying the view), everyone gets the same points, and at the end everybody wins with their collection of prizes. No live ranking during the race.

Sounds are synthesized in the browser (no audio files); the 🔊 button mutes them.

`tabodi/index.html` is a copy of `index.html` with a different `GAME_THEME` block at the top (title, character set, storage keys). To make another variant, copy the file and change that block.

Controls: jump button / tap the screen / Space or ↑ — duck: ↓ button or key.
