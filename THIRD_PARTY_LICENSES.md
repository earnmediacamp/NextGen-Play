# Third-party licences

NextGen Play's own code is released under the MIT License (see `LICENSE`). It uses the projects below. Their licences stay with them and are not changed by the MIT License.

| Project | Author | Licence | Where to read it |
| :-- | :-- | :-- | :-- |
| Media3 / ExoPlayer | Google | Apache License 2.0 | https://github.com/androidx/media |
| AndroidX Core, SwipeRefreshLayout | Google | Apache License 2.0 | https://developer.android.com/jetpack/androidx |
| libass | libass contributors | ISC | https://github.com/libass/libass |
| ass-media, ass-kt | peerless2012 | MIT | https://github.com/peerless2012/libass-android |
| FFmpeg (audio decoders, LGPL build) | FFmpeg developers | LGPL-2.1-or-later | https://ffmpeg.org |
| Poppins (font) | Indian Type Foundry | SIL Open Font License 1.1 | https://github.com/itfoundry/poppins |
| bsdiff (patch format) | Colin Percival | BSD | https://www.daemonology.net/bsdiff/ |
| Start.io SDK (ads) | Start.io | Proprietary, used under Start.io's terms | https://www.start.io |
| Google Translate web service | Google | Service terms (no code included) | https://policies.google.com/terms |

## Notes

- **FFmpeg (LGPL).** The app uses FFmpeg audio decoders through Media3's FFmpeg decoder module. FFmpeg is built from the official source, tag `n6.0`, without `--enable-gpl` and without `--enable-nonfree`. The build script (`tools/build_ffmpeg_lgpl.sh`) stops if either is switched on. The decoders ship as shared libraries inside the APK. The FFmpeg source is at https://git.ffmpeg.org/ffmpeg.git (tag `n6.0`), and the exact build steps are in this repository, so you can rebuild the libraries and the app yourself. FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project.
- **Audio format patents.** Some audio formats (for example AC3, E-AC3, DTS and TrueHD) are covered by patents in some countries. The app is provided as is, with no patent licence from the author.
- **Start.io SDK.** The SDK is closed source and is not part of this repository. It is added at build time from Start.io's package repository and is used under Start.io's terms. It is the reason the app shows ads. See the privacy policy in Settings > Privacy.
- **Fonts.** Poppins is bundled in the app (`app/src/main/assets/fonts`). Copyright 2020 The Poppins Project Authors (https://github.com/itfoundry/Poppins). It is licensed under the SIL Open Font License 1.1, which allows bundling. The licence text (`OFL.txt`) is kept with the font.
- **Patch updates.** The app reads patches in the bsdiff format with its own code. Only the format and the idea come from bsdiff.
- **Translation.** Optional subtitle translation sends subtitle text to the Google Translate web service, only after you allow it. No Google code is included, and the service has its own terms. The address it uses is unofficial and can change or stop.
- **Names.** Product and company names belong to their owners and are used only to say what the app is built with. NextGen Play is not affiliated with or endorsed by any of them.
