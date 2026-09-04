# Fielding Logger

The Fielding Logger records defensive plays — who fielded the ball, how, and the result. This data drives fielding percentage, zone tendency charts, and throwing accuracy analytics.

## How Fielder Selection Works

When a **lineup is confirmed** with defensive assignments, tapping a position on the field diagram **automatically selects** the player assigned to that position. No manual player selection is needed — simply tap the position, then log the play.

Without a confirmed lineup, select the fielder manually from the player selector at the top, then tap a position to confirm.

## Logging a Fielding Play

1. Tap the **position** on the field diagram — the assigned fielder is highlighted automatically
2. Select the **ball type** — how the ball arrived
3. Select the **fielding zone** — where relative to the player the ball was hit
4. Select **Catch** or **Error** for the fielding result
5. If a throw was made select the **throw zone** and **throw result**
6. Toggle **Double Play** if applicable
7. Tap **OUT** at the bottom to record the out and save the play

## Ball Types

| Type | Description |
|------|-------------|
| Ground Ball | Ball hit on the ground |
| Line Drive | Ball hit on a line |
| Fly Ball | Ball hit in the air |

## Fielding Zones

The fielding zone grid shows 9 positions relative to the fielder:

```
Behind Left | Behind | Behind Right
Left        | Player | Right
Front Left  | Front  | Front Right
```

Select where the ball was relative to the fielder when they fielded it.

## Throw Zones

The throw zone grid shows 9 directional zones for the throw:

```
High Left | High  | High Right
Left      | Player| Right
Low Left  | Low   | Low Right
```

Select the direction and height of the throw.

## OUT Button

The **OUT** button appears at the bottom of the form after a position is selected. Tap it after recording the field and throw details. This saves the play and increments the out count. If Double Play is toggled the button shows **DOUBLE PLAY ✓✓** and two outs are recorded.

Completing the field and throw entries first ensures complete data before saving.

## Special Plays

**Double Play (DP)** — toggle before tapping OUT to mark the play as a double play. Two outs are recorded.

**Passed Ball (PB)** — for catchers only. Appears in the field action options for the C position. Records a passed ball and counts as an error in the catcher's fielding percentage.

## Automatic Navigation

When a pitch is logged as **Hit in Play** in the Pitching Logger the app automatically navigates to the Fielding Logger. After logging the fielding play return to the Game Hub manually — multiple fielding plays can result from one ball in play.
