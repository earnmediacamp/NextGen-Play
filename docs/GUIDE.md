# NextGen Play guide

A short tour of what the app does and where to find it. Everything here is also reachable from the 3-dot menu > Settings.

## Library

- Three tabs: Folders, All videos, Favourites. Search is the magnifier.
- The sort button opens the library menu: view mode, grid or list, sort order and which details each row shows.
- Continue Watching sits at the top. Tap its header to fold it. Settings > List can turn it off.
- Videos you have not started show a NEW badge. Settings > List sets how many days it stays.
- Long-press a video or folder to select several. Folders can be hidden and brought back in Settings > General.

## Player gestures

| Gesture | What it does |
| :-- | :-- |
| Tap | Show or hide the controls (or play/pause, see Settings > Player > Controls) |
| Swipe left or right | Seek. Speed is set in Settings > Player > Navigation |
| Swipe up or down, left half | Brightness |
| Swipe up or down, right half | Volume |
| Double-tap the sides | Skip forward or back |
| Double-tap the middle | Play or pause |
| Press and hold | 2x speed. Keep your finger down and slide up or down to change the speed from 0.5x to 4x |
| Pinch | Zoom from 1x to 4x |
| Two fingers moving while zoomed | Pan |
| Double-tap while zoomed | Reset the zoom |

Every gesture has an on/off switch in Settings > Player > Controls. Lock mode can block everything or keep the volume and brightness swipes.

## Shortcut row

The small round buttons under the title: mute, sleep timer, night mode, frame back and forward, rotate, and optional ones for speed, screenshot, equalizer, mirror, vertical flip, repeat, shuffle and A-B repeat. The arrow at the start folds the whole row. Each button can be turned on or off in Settings > Player > Controls.

## Subtitles

- Formats: SRT, VTT and ASS/SSA. Animated ASS is a switch in Settings > Subtitle.
- Text size, colour, bold, border, background, alignment and bottom margin are in Settings > Subtitle. Font and font folder are in the player's subtitle panel.
- Several people speaking at once stack in one box instead of overlapping.
- Subtitles stay where they are when the controls appear. Settings > Subtitle > Layout can move them up instead.
- Character encoding, default sync and the italic and force-LTR effects are also in Settings > Subtitle.

## Translation

- The Translate panel in the player translates the current subtitles. Hinglish means Hindi written in English letters.
- It sends only the subtitle text to Google Translate, and only after you allow it. The switch is in Settings > Privacy.
- Styled ASS subtitles and picture subtitles cannot be translated.

## Audio

- Equalizer, volume boost, audio delay and the preferred audio language are in the player and in Settings > Audio.
- Audio delay can be remembered per video.

## Decoder

Settings > Decoder picks HW, HW+ or SW for local files and for network streams.

- HW: the phone's hardware decoders. FFmpeg only when the phone has none for that format.
- HW+: hardware video with FFmpeg preferred for audio (AC3, EAC3, DTS, TrueHD and others).
- SW: software video decoders.

If a decoder fails, the player tries the next one and shows a short message. Long-press the HW chip in the player to see exactly which decoder is running.

## Background play

Settings > Player > Playback > Background play keeps the audio going when you leave the app, with notification buttons. Picture in picture is skipped while it is on.

## Settings map

List, Player (Screen, Controls, Navigation, Playback), Decoder, Audio, Subtitle, General, Privacy, Development.

- General: theme and accent colour, hidden folders, update check, reset.
- Development: log viewer, and export or import of settings, favourites and hidden folders.

## Updates and privacy

The app checks for a new version about once a day and offers it from the Releases page. The privacy policy and open-source licences are in Settings > Privacy.
