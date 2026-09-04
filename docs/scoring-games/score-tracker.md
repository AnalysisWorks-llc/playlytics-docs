# Score and Inning Tracker

The score and inning tracker appears on the Game Hub and keeps a running record of the game situation.

## Automatic Score Updates

The score updates automatically in two situations:

- **Home run** — all runners on base plus the batter score. The score increments immediately when HR is logged in the At-Bat Logger.
- **Runner scores** — when the Baserunning Logger records a runner scoring (via Score action or Caught Stealing → scored), your team's score increments automatically.

You can also tap the score directly to edit it manually at any time.

## Inning Tracker

The inning tracker shows:
- **Inning number** — tap + or - to adjust
- **Top or Bottom** — tap to toggle between top and bottom of the inning
- **Out indicators** — three circles representing outs. Tap to fill each circle as outs are recorded.

Outs are also incremented automatically when:
- The Fielding Logger records an out (via the OUT button)
- The Baserunning Logger records a caught stealing, out on the bases, or pickoff
- The Pitching Logger records a strikeout (K button) or pickoff

When the **third out** is recorded:
- If in the top of the inning: automatically switches to the bottom of the inning, resets outs to zero
- If in the bottom of the inning: automatically advances to the next inning, switches to top, resets outs to zero

## Saving the Game Result

When the game ends tap **End Game** in the Game Hub. You will be prompted to confirm the final score and result (W/L/T). This saves the result to your schedule and updates your season record on the dashboard.
