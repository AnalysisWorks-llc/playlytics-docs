# Scoring Games

Playlytics captures game data through four specialized loggers — Pitching, At-Bat, Fielding, and Baserunning. Each logger is optimized for rapid data entry during live play.

## Starting a Game Session

1. From the dashboard tap **Log Game Data**
2. Select **Game** as the session type
3. Select your opponent — choose from saved opponents or add a new one
4. If you have a game scheduled for today it will appear as a pre-filled option
5. Tap **Start Game**

You are now in the **Game Hub** — the central screen for all game logging.

## Lineup Setup

Before the first pitch you can optionally set a **confirmed lineup**. This unlocks two automatic features:

- **At-Bat Logger** — automatically tracks the batting order and advances to the next batter after each at-bat
- **Fielding Logger** — automatically selects the assigned fielder when you tap a position on the field diagram

To set the lineup tap **Set Lineup** in the Game Hub. Assign players to batting order slots and defensive positions, then confirm. Substitutions can be recorded during the game through the substitution flow.

## Game Hub

The Game Hub is your home base during a game. From here you access:

- **Pitching Logger** — log every pitch
- **At-Bat Logger** — log hitting results
- **Fielding Logger** — log defensive plays
- **Baserunning Logger** — track runners on base and log baserunning events
- **Voice Logger** — describe plays verbally for AI-powered logging
- **Score and Inning Tracker** — track the current score and inning

## Shared Base State

All loggers share a **live base state** that shows which players are currently on each base. This state updates automatically:

- Hits, walks, and errors in the At-Bat Logger place the batter on the appropriate base
- Home runs in the At-Bat Logger clear all bases and score all runners automatically
- The Baserunning Logger shows the current diamond and lets you advance, score, or record outs for each runner

The score and out count also update automatically from actions taken in any logger.

## Navigation Between Loggers

Each logger has a **back arrow** in the top left to return to the Game Hub.

For related loggers you can navigate directly:
- **Pitching → Fielding** — when a pitch results in a ball in play the app automatically navigates to the Fielding Logger
- **At-Bat ↔ Baserunning** — a direct navigation button in the top right of each logger allows quick switching

## Who Logs Data

Any team member with Scorekeeper role or higher can log game data. For the best results:

- **Head Coach or Assistant Coach** — manages substitutions, pitcher changes, and reviews data
- **Scorekeeper or parent volunteer** — focuses on real-time data entry
- **Voice logging** — reduces the skill required for parent volunteers significantly
