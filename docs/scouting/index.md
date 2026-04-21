# Opponent Scouting Reports

## Overview

Playlytics includes two tiers of opponent scouting — a free research tool available to all users and a full AI-powered report available on paid plans.

## Accessing Scouting Reports

Navigate to **Schedule** and tap the **🔭 Scout** button on any game card. You can also tap the **📋 Report saved** badge on a game card to open a previously generated report instantly.

## Tier 1 — Free Research Prompt (All Users)

The free tier generates a polished research prompt and shares it to any AI app on your device — Gemini, Copilot, ChatGPT, or any other.

### How it works

1. Tap **Scout** on a scheduled game card
2. The opponent name and your team info are pre-filled
3. Add any context you know about the opponent — tap the microphone on your keyboard (mobile) or the mic button (desktop) to speak naturally:
   *"They play USSSA in Plant City, strong pitching staff, faced them last spring"*
4. Select the tournament stage and pitcher availability
5. Tap **Generate and Share** — your device's share sheet opens
6. Select Gemini, Copilot, or ChatGPT
7. The research prompt is pre-filled — tap send
8. The AI searches USSSA, Perfect Game, GSA, AAU, and other tournament databases and returns a comprehensive scouting report

### What the prompt searches

**Baseball:** USSSA, Perfect Game, GSA/Global Sports Alliance, AAU Baseball, Triple Crown Sports, Prep Baseball Report

**Softball:** USSSA Softball, Perfect Game Softball, PGF/Premier Girls Fastpitch, TCS Fastpitch, NSA, Alliance Fastpitch, AFA

### Tournament stage and pitcher availability

These optional selectors add important context to the prompt:

**Tournament stage:** Pool Play, Bracket Play, Semi-Final, Championship, Regular Season — affects strategic recommendations significantly. A championship game requires a different approach than a pool play opener.

**Pitching availability:** Full roster available, Ace unavailable, Limited arms, Must conserve for later — tells the AI how to frame pitching rotation recommendations.

## Tier 2 — Full In-App Report (Coach, Organization, Enterprise)

The full report combines your pasted external AI research with your internal game analytics for a data-driven scouting report saved directly in Playlytics.

### How it works

1. Run the Tier 1 prompt in Gemini or Copilot
2. Copy the full response from Gemini or Copilot
3. Return to Playlytics — tap Scout on the game card
4. Scroll to **Full Scouting Report**
5. Paste the Gemini/Copilot response into the research field (optional but recommended)
6. Tap **Generate Full Scouting Report**
7. Wait 60-90 seconds — the report analyzes all available data
8. The complete report appears and is saved automatically

### What the full report includes

The report automatically pulls from your Firestore data:
- Your win/loss record against this opponent
- Your pitching logs from previous games — strike rate, pitch type breakdown, location tendencies
- Your hitting logs — batting average, contact type distribution, strikeout rate
- Coach notes mentioning this opponent

Combined with pasted external research this produces a personalized analysis specific to your team's matchup history.

### Report sections

1. **Matchup Overview** — competitive assessment and key factors
2. **Opponent Profile** — tournament record and known tendencies
3. **Data Insights** — analysis from your logged game data
4. **Pitching Strategy** — pitch mix, sequencing, pitcher change triggers
5. **Offensive Game Plan** — lineup recommendations and at-plate approach
6. **Inning-by-Inning Focus** — early, middle, and late game strategy
7. **Pregame Huddle** — 5 talking points for the team

### Skipping external research

External research is optional. If you tap Generate without pasting anything the report still works — it uses your internal game data and general strategic analysis. Reports based on logged game history against the opponent are most valuable for recurring opponents.

### Saving and retrieving reports

Every report is saved automatically to your game record. To retrieve a saved report:

- Tap the **📋 Report saved** badge on the Schedule game card
- Or tap Scout → scroll to Previous Scouting Reports → tap View

Viewing a saved report costs no additional usage — only generating a new report counts against your monthly limit.

### Monthly limits

| Plan | Reports per Month |
|------|------------------|
| Free | 0 (Tier 1 only) |
| Player | 0 (Tier 1 only) |
| Coach | 15 |
| Organization | 60 |
| Enterprise | 100 |

Limits reset on the 1st of each month.

### Tips for best results

- **Run Tier 1 first** even if you plan to use Tier 2 — the external AI research significantly enhances the full report quality
- **Be specific with context** — mentioning the tournament circuit, location, and any players you know about improves recommendations
- **Generate before the tournament** — not during warm-ups. The report takes 60-90 seconds
- **Recurring opponents** — the more games you have logged against a team the more data-driven and specific the report becomes
- **Review before sharing** — reports are saved and can be shared with assistant coaches via the Share button on the report view
