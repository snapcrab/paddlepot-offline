# PaddlePot Offline

A doubles pickleball Mixer you can run in your browser.

- [Open the Mixer](https://snapcrab.github.io/paddlepot-offline/paddlepot-offline.html)
- [Download the HTML](https://github.com/snapcrab/paddlepot-offline/releases/latest/download/paddlepot-offline.html)
- [Download the ZIP](https://github.com/snapcrab/paddlepot-offline/releases/latest/download/paddlepot-offline.zip)
- [Read the user guide (PDF)](./paddlepot-offline-user-guide.pdf)

## Features

- **v1.3.0** Optional winner and loser racks for remixes.
- **v1.4.0** Add courts during play from the Courts tab.
- **v1.4.1** Saved scores show green for wins, red for losses, and grey for draws.
- **v1.4.2** Open rack players can join Winner or Loser games with the same wait-time priority.
- **v1.4.3** Choose Winner and Loser racks when setting up a new session.
- **v1.4.3** Updated the user guide for split racks, adding courts, and saved-score colours.

## Community release v1.4.4

PaddlePot Offline is a standalone doubles Mixer for clubs and volunteers. Use it to run games, rotate players and keep a leaderboard on your device.

- [Open in browser](https://snapcrab.github.io/paddlepot-offline/paddlepot-offline.html) (internet needed to load)
- [Download HTML](https://github.com/snapcrab/paddlepot-offline/releases/download/v1.4.4/paddlepot-offline.html)
- [Download ZIP](https://github.com/snapcrab/paddlepot-offline/releases/download/v1.4.4/paddlepot-offline.zip) (HTML, licence and guide)
- [User guide v1.4.4 (PDF)](https://github.com/snapcrab/paddlepot-offline/releases/download/v1.4.4/paddlepot-offline-user-guide.pdf)

For offline use, download the HTML or extract it from the ZIP, then open it in a compatible browser that can run local HTML files. Before relying on it at court, turn on airplane mode and try starting a Mixer and saving a score on the device you’ll use.

Scores and session data stay in the browser. The hosted page and a local copy may have separate saves, and browsers don’t sync those saves between devices. To move a session, choose **Settings → Back up JSON** in the original copy, then choose **Restore JSON** in the destination copy (on the setup screen or in Settings). Restore replaces any session already open there, so back it up first if you want to keep it.

The [MIT licence](./LICENSE) covers the original Mixer code. It allows use, adaptation and sharing, including commercial use, as long as the licence and copyright notice are kept with copies or substantial portions of the code. The PaddlePot name and logo and the PDF guide are outside that grant. The embedded Inter, JetBrains Mono and Space Grotesk fonts are under the SIL Open Font License 1.1; their notices are in the HTML.

See [Contributing](./CONTRIBUTING.md) to report a bug, share an idea or help improve the Mixer.

Click the PaddlePot logo or name in the Mixer header to go to the [PaddlePot homepage](https://paddlepot.app/).

## King of the Court Offline v0.1.0

Open [the standalone KOTC HTML](./paddlepot-kotc-offline.html) from your device in a compatible browser. Enter player names and at least two courts, then preview the opening round. Allow four players per court. Save scores as games finish and check the next round's court assignments and sit-outs before starting it. You can correct scores until you advance or end the session.

Wait order fills the available court spots. Players who sat out get first priority, followed by players returning from a break, then everyone else in wait order. Ladder position determines court assignment. Add late arrivals from **Players** to put them at the bottom of the ladder. Returning players keep their positions. Under **Results**, each player's longest streak counts consecutive completed games on Court 1. A sit-out pauses the streak.

KOTC saves separately in the browser. Use **Settings → Back up JSON** to download a KOTC backup and **Restore JSON** from setup or Settings to load it. Restoring replaces the open KOTC session. Use the app that created the backup when restoring a Mixer or KOTC session.
