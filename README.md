<div align="center">

<h1>shaders</h1>
<p><i><b>Ghostty terminal shaders</b></i></p>

[![GitHub][github-badge]][github-url]
[![Ghostty][ghostty-badge]][ghostty-url]

</div>

___

## ToC

- [About](#about)
- [Install](#install)
- [Usage](#usage)
- [Shaders](#shaders)
- [Contact](#contact)

___

## About

- **40 GLSL shaders** for Ghostty terminal
- cursor effects- trails, warps, ripples, booms
- background effects- CRT, matrix, starfield, bloom, gradients
- vendored and stripped of provenance for clean config

___

## Install

```bash
git clone --depth 1 https://github.com/vdutts7/shaders ~/.config/ghostty/shaders
```

___

## Usage

Add to Ghostty config (`~/Library/Application Support/com.mitchellh.ghostty/config.ghostty`):

```
custom-shader = ~/.config/ghostty/shaders/<shader>.glsl
custom-shader-animation = always
```

| Arg | Description |
|-----|-------------|
| `custom-shader` | path to `.glsl` file |
| `custom-shader-animation` | `always` for animated, `true` for cursor-only |

___

## Shaders

**Cursor effects** (lightweight, trigger on cursor movement)
- `cursor_tail` - fading trail behind cursor
- `cursor_sweep` - sweep effect
- `cursor_warp` - warp/teleport trail
- `cursor_blaze` - blazing cursor
- `ripple_cursor` - ripple ring on movement
- `rectangle_boom_cursor` - rectangle explosion
- `ripple_rectangle_cursor` - rectangle ripple
- `sonic_boom_cursor` - sonic boom pulse

**CRT / Retro**
- `crt` - full CRT simulation
- `bettercrt` - cleaner CRT
- `in-game-crt` - game-style CRT
- `in-game-crt-cursor` - CRT with cursor effect
- `retro-terminal` - retro green terminal
- `tft` - TFT display effect

**Background animations**
- `bloom` - subtle text glow
- `starfield` - moving stars
- `starfield-colors` - colored starfield
- `galaxy` - galaxy background
- `animated-gradient-shader` - animated gradient
- `gradient-background` - static gradient
- `just-snow` - falling snow
- `underwater` - underwater effect
- `water` - water surface

**Matrix / Glitch**
- `inside-the-matrix` - matrix rain
- `matrix-hallway` - matrix hallway
- `glitchy` - glitch effect
- `glow-rgbsplit-twitchy` - RGB split glitch

**Misc**
- `fireworks` - fireworks
- `fireworks-rockets` - rocket fireworks
- `cubes` - 3D cubes
- `gears-and-belts` - mechanical gears
- `sparks-from-fire` - fire sparks
- `smoke-and-ghost` - smoke effect
- `spotlight` - spotlight
- `cineShader-Lava` - lava
- `dither` - dithering
- `drunkard` - wobble effect
- `mnoise` - noise
- `negative` - invert colors
- `sin-interference` - interference pattern

___

## Contact

<a href="https://vd7.io"><img src="https://res.cloudinary.com/ddyc1es5v/image/upload/v1773910810/readme-badges/readme-badge-vd7.png" alt="vd7.io" height="40" /></a> &nbsp; <a href="https://x.com/vdutts7"><img src="https://res.cloudinary.com/ddyc1es5v/image/upload/v1773910817/readme-badges/readme-badge-x.png" alt="/vdutts7" height="40" /></a>

<!-- BADGES -->
[github-badge]: assets/badges/github.badge.svg
[github-url]: https://github.com/vdutts7/shaders
[ghostty-badge]: assets/badges/ghostty.badge.svg
[ghostty-url]: https://ghostty.org
