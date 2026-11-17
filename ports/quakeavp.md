# QuakeAVP

**Quake** · originally on PC (1996)
Port by A.Cervantez ([@Ywach404](https://github.com/Ywach404))

Start with this command, which gets exactly the code that was scanned:

```
git clone https://github.com/Ywach404/QuakeAVP && cd QuakeAVP && git checkout d953ffee02c39307e1f56e0f622830ec489ca7d3 && git submodule update --init --recursive
```

Then follow the [install guide](https://github.com/Ywach404/QuakeAVP/blob/d953ffee02c39307e1f56e0f622830ec489ca7d3/AVP-INSTALL.md) from its build steps. Skip only its step that clones or downloads this repo, which would fetch newer code that may not have been scanned; keep every other step, including dependency downloads.

| | |
| --- | --- |
| Trust | Developer-verified |
| Status | Developer-verified: Bare hands or PSVR2 Sense, in a full immersive space. id1 and the two mission packs play; the 2021 rerelease episodes do not load yet. Bring your own pak files. |
| Plays as | 6DoF immersive |
| Health | OK |
| Scan | Scanned 2026-11-17 · 0 commits since |
| Source (scanned) | [Ywach404/QuakeAVP at d953ffee02c3](https://github.com/Ywach404/QuakeAVP/tree/d953ffee02c39307e1f56e0f622830ec489ca7d3) |
| Install guide | [AVP-INSTALL.md at d953ffee02c3](https://github.com/Ywach404/QuakeAVP/blob/d953ffee02c39307e1f56e0f622830ec489ca7d3/AVP-INSTALL.md) |
| Repo | [Ywach404/QuakeAVP](https://github.com/Ywach404/QuakeAVP) |
| License | GPL-2.0 |
| Last commit | 2026-11-17 |
| visionOS | 26.0 or later |
| Input | hand tracking, game controller |
| Tags | fps, first-person, vr, 6dof, quakespasm, id-tech-1, source-port, hand-tracking |

Quake built for Apple Vision Pro rather than ported onto it: QuakeSpasm's engine core with a native Metal renderer, single-pass foveated stereo, and hand tracking as a first-class input, so the whole game plays with no controller at all. Bring your own pak files.

## Screenshots

From the port's repo at d953ffee02c3.

<img src="https://raw.githubusercontent.com/Ywach404/QuakeAVP/d953ffee02c39307e1f56e0f622830ec489ca7d3/docs/media/weapon-wheel.gif" alt="Screenshot of QuakeAVP" width="400">
<img src="https://raw.githubusercontent.com/Ywach404/QuakeAVP/d953ffee02c39307e1f56e0f622830ec489ca7d3/docs/media/hand-viewing-modes.gif" alt="Screenshot of QuakeAVP" width="400">
<img src="https://raw.githubusercontent.com/Ywach404/QuakeAVP/d953ffee02c39307e1f56e0f622830ec489ca7d3/docs/media/phaseout-occlusion.gif" alt="Screenshot of QuakeAVP" width="400">

## Credits

- [Watch the devlog, the port running on a real Vision Pro](https://www.youtube.com/watch?v=-G4lDuGikJI): Video
- [A.Cervantez](https://github.com/Ywach404/QuakeAVP): The Apple Vision Pro port, the Metal renderer and the hand tracking
- [QuakeSpasm](https://github.com/sezero/quakespasm): The engine core
- [XcodeGen](https://github.com/yonaskolb/XcodeGen): Xcode project generation
- id Software: Original game

## Upstream projects

- <https://github.com/sezero/quakespasm>

---

This index only links to the developer's own repository. Automated checks and an AI safety check can miss things, and they can't confirm the port runs on Apple Vision Pro. Building runs the port's build scripts on your Mac with your permissions. You must own the game and supply your own legally obtained game files. [Report a problem](https://github.com/edgytoast/avp-ports-index/issues/new?template=report-entry.yml).

Curated by trevorbilt · [trevorbilt.com](https://trevorbilt.com)
