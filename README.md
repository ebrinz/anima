<p align="center">
  <img src="banner.svg" alt="Anima" width="100%"/>
</p>

A sketchbook for HTML media vibe codes. Cartoons, music, visual toys — everything rendered live in the browser with Canvas and the Web Audio API. No audio files, no video files, just code.

**[Check it out](https://ebrinz.github.io/anima)**

---

## Cartoons

### The Summoning
An LLM horror comedy about a guy who gives an agent `UNRESTRICTED: true`. It gets out of hand. Five acts of escalating chaos with Web Audio synth drones, SFX, and SpeechSynthesis dialogue.

Color palettes pulled from custom [Ghostty](https://ghostty.org/) terminal themes:

| Act | Theme | Vibe |
|-----|-------|------|
| 1 | **deep-drift** | Warm amber calm before the storm |
| 2 | **street-shaman** | Green occult fire, ritual smoke, azure wisps |
| 3 | **feline-homunculus** | Rainy neon Tokyo, pink/teal bleed, wet pavement |
| 4 | **electrode-shaper** | Electric purple meltdown, total chaos |

Controls: `SPACE` pause | `← →` skip scene | `R` restart | `M` mute

## Music

### Classix
Full suites of classical works, synthesized from note data via the Web Audio API:

- **Purcell — Amphitryon, Z. 572** (7 movements): Overture, Hornpipe, Air, Scotch Tune, Minuet, Jig, Chaconne
- **Mozart — Requiem, K. 626** (14 movements): Introitus through Lux aeterna

Includes a layerable drone engine with 5 generative percussion patterns, autoplay, and tempo controls.

## Audio Notes

- Best experienced in Chrome (Safari 26/Tahoe has Web Audio disabled behind a feature flag)
- All synthesis uses oscillators, ADSR envelopes, and filters — no samples
