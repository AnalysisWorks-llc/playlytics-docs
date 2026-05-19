# Import from GameChanger

## Overview

Playlytics can import your existing roster and season statistics from a GameChanger CSV export. This lets coaches bring years of historical data into Playlytics immediately — no re-logging required.

Imported stats are stored separately from Playlytics-logged game data and combined intelligently in analytics — so coaches can import from GameChanger and continue logging in Playlytics simultaneously without double-counting.

## How to Export from GameChanger

1. Go to **web.gc.com** and sign in
2. Select your team
3. Navigate to the **Stats** section
4. Scroll to the bottom of the page
5. Click **Export Stats**
6. Save the CSV file to your device

The export must be done from the GameChanger website — not the mobile app. The web export includes the full stats format Playlytics requires.

## How to Import into Playlytics

1. Go to **Settings → Import from GameChanger**
2. Tap the upload area or drag and drop your CSV file
3. Playlytics reads the file and detects all players automatically
4. Review the roster matching screen
5. Select import options
6. Confirm and import

The import is completed entirely on your device — no server processing required. Most imports complete in seconds.

## Roster Matching

Playlytics automatically matches GameChanger players to your existing Playlytics roster using a priority system:

| Match Type | How It Works |
|------------|-------------|
| **Exact** | First name and last name match exactly |
| **Partial** | Last name matches and first initial matches |
| **Jersey #** | Jersey number matches when name does not |
| **New** | No match found — player will be created |

For partial and jersey matches a dropdown appears letting you manually select the correct Playlytics player or create a new one.

### Guest Players

Players in your GameChanger export who are not on your current roster appear as new players. You can choose whether to add them to your team roster or import their stats only as guest players.

Guest players imported as guests only:
- Their stats appear in analytics with a **(guest)** indicator
- They do not appear on your roster screen
- Their stats are included in team leaderboards

## Import Options

After reviewing roster matching you can choose which stat categories to import:

- **Roster** — always included, creates or updates player records
- **Batting Stats** — AVG, OBP, SLG, OPS, H, HR, RBI, SB, LD%, GB%, FB% and more
- **Pitching Stats** — ERA, IP, W/L/S, WHIP, K, BB and more (only for players who pitched)
- **Fielding Stats** — FLD%, TC, PO, A, E, DP, PB, and innings played by position

## Viewing Imported Stats

After importing use the **Imported** filter on any analytics screen to view stats from GameChanger specifically. The filter appears alongside All, Game, Team Practice, and Individual filters.

### How filters work with imported data

| Filter | What It Shows |
|--------|--------------|
| **All** | GameChanger stats + all Playlytics logged data combined |
| **Game** | GameChanger stats + Playlytics logged game data combined |
| **Team Practice** | Playlytics logged practices only |
| **Individual** | Playlytics logged individual sessions only |
| **Imported** | GameChanger season totals only |

GameChanger data is treated as game data — it belongs in the Game filter alongside Playlytics-logged games.

### Combined stat calculations

When both GameChanger and Playlytics data exist for a player:

- **Counting stats** (H, AB, HR, RBI, TC, E etc.) are added together
- **Rate stats** (AVG, OBP, FLD% etc.) are recalculated from the combined counting stats
- **Contact quality** (LD%, GB%, FB%) uses Playlytics logged data when available, GameChanger percentages as fallback
- **Fielding percentage** uses GameChanger's calculation directly when no Playlytics fielding logs exist

A data source badge appears on analytics screens indicating whether stats are from GameChanger only, Playlytics only, or combined from both sources.

## Importing Multiple Seasons

Each import is stored by season year. Importing a new CSV overwrites the previous import for the same season — it does not create duplicate records.

To import data from a previous season change the season year before importing, or contact support for guidance on multi-season imports.

## Already Logging in Playlytics?

If you score games in Playlytics AND import from GameChanger the stats are combined without double-counting:

- GameChanger provides season totals
- Playlytics provides pitch-level and at-bat-level detail
- The All and Game filters show the combined picture
- The Imported filter shows only GameChanger totals
- Practice and Individual filters show only Playlytics data

This hybrid approach gives you the most complete statistical picture — GameChanger's breadth combined with Playlytics' depth.

## What GameChanger Import Does Not Include

GameChanger season totals do not include pitch-by-pitch or at-bat-by-at-bat detail. As a result these Playlytics features require game logging:

- Pitch heat maps and location charts
- Spray charts and contact location data
- At-bat sequencing and count analysis
- Real-time pitch count tracking
- Inherited runner ERA adjustments

These features become available as you log games in Playlytics going forward.

## Tips

- **Import before your first Playlytics game** to establish a full season baseline
- **Re-import periodically** as your GameChanger season progresses to keep totals current
- **Use the Imported filter** to verify the import completed correctly before relying on combined stats
- **Guest players** — decide before importing whether guest players should be added to your roster or kept as stats-only entries
- **Roster matching** — review partial matches carefully, especially for players with common last names
