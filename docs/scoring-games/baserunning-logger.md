# Baserunning Logger

The Baserunning Logger tracks all baserunning events — stolen bases, scores, outs on the bases, and pickoffs. It uses a **live diamond view** that shows which players are currently on each base, updated in real time as at-bats are logged.

## The Diamond View

The center of the screen shows a baseball diamond with three base cards — 1B, 2B, and 3B. Each card shows the name of the runner currently on that base, or **empty** if unoccupied. Tap a base card to open the action panel for that runner.

Base state is shared across all loggers. When the At-Bat Logger records a hit, walk, or error, the batter automatically appears on the correct base without any manual entry in the Baserunning Logger.

## Logging a Baserunning Event

1. Tap the **base card** for the runner you want to log
2. The **action panel** opens below the diamond
3. Select the action — Advance, Score, Out, Steal Attempt, or Picked Off
4. The base state updates immediately

## Actions for an Occupied Base

| Action | Description |
|--------|-------------|
| Advance → | Moves runner to the next base. Blocked if the next base is already occupied — advance that runner first. |
| Score | Runner scores a run. Removes runner from base, increments your team's score. |
| Out | Runner is out on the base paths. Removes runner from base, increments out count. |
| Steal Attempt | Opens SB / CS buttons. SB moves runner to next base; CS removes runner and increments out count. |
| Picked Off | Runner is picked off. Removes runner, increments out count. |

## Logging an Empty Base

Tap an empty base card, then tap **+ Place a runner** to select a player from your roster. Only players not currently on another base appear in the list. Use this to manually correct base state if needed.

## Sprint Time and Distance

After opening an action panel, a **time input** and **distance selector** appear at the bottom. Record sprint time (in seconds) and the distance run (1B→2B, 2B→3B, 3B→H, 1B→3B, 2B→H). These feed into baserunning speed analytics.

## Blocked Advances

If you attempt to advance a runner to an occupied base, a warning appears: **"[Base] is occupied — advance that runner first."** Resolve the lead runner before advancing the trailing runner. This prevents two runners being assigned to the same base.

## Clear Bases

The **Clear Bases** button at the bottom of the screen removes all runners from all bases — use this at the end of an inning or to correct a data entry error.

## Session Counters

The bar at the top shows running totals for the current scoring session:

| Counter | Description |
|---------|-------------|
| SCORED | Runs scored since the session started |
| SB | Stolen bases recorded |
| CS | Caught stealing recorded |

## Quick Navigation

The **→ At-Bat** button in the top right navigates directly to the At-Bat Logger.
