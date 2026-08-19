# Spring Alien Platformer 👽

A little 2D platformer that runs in a web browser — no installs, no build tools.
It stars a green alien who bounces around on a spring. Made as a coding
learning project.

## How to play

Just open **`index.html`** in any web browser (double-click it, or drag it into
a browser window). That's it.

### Controls

| Action | Keys |
| --- | --- |
| Move | Arrow keys, or `A` / `D` |
| Jump | `Space`, `Up`, or `W` |
| Throw a bomb | `F` |

## The levels

1. **Platforms** — hop up a few ledges to the flag.
2. **The big jump** — sprint across the ground and leap to a faraway goal.
3. **Lava floor** — hop across stepping stones; don't fall in!
4. **Rickety trap** — a normal-looking platform drops into the lava once you step on it.
5. **Alien enemy** — a purple alien paces back and forth; jump over it.
6. **Moving platform** — ride the ferry across a gap you can't jump.
7. **Brick wall** — grab the bomb and throw it to blast through the wall.

Reach the last flag for the **You Win!** screen. A timer with **Start / Restart**
buttons sits under the game, and it remembers your **best (fastest) finish time**.

## How it's built

Everything lives in a single `index.html` file — the HTML, styling, and all the
game code together. The game is drawn on an HTML `<canvas>`, and the characters
(hero, alien, flag, bomb) are all little pixel-art grids painted by one shared
drawing function. Each level is just described as data (platforms, goal, lava,
enemies, and so on), and one game loop knows how to play any of them.
