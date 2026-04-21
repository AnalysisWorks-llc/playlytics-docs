# Lineup Builders

## Overview

Playlytics includes two lineup builders — Defensive Lineup and Batting Order — both using your logged player analytics to make data-driven suggestions.

## Accessing Lineup Builders

Navigate to **More** in the bottom navigation → **Lineups** → select Defensive Lineup or Batting Order.

## Defensive Lineup Builder

The defensive lineup builder suggests optimal fielding alignments based on each player's fielding percentage at each position and ERA for pitchers.

### How it works

1. Navigate to Lineups → Defensive Lineup
2. Tap **Auto-Suggest** to fill all positions automatically
3. The algorithm fills positions using this priority order:
   - Pitcher — selected by lowest ERA (not fielding percentage)
   - Catcher — highest FLD% at C
   - Shortstop — highest FLD% at SS
   - Second Base, Third Base, First Base
   - Center Field, Left Field, Right Field
4. Override any position by tapping the player name → select a different player
5. Tap **Clear All** to reset and start fresh

### Reading the position cards

Each assigned position card shows:
- **Player name and jersey number** — tap to change the assignment
- **Fielding %** — color coded green (≥90%), amber (75-89%), red (<75%)
- **Throwing %** — same color coding
- **📊 chart** — tap to view full polar accuracy charts for this player at this position

For the **pitcher position** the card shows ERA and strikeout rate instead of fielding stats — tap the chart icon to view the pitching heat map.

### Pitcher selection

The pitcher slot is filled based on ERA not fielding percentage. The player with the lowest ERA among available pitchers is suggested. Age-appropriate ERA thresholds apply based on your team level.

### Mobile layout

On mobile the field diagram adjusts spacing automatically to prevent position card overlap. The spatial relationship of the positions is maintained — outfield at top, infield in middle, battery at bottom.

### Availability tracking

Mark players as unavailable before building the lineup. Tap a player → Mark Unavailable → select a reason (injury, absence, rest, pitch count limit). Unavailable players are excluded from auto-suggestions.

## Batting Order Builder

The batting order builder suggests batting order based on OBP, power, and speed metrics.

### How it works

1. Navigate to Lineups → Batting Order
2. The algorithm places players based on:
   - **Leadoff** — highest OBP player
   - **2-3 spots** — high contact, good OBP
   - **Cleanup and 5** — highest power metrics
   - **6-9** — balanced contact and speed
3. Drag and drop players to reorder
4. Each player card shows a sparkline of recent at-bat results

### Sparklines

The mini trend chart on each player card shows recent performance at a glance — a quick visual of current form before you commit to a batting order.

### Saving lineups

Tap **Save Lineup** to store the configuration. Saved lineups appear in your lineup history and can be recalled for future games.

### Game Day card

The Game Day view combines the defensive alignment and batting order on one screen that can be shared with assistant coaches via the Share button.

## Tips for Best Results

- **Log more data** — lineup suggestions improve significantly with more game data. After 20+ at-bats batting order recommendations become statistically meaningful
- **Use availability tracking** — mark injured or resting players before auto-suggest to get realistic lineup recommendations
- **Override freely** — the suggestions are a starting point. Your coaching knowledge of matchups and situational factors should always have the final say
- **Check the polar charts** — tap 📊 on any position card to see detailed fielding zone accuracy before making defensive assignments
