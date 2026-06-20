# TandemPVP

Real-time Pokemon GO PVP battle overlay that detects opponent pokemon and displays competitive movesets.

## Features

### Live Overlay
- Floating overlay that displays during Pokemon GO battles
- Auto-detects opponent's Pokemon from screen using OCR
- Shows recommended charged moves with energy requirements

### Opponent Analysis
- Displays all possible competitive movesets for detected Pokemon
- Shows energy cost for each charged move (how many fast moves needed)
- Toggle between different move options with quick buttons
- Supports multiple Pokemon forms (Alolan, Galarian, etc.)

### Team History
- Records all battles with timestamp and result (win/loss)
- Calendar view to browse matches by date
- Edit match notes for future reference
- Overall statistics and win/loss tracking

### Match Analysis
- Search Pokemon to see your record against them
- View lead Pokemon frequency and win rates
- Common Pokemon pairings in your team
- Per-Pokemon matchup statistics

## How to Use

### Initial Setup
1. Open the app and tap "Grant overlay permission"
   - This allows the overlay to display during other apps
2. Tap "Start overlay" to begin scanning

### During Battle
- The overlay appears in the top-right corner
- Shows opponent's Pokemon name and recommended moves
- **↻ Switch fast** - Cycle through fast move options
- **↻ Change form** - Switch between different Pokemon forms
- **Reset** - Clear the detection if Pokemon is mis-scanned
- **W** - Mark battle as win
- **L** - Mark battle as loss

### Analysis
- Search for any Pokemon to see your record
- View top leads and most-seen opponents
- Check common team pairings

## Display Modes

Choose how charged moves are displayed:
- **Counts** - Number of fast moves needed per charged move option
- **Turns** - Time in seconds (each turn is 500ms)

