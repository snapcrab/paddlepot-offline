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
