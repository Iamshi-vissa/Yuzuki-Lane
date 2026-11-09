# Y��ZUKI LANE

An endless runner down a Japanese maple street at sunset, under a rising full moon. A straw-hatted wanderer in a wolf mask runs a lantern-lit lane; jump and duck past what the street throws at you.

Everything is a single self-contained `index.html`: all art is drawn on a canvas in code, the music is synthesised with the Web Audio API, and the only external request is Google Fonts.

## PLAY

Open `index.html` in a browser, or deploy the folder to any static host (a `vercel.json` is included).

| Action | Keyboard | Touch |
| --- | --- | --- |
| Jump (press again mid-air to double jump; hold for a higher jump) | Space / ↑ / W | Tap the right side |
| Duck (drops you fast mid-air) | ↓ / S | Hold the left side |
| Pause / resume | P or Esc | ⏸ button |
| Mute | M | ♪ button |

## OBSTACLES

- **Stone lantern** and **sake barrels**: jump over them.
- **Hanging festival lantern** (from 120 m): duck under it.
- **Rolling taiko drum** (from 260 m): comes at you faster than the street.
- **Stacked barrels** (from 420 m): a higher jump.

The run speeds up as you go. The sky moves from dusk to a moonlit night and back, and your best distance is saved in the browser.

## DEPLOY

```bash
npx vercel deploy --prod
```
