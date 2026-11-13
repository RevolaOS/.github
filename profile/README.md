# RevolaOS

Apple's original iPod Classic firmware with a small core and on-device extensions. Based on 2.0.5 for the 6G, 6.5G and 7G.

Extensions are files on the iPod, turned on and off in Settings. An extension that is off is not loaded and uses no RAM. RAM comes first in every decision and one extension does one thing; the full rules are in STYLE.md.

| Repository | What it holds |
|---|---|
| [revola](https://github.com/RevolaOS/revola) | Core firmware, extension loader, SDK, documentation |
| [extensions](https://github.com/RevolaOS/extensions) | First-party extensions |
| [homebrew](https://github.com/RevolaOS/homebrew) | First-party games and apps |
| [themes](https://github.com/RevolaOS/themes) | First-party themes and the theme compiler |
| [reversing](https://github.com/RevolaOS/reversing) | Apple firmware documentation and symbols |
| [installer](https://github.com/RevolaOS/installer) | Desktop installer and device tools |
| [emulator](https://github.com/RevolaOS/emulator) | QEMU fork and `ipodvm` |
| [repriseos-heritage](https://github.com/RevolaOS/repriseos-heritage) | Archived mirror of RepriseOS at the fork point |

| Page | Contents |
|---|---|
| Installing, extensions, recovery | [User guide](https://github.com/RevolaOS/revola/tree/main/docs/guide) |
| Core internals and the SDK | [Developer documentation](https://github.com/RevolaOS/revola/tree/main/docs) |
| Principles, documentation and code rules | [STYLE.md](https://github.com/RevolaOS/.github/blob/main/STYLE.md) |

## Development

Large language models are used for much of the coding on RevolaOS. Their output is checked in the emulator, its memory use comes from the heap profile, and every release is tested on an iPod before it ships. Contributions written with the same tools are welcome and tested in the same way.

RevolaOS is derived from [RepriseOS](https://github.com/lgreitis/osos-lab). See the NOTICE file in each repository.
