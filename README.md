# Obtainium Emulation Pack

**(Forked from: https://github.com/RJNY/Obtainium-Emulation-Pack)**

An [Obtainium](https://github.com/ImranR98/Obtainium) import file that adds popular Android
emulation applications to Obtainium.

To get started, navigate to releases and download the latest obtainium-emulation-back.json.
Finally; import file with Obtainium.

Adds the following to auto pull:

- Daijishou
- Dolphin (Development Versions)
- DuckStation (Beta Version)
- EKA2L1
- Key Mapper
- Lime3DS
- MelonDS (stable)
- MelonDS (nightly)
- NetherSX2 Patch [TRACK ONLY]
- PPSSPP
- RetroArch (AArch64) (nightly)
- ScummVM
- Ship of Harkinian (Zelda - OOT Port)
- 2 Ship 2 Harkinian (Zelda - MM Port)
- Turnip Drivers [TRACK ONLY]
- Vita3K
- Winlator
... and Obtainium of course

### What if I want to pick-and-choose what I install
The maintainer of Obtainium also hosts a collection of Crowdsourced app configurations.
[apps.obtainium.imranr.dev](https://apps.obtainium.imranr.dev)

### Why do some applications say TRACK ONLY?
As the name implies, these application versions are only tracked, not pulled. This was done because we _can't_ pull these resources, but you may still care to know when these resources have updates so you can pull them manually. For example: NetherSX2 can't provide an APK for legal reasons, but you'll get update notifications so you don't have to manually check or be stuck with outdated resources.

### How do I use TRACK ONLY resources?
When you get notified of an update to your track only resource:
- visit the link to your resource
- download it manually
- in obtainium > click resource > click "Mark Updated"

### I don't like <resource>, or <resource> is incompatible with my device.
No problem. Keep what you like, remove the rest!

### What happened to Citra / Yuzu?
These repositories [no longer exist](https://twitter.com/yuzuemu/status/1764733659444064671) due to a [lawsuit](https://storage.courtlistener.com/recap/gov.uscourts.rid.56980/gov.uscourts.rid.56980.10.0.pdf) by Nintendo against Tropic Haze LLC (former maintainers of Citra & Yuzu). Links to broken repositories cause errors in obtainium; and so, they were removed from this export script.

### A note about stable, nightly and canary versions of the same app
You cannot install more than one version of the same app. For example: You must choose between RetroArch (stable) or RetroArch (nightly). You cannot have both.

### How does this work?
Obtainium allows you to filter for links on a page using regular expression (regex)
It also allows you to follow multiple links using regex.
see https://regexr.com/7rmf7 for a basic example of how this works.

### Can this break?
Yes. Absolutely it can.
Any of the scrapers that use regex can break if the maintainer changes their page.
The applications pulling from GitHub are more stable and less likely to break.
