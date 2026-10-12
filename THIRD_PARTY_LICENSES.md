# Third-party licences

NextGen Play is released under the GNU General Public License v3.0 (see `LICENSE`). It uses the projects below. Their licences stay with them.

| Project | Author | Licence | Where to read it |
| :-- | :-- | :-- | :-- |
| Media3 / ExoPlayer | Google | Apache License 2.0 | https://github.com/androidx/media |
| AndroidX Core, SwipeRefreshLayout | Google | Apache License 2.0 | https://developer.android.com/jetpack/androidx |
| libass | libass contributors | ISC | https://github.com/libass/libass |
| ass-media | peerless2012 | See its repository | https://github.com/peerless2012 |
| NextLib (FFmpeg decoders for Media3) | Anil Kumar Beesetti | GPL-3.0 | https://github.com/anilbeesetti/nextlib |
| FFmpeg | FFmpeg developers | Depends on how it is built. NextLib documents its build | https://ffmpeg.org |
| Poppins (font) | Indian Type Foundry | SIL Open Font License 1.1 | https://github.com/itfoundry/poppins |
| bsdiff (patch format) | Colin Percival | BSD | https://www.daemonology.net/bsdiff/ |

## Notes

- **Why GPL-3.0.** NextLib is GPL-3.0. A program that includes it and is shared with other people has to be shared under GPL-3.0 too, with the source available. The source of NextGen Play is in this repository.
- **Fonts.** Poppins is bundled in the app (`app/src/main/assets/fonts`). The Open Font License allows this. The font keeps its own licence and its authors' copyright notice, which are in the Poppins repository linked above.
- **Patch updates.** The app reads patches in the bsdiff format with its own code. Only the format and the idea come from bsdiff.
- **Translation.** Optional subtitle translation sends subtitle text to the Google Translate web service. No Google code is included, and the service has its own terms. The address it uses is unofficial and can change or stop.
- **Names.** Product and company names belong to their owners and are used only to say what the app is built with.
- **To check before publishing.** The licence of ass-media is not stated here, and the exact build licence of the FFmpeg inside NextLib should be read on NextLib's page.
