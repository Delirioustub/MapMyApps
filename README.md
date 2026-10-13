# MapMyApps

Personal map for places you share from Instagram, Pinterest, Facebook, and other apps.

Places stay in the browser on your phone. This repo is only the app shell.

## Phone setup

The app lives at `https://delirioustub.github.io/MapMyApps/`. Open it in Safari and use Share, Add to Home Screen.

Build the share sheet shortcut once (on any iPhone):

1. Open Shortcuts and tap + to make a new shortcut. Name it MapMyApps.
2. Tap the info (i) button and turn on Show in Share Sheet. Set it to receive URLs, Safari web pages, and text. If there is no input, choose Continue.
3. Add the action URL Encode. Its input should be Shortcut Input.
4. Add the action Open URLs. Type `https://delirioustub.github.io/MapMyApps/?add=` and then tap to insert the URL Encoded Text variable right after it.
5. Tap Done.

Share it with someone else: in Shortcuts, long press MapMyApps, tap Share, then Copy iCloud Link, and text that link. They open it, tap Add Shortcut, and MapMyApps shows up in the share sheet of Instagram, Facebook, Pinterest, TikTok, Safari, and other apps.

Using it: on a post, tap Share, then MapMyApps (scroll the app row or tap More the first time). The app opens and searches automatically. Tap the right place to save it. If only a link came through and no place is found, type the place name and tap Find place. Go opens Apple Maps directions.

Route appears when the selected list has two or more places. It shows the stops numbered in order on the map (starting from the newest saved place, then always the nearest next stop), with buttons to open the whole trip in Apple Maps or Google Maps.
