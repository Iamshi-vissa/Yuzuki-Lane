# YŪZUKI LANE

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

## ON PHONES

The game plays in landscape. On Android, starting a run goes fullscreen and locks the screen sideways. On iPhone (where websites can't lock rotation), a prompt asks you to turn the phone, and a run pauses if you turn it upright again. Add it to your home screen to play it fullscreen like an app.

## OBSTACLES

- **Stone lantern** and **sake barrels**: jump over them.
- **Hanging festival lantern** (from 120 m): duck under it.
- **Rolling taiko drum** (from 260 m): comes at you faster than the street.
- **Stacked barrels** (from 420 m): a higher jump.

The run speeds up as you go. The sky moves from dusk to a moonlit night and back, and your best distance is saved in the browser.

## MUSIC AND SOUND

Two original pieces written for the game crossfade as you play:

- **Lantern Run** (while running): a bright bamboo-flute hook in the Japanese yo scale over pads, bass and koto, with a festival drum groove, shamisen and taiko that build as the run speeds up.
- **Ash and Moonlight** (after a crash): slow pads in the in-scale, temple-bell strikes, soft koto and a low flute. A new run fades back to Lantern Run.

Jumps make a heavy breath, ducking makes a scraping slide on the stones (the body skids with the same sound after a crash), and each obstacle has its own crash sound. Everything is synthesised live with the Web Audio API and mixed through a reverb, so there are no audio files and no third-party licences. Press M or the ♪ button to mute.

## DEPLOY

```bash
npx vercel deploy --prod
```
