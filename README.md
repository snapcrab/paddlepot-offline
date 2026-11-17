# PaddlePot Offline

Run a doubles pickleball Mixer or King of the Court session in your browser.

- [Open the Mixer](https://snapcrab.github.io/paddlepot-offline/paddlepot-offline.html)
- [Download the HTML](https://github.com/snapcrab/paddlepot-offline/releases/latest/download/paddlepot-offline.html)
- [Download the ZIP](https://github.com/snapcrab/paddlepot-offline/releases/latest/download/paddlepot-offline.zip)
- [Read the Mixer user guide](./paddlepot-offline-user-guide.html)
- [Open the standalone King of the Court file](./paddlepot-kotc-offline.html)
- [Read the King of the Court user guide](./paddlepot-kotc-offline-user-guide.html)

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

For offline use, download the HTML or extract it from the ZIP, then open it in a compatible browser that can run local HTML files. Before relying on it at court, turn on airplane mode and try starting a Mixer and saving a score on the device you’ll use.

Scores and session data stay in the browser. The hosted page and a local copy may have separate saves, and browsers don’t sync those saves between devices. To move a session, choose **Settings → Back up JSON** in the original copy, then choose **Restore JSON** in the destination copy (on the setup screen or in Settings). Restore replaces any session already open there, so back it up first if you want to keep it.

The [MIT licence](./LICENSE) covers the original Mixer code. It allows use, adaptation and sharing, including commercial use, as long as the licence and copyright notice are kept with copies or substantial portions of the code. The PaddlePot name and logo and the user guides are outside that grant. The embedded Inter, JetBrains Mono and Space Grotesk fonts are under the SIL Open Font License 1.1; their notices are in the HTML.

See [Contributing](./CONTRIBUTING.md) to report a bug, share an idea or help improve the Mixer.

Click the PaddlePot logo or name in the Mixer header to go to the [PaddlePot homepage](https://paddlepot.app/).

## King of the Court Offline v0.1.0

Open [the standalone KOTC HTML](./paddlepot-kotc-offline.html) from your device in a compatible browser. Enter player names and at least two courts, then preview the opening round. Allow four players per court. Save scores as games finish and check the next round's court assignments and sit-outs before starting it. You can correct scores until you advance or end the session.

Wait order fills the available court spots. Players who sat out get first priority, followed by players returning from a break, then everyone else in wait order. Ladder position determines court assignment. Add late arrivals from **Players** to put them at the bottom of the ladder. Returning players keep their positions. Under **Results**, each player's longest streak counts consecutive completed games on Court 1. A sit-out pauses the streak.

KOTC saves separately in the browser. Use **Settings → Back up JSON** to download a KOTC backup and **Restore JSON** from setup or Settings to load it. Restoring replaces the open KOTC session. Use the app that created the backup when restoring a Mixer or KOTC session.

## Mixer v1.4.5

Use **Release allocation** on an unscored court to cancel the game. Available players return to their racks or waiting queue with their previous wait priority. The allocation is removed from game history. A court marked unavailable stays unavailable when released.

## King of the Court Offline v0.2.0

Set up a session by player count or by name. In **Players → Add player**, leave the name blank to assign the next player number. Use the availability switches to manage who can play in the next round.

Use **Release allocation** before saving any score for the round. Add players or switch players to unavailable, then review and restart the same round. Completed rounds and ladder movement carry forward.

## King of the Court Offline v0.2.1

KOTC uses Mixer's layout, logo, local save indicator, embedded fonts, tabs and court cards. Partners appear as **Player 3 & Player 1**. Log each court's score from its card or save all entered scores from the Play tab.

## HTML user guides

The [Mixer guide for v1.4.5](./paddlepot-offline-user-guide.html) covers releasing an unscored court. The [King of the Court guide for v0.2.1](./paddlepot-kotc-offline-user-guide.html) covers round setup, rotation, release and results.

Save a guide's HTML file to read it offline. Keep it beside the matching app HTML if you want the guide's **Open** link to work from a local copy.
