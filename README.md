# The Masque of the Last Sunset: iPad table app

An offline web app (PWA) with the same content as the Table Edition PDF, built for navigating at the table.

## Installing on the iPad (one-time, needs internet)
1. Host this folder on any HTTPS address (GitHub Pages, Netlify, Cloudflare Pages).
2. On the iPad, open the address in **Safari**, then tap **Share → Add to Home Screen**.
3. Open the app from the home screen once, while online, so it caches everything.

After that it runs fullscreen and fully offline.

## At the table
- **Sidebar:** every section, grouped Prepare / Run / Clues / Cast / Places / Players. In portrait, tap ☰ to open it.
- **Search (⌕):** names, places, clue text. Tap a result to jump to it; the target flashes.
- **Back (‹):** returns from any jump, since the installed app has no browser back button.
- **Top bar:** tap the Red and Amber segments to advance the clocks. "Burnt" counts destroyed copies; tap it to open the tracker.
- **Tick boxes:** every box is tappable. Ticking a clue on the Clue Web page rings that clue's badges green everywhere, including the clue map and the indexes.
- **PC sheets:** wealth boxes are tappable, and the injury and disorder lines are writable. Clocks & Tracker has a free **Table Notes** box.
- **Show to players:** on player pages, this hides the GM chrome (clocks and sidebar).
- **New session:** clears all ticks, notes and clocks.

Everything is saved on the iPad itself and nothing leaves the device.

## Updating
Rebuild the app, upload the folder again, then open the app while online. It picks up the new version on the next launch.
