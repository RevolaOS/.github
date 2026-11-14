# RevolaOS

Apple's original iPod Classic firmware with a small core and on-device extensions. Based on 2.0.5 for the 6G, 6.5G and 7G.

Extensions are files on the iPod, turned on and off in Settings. An extension that is off is not loaded and uses no RAM. RAM comes first in every decision and one extension does one thing; the full rules are in STYLE.md.

## Screenshots
<img width="320" height="240" alt="ipodvm-screens-20261114-031322" src="https://github.com/user-attachments/assets/f288eec5-e31c-4412-9f3d-12628a2d8797" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031338" src="https://github.com/user-attachments/assets/a6d67377-38a7-4939-9567-c4b47f9e5b27" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031606" src="https://github.com/user-attachments/assets/dae6764e-8195-4377-9bdc-c7306b758e7f" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031623" src="https://github.com/user-attachments/assets/b1976da4-100b-458f-a433-fb7371538e2e" />
<img width="320" height="240" alt="ipodvm-screens-20261114-032317" src="https://github.com/user-attachments/assets/24cff263-8fd1-4103-a737-24b342208111" />
<img width="320" height="240" alt="ipodvm-screens-20261114-032313" src="https://github.com/user-attachments/assets/a8c06686-7dc9-46f5-becf-04a31e9b07ce" />
<img width="320" height="240" alt="ipodvm-screens-20261114-032300" src="https://github.com/user-attachments/assets/cc2f3612-8f1f-4874-85f4-e7505cf2cf1a" />
<img width="320" height="240" alt="ipodvm-screens-20261114-032007" src="https://github.com/user-attachments/assets/63e11ba5-47e5-4745-808c-b4232435a38c" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031722" src="https://github.com/user-attachments/assets/b99a5952-d945-4d82-b4ff-948840e23554" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031720" src="https://github.com/user-attachments/assets/1bfb1bdd-17e8-4bd1-b46b-9b3bb77f105e" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031649" src="https://github.com/user-attachments/assets/3a8b5cdb-992d-40ca-aa03-dfac2345900a" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031641" src="https://github.com/user-attachments/assets/9e6198f3-c625-46a3-97b6-fa7e4667bc1b" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031519" src="https://github.com/user-attachments/assets/08539b94-6455-46b5-9d76-f7be30eeb484" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031430" src="https://github.com/user-attachments/assets/7494f133-2ad6-4cf5-9684-ae99de4e670b" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031409" src="https://github.com/user-attachments/assets/bb5c00ba-7cf1-4391-a82d-e4ecd78fe4ad" />
<img width="320" height="240" alt="ipodvm-screens-20261114-031356" src="https://github.com/user-attachments/assets/66d55b31-e66e-4324-98d2-7c8d17db8143" />

## Repository

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
