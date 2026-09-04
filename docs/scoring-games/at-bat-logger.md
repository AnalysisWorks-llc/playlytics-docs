# At-Bat Logger

The At-Bat Logger records hitting results for each batter. Data from the At-Bat Logger drives batting average, on-base percentage, slugging, and all hitting analytics.

## Batter Selection

When a **lineup is confirmed** the logger automatically shows the current batter based on the batting order. The order advances automatically after each recorded at-bat. Tap **Override** if you need to log a different batter (for example a pinch hitter not yet in the order).

Without a confirmed lineup select the batter manually from the player selector at the top of the screen.

## Logging an At-Bat

1. Select the **contact type** — how the ball was hit (Ground Ball, Line Drive, Fly Ball)
2. Select the **result** — the at-bat outcome
3. Tap the **spray chart** to indicate where the ball was hit
4. Optionally toggle **Hard Hit** or **Long AB**
5. Set the **RBI** count if runs scored on the play
6. The record saves automatically when both contact type and result are selected

Quick-save results (K, BB, HBP) save immediately without requiring a contact type.

## Contact Types

| Type | Description |
|------|-------------|
| GB | Ground ball — ball hit on the ground |
| LD | Line drive — ball hit on a line, low trajectory |
| FB | Fly ball — ball hit in the air, high trajectory |

## Results

| Result | Description |
|--------|-------------|
| 1B | Single |
| 2B | Double |
| 3B | Triple |
| HR | Home run — all runners score automatically, bases clear |
| OUT | Any out — groundout, flyout, lineout |
| K / K | Strikeout swinging / looking — saves immediately |
| BB | Walk — saves immediately |
| HBP | Hit by pitch — saves immediately |
| ERR | Reached on error |
| FC | Fielder's choice |
| SAC | Sacrifice bunt or fly |

## Base State — Automatic Updates

After each at-bat the app automatically updates the shared base state visible in the Baserunning Logger:

- **1B, 2B, 3B hits** — batter is placed on the appropriate base. If that base is occupied a prompt appears asking where the displaced runner went (advance, score, or out).
- **HR** — all runners on base score automatically and the bases clear. No action needed in the Baserunning Logger.
- **Walk / HBP / Error / FC** — batter is placed on first base. Occupied-base conflicts prompt for resolution.
- **Outs / K** — no base change.

The score counter updates automatically when runners score via the displacement prompt or on a home run.

## Spray Chart

Tap the zone on the field diagram where the ball was hit. This drives spray chart heat maps in hitting analytics.

Zones include all outfield areas (Shallow LF, Deep LF, Left Center Gap, Center Field, Right Center Gap, Shallow RF, Deep RF) and infield positions (3B, SS, 2B, 1B, Pitcher/Catcher area).

## Hard Hit and Long AB Toggles

**Hard Hit** — ball hit with significant force. Hard hit rate is tracked separately in analytics.

**Long AB** — at-bat extended to 6 or more pitches. Long AB rate is a component of Quality At-Bat percentage.

## RBI

Tap the RBI selector (0–4) before the result saves. RBI count is stored on the log and appears in season totals.

## Quick Navigation

The **→ Baserunning** button in the top right navigates directly to the Baserunning Logger — useful after a hit to manage runners already on base before the next batter.
