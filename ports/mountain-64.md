# Mountain 64

**Celeste 64: Fragments of the Mountain** · originally on PC (2024)
Port by [@LowRiderXR](https://github.com/LowRiderXR)

Start with this command, which gets exactly the code that was scanned:

```
git clone https://github.com/LowRiderXR/mountain64-visionos-app && cd mountain64-visionos-app && git checkout 2955eba09694581c2c45fce1febac103d18be8c8 && git submodule update --init --recursive
```

Then follow the [install guide](https://github.com/LowRiderXR/mountain64-visionos-app/blob/2955eba09694581c2c45fce1febac103d18be8c8/AVP-INSTALL.md) from its build steps. Skip only its step that clones or downloads this repo, which would fetch newer code that may not have been scanned; keep every other step, including dependency downloads.

| | |
| --- | --- |
| Trust | Working |
| Status | Working: Unofficial, free fan port, not made or endorsed by the Celeste team. The developer also offers it on TestFlight. Building from source needs your own FMOD Engine download from fmod.com. Not tested by the curator. |
| Plays as | 6DoF immersive |
| Health | OK |
| Scan | Scanned 2026-11-16 · 0 commits since |
| Source (scanned) | [LowRiderXR/mountain64-visionos-app at 2955eba09694](https://github.com/LowRiderXR/mountain64-visionos-app/tree/2955eba09694581c2c45fce1febac103d18be8c8) |
| Install guide | [AVP-INSTALL.md at 2955eba09694](https://github.com/LowRiderXR/mountain64-visionos-app/blob/2955eba09694581c2c45fce1febac103d18be8c8/AVP-INSTALL.md) |
| Repo | [LowRiderXR/mountain64-visionos-app](https://github.com/LowRiderXR/mountain64-visionos-app) |
| License | Custom license |
| Last commit | 2026-11-16 |
| visionOS | 27.0 or later |
| Input | game controller |
| Tags | celeste, celeste-64, platformer, 3d, vr, source-port |

Native Vision Pro port of Celeste 64, the free 3D Celeste platformer released with its source: the mountain in stereo in a full immersive space, with head tracking and game-controller input. The game content comes from the official source release.

## Credits

- [Maddy Makes Games and EXOK](https://github.com/EXOK/Celeste64): Celeste 64, the original game and its source
- [Noel Berry](https://github.com/FosterFramework/Foster): Foster framework
- [SDL](https://github.com/libsdl-org/SDL): Input, windowing and GPU
- FMOD Studio by Firelight Technologies: Audio

## Upstream projects

- <https://github.com/EXOK/Celeste64>
- <https://github.com/LowRiderXR/foster-visionos>
- <https://github.com/LowRiderXR/sdl-visionos>

---

This index only links to the developer's own repository. Automated checks and an AI safety check can miss things, and they can't confirm the port runs on Apple Vision Pro. Building runs the port's build scripts on your Mac with your permissions. You must own the game and supply your own legally obtained game files. [Report a problem](https://github.com/edgytoast/avp-ports-index/issues/new?template=report-entry.yml).

Curated by trevorbilt · [trevorbilt.com](https://trevorbilt.com)
