# SheikahVision

**The Legend of Zelda: Breath of the Wild** · originally on Other (2017)
Port by [@zlinoliver](https://github.com/zlinoliver)

Start with this command, which gets exactly the code that was scanned:

```
git clone https://github.com/zlinoliver/BotW-SheikahVision && cd BotW-SheikahVision && git checkout d5a8f69f355a129c02580bd4c95a0791822c6bec && git submodule update --init --recursive
```

Then follow the [install guide](https://github.com/zlinoliver/BotW-SheikahVision/blob/d5a8f69f355a129c02580bd4c95a0791822c6bec/AVP-INSTALL.md) from its build steps. Skip only its step that clones or downloads this repo, which would fetch newer code that may not have been scanned; keep every other step, including dependency downloads.

| | |
| --- | --- |
| Trust | Developer-verified |
| Status | Developer-verified: Beta. The developer plays it through end to end on Apple Vision Pro \(M5, visionOS 27\); M2 untested. Needs PS VR2 Sense controllers. The Mac installer in Releases builds the app on your Mac from your own game files; it holds no game data and no prebuilt Vision Pro app. |
| Plays as | 6DoF immersive |
| Health | OK |
| Scan | Scanned 2026-11-19 · 0 commits since |
| Source (scanned) | [zlinoliver/BotW-SheikahVision at d5a8f69f355a](https://github.com/zlinoliver/BotW-SheikahVision/tree/d5a8f69f355a129c02580bd4c95a0791822c6bec) |
| Install guide | [AVP-INSTALL.md at d5a8f69f355a](https://github.com/zlinoliver/BotW-SheikahVision/blob/d5a8f69f355a129c02580bd4c95a0791822c6bec/AVP-INSTALL.md) |
| Repo | [zlinoliver/BotW-SheikahVision](https://github.com/zlinoliver/BotW-SheikahVision) |
| Developer site | <https://sheikahvision.com> |
| License | Custom license |
| Last commit | 2026-11-19 |
| visionOS | 26.0 or later |
| Input | game controller |
| Tags | zelda, breath-of-the-wild, wiiu, vr, static-recompilation, motion-controls |

Breath of the Wild in first-person VR on Apple Vision Pro, running natively on the headset: the Wii U executable is statically recompiled on your Mac, graphics run on Metal, motion controls follow BetterVR. No emulator, no PC, no streaming.

## Screenshots

From the port's README at d5a8f69f355a.

<img src="https://raw.githubusercontent.com/zlinoliver/BotW-SheikahVision/d5a8f69f355a129c02580bd4c95a0791822c6bec/docs/images/controls.png" alt="Controls: both PS VR2 Sense controllers and the body gestures" width="400">
<img src="https://raw.githubusercontent.com/zlinoliver/BotW-SheikahVision/d5a8f69f355a129c02580bd4c95a0791822c6bec/docs/images/architecture.png" alt="Architecture: static recompilation on the Mac, then the VR layer, game logic, Wii U runtime, graphics and visionOS on the headset" width="400">

## Credits

- [zlinoliver](https://github.com/zlinoliver/BotW-SheikahVision): SheikahVision, the visionOS port and Mac installer
- [Crementif](https://github.com/Crementif/BotW-BetterVR): BetterVR, the PC VR mod whose methods and research the VR layer follows
- [Ishaan Kalra](https://github.com/IshaanKalra2103/BotWRecomp): BotWRecomp, the static recompilation this port is built on
- [Cemu](https://github.com/cemu-project/Cemu): Latte, the graphics layer, running on Metal
- [Glovebox](https://github.com/glovebox-vr/glovebox): Glovebox, the Mac installer SheikahVision's installer is modelled on
- Nintendo: Original game

## Upstream projects

- <https://github.com/IshaanKalra2103/BotWRecomp>
- <https://github.com/Crementif/BotW-BetterVR>

---

This index only links to the developer's own repository. Automated checks and an AI safety check can miss things, and they can't confirm the port runs on Apple Vision Pro. Building runs the port's build scripts on your Mac with your permissions. You must own the game and supply your own legally obtained game files. [Report a problem](https://github.com/edgytoast/avp-ports-index/issues/new?template=report-entry.yml).

Curated by trevorbilt · [trevorbilt.com](https://trevorbilt.com)
