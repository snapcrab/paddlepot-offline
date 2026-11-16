# paddlepot-offline

## v1.0.0 · Offline doubles Mixer

Download [paddlepot-offline.html](./paddlepot-offline.html) and open it directly in your browser. The file includes everything needed to run the Mixer offline.

1. Enter one distinct player name per line, choose the court count, and select **Start Mixer** to assign the first games.
2. Enter both scores and select **Save score**. The court opens immediately and the leaderboard updates from completed games.
3. Select **Use open courts** to remix available courts while others are playing, or **Wait for all courts** to wait for every in-play score. Select **Remix courts** when ready.
4. Use **Correct score** in Results to update a saved result. The leaderboard shows games played, wins and point differential, and ranks players by wins, then point differential. A tied score counts as a game played for all four players.
5. Use **Back up JSON** to download the session, including in-play assignments and remix timing. **Restore JSON** loads a backup and asks before replacing an active session.

The Mixer gives available players with fewer assignments first opportunity to play, then favours those who have waited longer since their last assignment. It looks for less frequent and less recent teammates and opponents within those priorities.

The session saves in the current browser profile. Reopen the same HTML file from the same location to resume. Browsers can handle local-file storage differently, so use a JSON backup to move between file locations, browsers or devices.

Any decision to replace free public session creation on paddlepot.app belongs to a later rollout.

## v1.1.0 · Classic PaddlePot theme and player entry

The Offline Mixer uses the Classic dark palette, original PaddlePot logo, and Inter, Space Grotesk, and JetBrains Mono. The logo and fonts are embedded in the HTML.

Choose **Number of players** to create Player 1, Player 2, and so on. Type a count from 4 to 200 or use the **−** and **+** buttons. Choose **Enter player names** to paste or type one distinct name per line.

The session uses the Classic swipeable navigation on phones. **Play** has scores and remix controls, **Players** shows the roster and who is waiting, **Leaderboard** ranks players, **Stats** shows alphabetical totals, **Courts** shows court availability, and **Results** contains score corrections. Find JSON backup, restore, and New session under **Settings**. You can also restore a backup from setup. v1.0.0 JSON backups still work.

## v1.2.0 · Availability and player match history

Use the switches in **Players** to take players out of the next mix or make them available again. Use **+ Add player** to enter a name or leave it blank for the next unused player number. New players are available for the next mix. **Players** shows completed games under each name, and **Play** shows that count in brackets for waiting players.

In **Courts**, choose **D** to open a court for doubles or **U** to make it unavailable. Players and courts marked unavailable can finish and score games already in play. The **Mode** card controls remix timing.

Tap a name in **Leaderboard** to see all of that player's completed matches with partners, opponents, courts and scores. The leaderboard also shows games played and each player's win, loss and draw record. This replaces the separate Stats tab.

Player and court availability is saved locally and included in JSON backups. Earlier backups restore with all players and courts available.

## Download PaddlePot Offline

- [Download the standalone HTML](https://github.com/snapcrab/paddlepot-offline/releases/latest/download/paddlepot-offline.html).
- [Download the ZIP](https://github.com/snapcrab/paddlepot-offline/releases/latest/download/paddlepot-offline.zip) if your phone adds a .txt extension. The ZIP contains one file, paddlepot-offline.html.

On iPhone, tap the ZIP in Files to unpack it. On Android, open the ZIP in Files by Google and tap **Extract**. Open the extracted HTML in a browser that can run local HTML files. Before relying on it courtside, try starting a Mixer and saving a score in airplane mode.

## Open PaddlePot in a browser

[Open PaddlePot Offline on GitHub Pages](https://snapcrab.github.io/paddlepot-offline/paddlepot-offline.html) to use the Mixer without downloading a file. This is the link to share on Facebook. The hosted page opens over the internet and saves the session in the current browser. Use JSON backup and restore to move a session between the hosted page and the downloaded file.
