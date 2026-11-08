<p align="center">
  <img src="docs/banner.jpg" alt="Flubbie" width="820">
</p>

<p align="center">
  <b>Leap from ring to ring, slip between the monsters, and climb all the way to the Golden Ring.</b><br>
  A colorful one-tap arcade game that runs right in your browser.
</p>

<p align="center">
  <a href="https://agmcorp.itch.io/flubbie"><img src="https://img.shields.io/badge/%E2%96%B6%20Play%20free-itch.io-fa5c5c?style=for-the-badge" alt="Play free on itch.io"></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Mobile%20%26%20desktop-browser-4aa8ff?style=for-the-badge" alt="Mobile and desktop browser">
</p>

<p align="center">
  <img src="docs/menu.jpg" width="200" alt="Main menu">
  <img src="docs/play.jpg" width="200" alt="Climbing the rings">
  <img src="docs/boss.jpg" width="200" alt="Boss defeated, new prizes in the shop">
  <img src="docs/finale.jpg" width="200" alt="The grand finale">
</p>

## How to play

Flubbie sits in a ring. **Tap the screen** (or press <kbd>Space</kbd>) to jump to the next one.

The monsters move in patterns: watch them, wait for the gap, and go. But don't wait too long, because every ring has its own timer. Hit a monster and you fall back to your last checkpoint.

## What's inside

- **A long climb** with a boss every few rings, a celebration at each milestone, and a grand finale on the Golden Ring
- **Power-ups and tricks**: power ball, shield, shockwave, slow and fast clocks, tiny potion, magnet, freeze, candy rain, a hungry monster friend, and a couple of sneaky curses
- **Endless mode**, unlocked at the top: the rings never stop, so how high can you go?
- **A candy shop and a wardrobe** full of colors, looks and pets that float by Flubbie's side
- **Prizes** to win along the way, from a mustache to the royal crown
- **Seasonal looks**: Halloween and Christmas dress up the sky, the monsters and the pets. Pick one anytime from the menu
- **Share your record** as a picture and challenge your friends
- Plays on phones and computers, nothing to install

<p align="center">
  <img src="docs/halloween.jpg" width="200" alt="Halloween look">
  <img src="docs/christmas.jpg" width="200" alt="Christmas look">
  <img src="docs/shop.jpg" width="200" alt="The shop">
</p>

## Run it locally

The whole game is a single `index.html` with its music and sound effects next to it. Browsers block sound files opened straight from disk, so serve the folder with any small web server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Project layout

```
index.html        the whole game: graphics, logic and styles
*.mp3             music: menu, game, game over and finale
sfx/              sound effects
docs/             images for this page (not part of the game)
```

To publish on itch.io, zip `index.html`, the `.mp3` files and the `sfx/` folder.

## History

Flubbie was born in 2020 as a mobile game built with Unity. This is its browser edition, rebuilt from scratch with new characters, power-ups, bosses and a whole lot more. The original still lives at [agmcorp.itch.io/flubbie-original](https://agmcorp.itch.io/flubbie-original).

## Credits

**Game and design:** Álvaro G. Morales (AGMCORP)<br>
**Sounds:** Freesound.org and IndieGameMusic.com

Made in Montevideo, Uruguay.
