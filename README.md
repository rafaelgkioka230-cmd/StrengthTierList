# Strength -Tier- List

A sleek tier list application for ranking players and characters with a dark theme featuring red accents.

## Features

- **Tier Ranking System**: Organize players into S, A, B, C, and D tiers
- **Owner-Only Controls**: 
  - Only the owner can remove individual players using the remove button (×)
  - Only the owner can clear all players at once
  - Password-protected owner mode
- **Black & Red Theme**: Dark background with vibrant red accents
- **Persistent Storage**: All players are saved to your browser's local storage
- **Responsive Design**: Works great on desktop and mobile devices

## How to Use

1. **Enable Owner Mode** (if you're the owner):
   - Click the "Owner Mode: OFF" button
   - Enter the owner password: `owner`
   - The button will change to "Owner Mode: ON"

2. **Add Players**:
   - Enter a player name in the input field
   - Select which tier they belong to (S, A, B, C, or D)
   - Click "Add Player" or press Enter

3. **Remove Players** (Owner Only):
   - Enable owner mode first
   - Click the red "×" button on any player card
   - Or use "Clear All Players" to remove everyone at once

## Owner Password

Default password: `owner`

⚠️ **Note**: Change this password in the code (`script.js`) for better security in production use.

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling with black background and red accents
- `script.js` - Application logic and owner controls
- `README.md` - This file

## Local Storage

Your tier list is automatically saved to your browser's local storage. The data persists even after closing the browser.

## Customization

You can customize:
- Owner password in `script.js`
- Colors in `styles.css`
- Tier names by editing the tier labels in `index.html`

Enjoy your Strength -Tier- List!
