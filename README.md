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
