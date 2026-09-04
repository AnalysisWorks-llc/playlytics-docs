# Hitting Analytics

## Spray Chart

The spray chart shows where batted balls were hit across the field. Each dot represents a batted ball colored by result:
- **Green** — hits
- **Red** — outs
- **Yellow** — errors and fielder's choices

Use the spray chart to identify:
- Pull tendencies vs opposite field hitting
- Gap power vs straight-away hitting
- Infield hit tendencies

## Batting Average Trend

The trend chart shows batting average over time. Use the date range filter to evaluate recent performance vs season-long trends.

## Contact Type Distribution

The donut chart shows the breakdown of ground balls, line drives, and fly balls. Line drive percentage is the strongest predictor of hitting success — higher line drive rates generally correlate with better outcomes.

## Hard Hit Rate

Hard hit rate tracks the percentage of at-bats where the ball was hit with authority. This is a quality-of-contact metric independent of results.

## Season Totals

The season totals card shows cumulative stats for the selected date range and event filter.

| Stat | Description |
|------|-------------|
| AB | At-bats |
| H | Total hits (singles + doubles + triples + home runs) |
| 2B | Doubles |
| 3B | Triples |
| HR | Home runs |
| RBI | Runs batted in |
| BB | Walks |
| K | Strikeouts |
| HBP | Hit by pitch |
| SAC | Sacrifice bunts and flies |
| SB | Stolen bases |
| CS | Caught stealing |

::: tip Reading the hit breakdown
**H** is total hits — the standard baseball convention. **2B**, **3B**, and **HR** break out the extra-base portion. Singles can be derived as H − 2B − 3B − HR.
:::

## Rate Stats

| Stat | Description |
|------|-------------|
| BA | Batting Average — H ÷ AB |
| OBP | On-Base Percentage — (H + BB + HBP) ÷ (AB + BB + HBP) |
| SLG | Slugging Percentage — total bases ÷ AB. Total bases = 1×1B + 2×2B + 3×3B + 4×HR |
| OPS | On-Base Plus Slugging — OBP + SLG |

## Quality At-Bat Percentage (QAB%)

QAB% measures how often a batter has a productive plate appearance regardless of result. An at-bat qualifies as a QAB when any of the following occur:

- Hit
- Walk or HBP
- Hard hit ball
- Long at-bat (6+ pitches)
- Sacrifice
- RBI
- Reached on error

A QAB% above the age-group threshold (shown on the analytics screen) indicates a consistently productive hitter.
