<p align="center"><img src="docs/screenshots/banner.png" alt="NextGen Play"></p>

<p align="center">
An offline video player for Android with gesture controls, full ASS subtitles and Hinglish subtitle translation.
</p>

## Preview

<table>
  <tr>
    <td width="25%"><img src="docs/screenshots/01-library.png" width="100%" alt="Library"></td>
    <td width="25%"><img src="docs/screenshots/03-settings.png" width="100%" alt="Settings"></td>
    <td width="25%"><img src="docs/screenshots/04-decoder.png" width="100%" alt="Decoder"></td>
    <td width="25%"><img src="docs/screenshots/05-hinglish.png" width="100%" alt="Hinglish subtitles"></td>
  </tr>
</table>

<p align="center"><img src="docs/screenshots/02-player.png" width="100%" alt="Player"></p>

<p align="center"><sub>Preview images show the app's layout with sample content. They are illustrations, not captures of a real library. Tap an image to see it larger.</sub></p>

## What it is

NextGen Play plays video files on your phone and links you type in yourself. It has no accounts. It uses anonymous Firebase Analytics counts (installs, active users, app version, country); no video names or file paths are sent. It is free and shows ads from Unity LevelPlay on the video list. It is built on Media3 / ExoPlayer.

## Highlights

- **Gestures:** swipe to seek, volume and brightness, double-tap, press and hold for 2x (slide up or down to change the speed), pinch to zoom and pan
- **Subtitles:** SRT, VTT and ASS/SSA with animated rendering, delay, styling, fonts and auto sync
- **Translation:** optional subtitle translation, including Hinglish (Hindi in English letters). It asks for permission first
- **Decoders:** HW, HW+ and SW modes with automatic fallback when one fails
- **Audio:** equalizer, volume boost, audio delay and remembered audio language
- **Playback:** background play with notification controls, picture in picture, resume, sleep timer, A-B repeat
- **Library:** folders, search and favourites, with a full Settings screen
- **Folder tools:** select several folders, delete, move, copy, rename, pin to top, hide, mark watched, properties
- **Recycle bin:** deleted videos (with their subtitles) wait for 7 to 60 days and can be restored
- **Private vault:** hide videos behind a PIN, out of the library and other gallery apps
- **Earphones:** audio calibration saved separately for each Bluetooth or wired output
- **Tools:** log viewer, settings export and import, and a Report a problem form (email with up to 4 screenshots)

A short tour of every feature is in the [guide](docs/GUIDE.md).

## Ads

NextGen Play is free and supported by ads from Unity LevelPlay: one banner at the bottom of the video list, and one full-screen video ad at most once every 40 minutes, after you come back to the list from the player. You can also watch a short rewarded video ("Go ad-free") to remove ads for 6, 12 or 24 hours. Ads only appear on the video list and never during playback.

## Download

Get the latest APK from the [Releases page](../../releases/latest). Android may show a Play Protect prompt for apps installed outside the Play Store. The app updates itself from the same page.

## Built with, and credits

NextGen Play stands on the work of these people and projects. Thank you.

| Project | By | Used for | Licence |
| :-- | :-- | :-- | :-- |
| [Media3 / ExoPlayer](https://github.com/androidx/media) | Google | Playback engine, player UI, HLS | Apache-2.0 |
| [libass](https://github.com/libass/libass) | libass contributors | ASS/SSA subtitle rendering | ISC |
| [ass-media](https://github.com/peerless2012/libass-android) | peerless2012 | Connects libass to Media3 | MIT |
| [FFmpeg](https://ffmpeg.org) | FFmpeg developers | Audio decoders (LGPL build, no GPL or non-free parts) | LGPL-2.1+ |
| AndroidX Core, SwipeRefreshLayout | Google | Update install, pull to refresh | Apache-2.0 |
| [Poppins](https://github.com/itfoundry/poppins) | Indian Type Foundry | Bundled font | SIL Open Font License 1.1 |
| [bsdiff](https://www.daemonology.net/bsdiff/) | Colin Percival | Small patch updates | BSD |
| Unity LevelPlay and Unity Ads SDK | Unity Technologies | Ads (Unity Ads and ironSource Ads networks) | Proprietary, used under Unity's terms |
| Firebase Analytics | Google | Anonymous usage counts | Apache-2.0 SDK, service terms |
| Google Translate web service | Google | Optional subtitle translation (service only) | Service terms |

Full notes are in [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md), and the same list is inside the app under Settings > Privacy. The logo is by the project owner.

## Privacy

Your videos, history, favourites and settings stay on your device. Things that go online: the update check, anonymous Firebase Analytics usage counts, links you enter yourself, subtitle text if you allow translation, and ads. The ads are provided by Unity LevelPlay, which mediates Unity Ads and ironSource Ads. These networks may use your advertising ID, IP address and approximate device information to choose and measure ads. You can reset or disable your advertising ID in your phone's Settings > Privacy > Ads. Read the full policy in the app under Settings > Privacy.

## Disclaimer

NextGen Play does not provide, host or link to any video content. It plays files on your device and links you enter yourself. You are responsible for having the right to play and use the content you open. NextGen Play is not affiliated with or endorsed by Google, FFmpeg, Unity or any other project or company named here.

## Licence

NextGen Play's own source code is released under the **MIT License**. The full text is in [LICENSE](LICENSE). The projects it uses keep their own licences, listed in [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md). The Unity LevelPlay and Unity Ads SDKs are closed source and are not part of this repository.

The FFmpeg decoders are LGPL-2.1+. Their source tag and the build script (`tools/build_ffmpeg_lgpl.sh`) are in this repository, so you can rebuild them.

Copyright (c) 2026 Abhi (NextGen Play).
