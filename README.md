# System 36 Golf Scorer

A mobile and desktop web application for calculating System 36 golf handicaps for casual tournaments.

![System 36 Golf Scorer](screenshot.png)

## Features

### Core Functionality
- **System 36 Handicap Calculation** - Automatic calculation based on hole performance
  - Par or better: 2 points
  - Bogey: 1 point
  - Double bogey or worse: 0 points
  - Handicap = 36 - Total Points
  - Net Score = Gross Score - Handicap

### Player Management
- Add unlimited players
- Remove players
- Switch between players for score entry
- Track multiple rounds simultaneously

### Course Setup
- **Quick Presets:**
  - Lombok Kosaido Golf & Country Club (Par 72)
  - Standard Par 72 Course
- **Custom Courses:**
  - Upload scorecard images as reference
  - Set par values for all 18 holes
  - Choose tee colors (Championship, Men's, Ladies, Senior, Custom)
  - Save courses for future use
  - Delete saved courses

### Scoring
- Hole-by-hole score entry
- Visual scorecard table
- Real-time statistics:
  - System 36 Points
  - Handicap
  - Gross Score
  - Net Score
  - Score to Par

### Results & Leaderboard
- Automatic ranking by net score
- Trophy icon for winner
- Complete statistics table:
  - Rank
  - Player name
  - Gross score
  - Score to par
  - System 36 points
  - Handicap
  - Net score

### Save & Load
- Save complete or partial rounds
- Name your rounds (e.g., "Lombok Kosaido - Nov 18")
- View all saved rounds with timestamps
- Load any saved round to continue later
- Delete old rounds
- Data persists in browser localStorage

### Print
- Print-optimized layout
- Includes full scorecard and results
- Clean output for tournament records

## How to Use

### 1. Course Setup
1. Choose a preset course or upload a scorecard image
2. Adjust hole pars if needed
3. Set the tee colors you're playing from

### 2. Add Players
1. Enter player names
2. Click "Add Player"
3. Repeat for all players in your group

### 3. Enter Scores
1. Click on a player card to select them
2. Enter their score for each hole (1-18)
3. Watch real-time System 36 calculations
4. Switch players and repeat

### 4. View Results
- Results automatically appear as scores are entered
- See complete leaderboard with handicaps
- Winner highlighted with trophy

### 5. Save Your Round
1. Enter a round name
2. Click "Save Current Round"
3. Access it anytime from "Saved Rounds"

### 6. Print Results
- Click "Print Results" for a clean printout
- Perfect for posting tournament results

## Installation

### Option 1: Open Directly
Simply open `index.html` in any modern web browser (Chrome, Safari, Firefox, Edge)

### Option 2: Host on Web Server
Upload `index.html` to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Your own web server

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/drgreenland/System36.git
cd System36

# Open in browser
open index.html
# or on Linux
xdg-open index.html
# or on Windows
start index.html
```

## Technical Details

- **Framework:** Pure HTML5, CSS3, and vanilla JavaScript (no dependencies)
- **Storage:** Browser localStorage for data persistence
- **Responsive:** Works on mobile phones, tablets, and desktops
- **Offline:** Fully functional without internet connection
- **Browser Support:** All modern browsers (Chrome, Safari, Firefox, Edge)

## File Structure

```
System36/
├── index.html          # Main application (single file)
├── README.md          # This file
└── screenshot.png     # App screenshot (optional)
```

## System 36 Scoring Rules

System 36 is a temporary handicapping method for golfers without official handicaps:

**Points Per Hole:**
- **Par or better** (Birdie, Eagle): 2 points
- **Bogey** (+1): 1 point
- **Double bogey or worse** (+2 or more): 0 points

**Handicap Calculation:**
- Add up all points from 18 holes
- Handicap = 36 - Total Points
- Example: 23 points = 13 handicap

**Net Score:**
- Net Score = Gross Score - Handicap
- Winner is lowest net score

This system:
- Encourages continued effort throughout the round
- Provides fair competition between players of different skill levels
- Makes casual tournaments more engaging and equitable

## Designed For

- **Lombok Golf Courses:**
  - Lombok Kosaido Golf & Country Club (Sire Bay)
  - GEC Rinjani Golf & Resort
  - Kaleang Golf Course
- **Any 18-hole golf course worldwide**

## Development

Built with ❤️ for golfers in Lombok, Indonesia

### Technologies Used
- HTML5
- CSS3 (Gradient backgrounds, Flexbox, Grid)
- JavaScript ES6+
- localStorage API
- Print Media Queries

### Browser Storage
All data is stored locally in your browser using localStorage:
- Saved rounds: `golfRounds`
- Saved courses: `golfCourses`
- No server required
- Data persists until you clear browser data

## Privacy

- **No data collection:** All data stays on your device
- **No internet required:** Works completely offline
- **No tracking:** No analytics or third-party scripts
- **No accounts:** No registration or login needed

## Future Enhancements

Potential features for future versions:
- [ ] Export rounds to CSV/PDF
- [ ] Multi-round handicap tracking
- [ ] USGA handicap index calculation
- [ ] Course rating and slope integration
- [ ] Detailed statistics and trends
- [ ] Share results via email/SMS
- [ ] Photo upload for each hole
- [ ] GPS distance tracking
- [ ] Stroke play vs. match play modes

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## License

MIT License - Free to use and modify

## Support

For questions or support:
- Open an issue on GitHub
- Contact: [Your contact info]

## Changelog

### Version 1.0.0 (November 2024)
- Initial release
- Core System 36 calculation
- Player management
- Course presets
- Save/load functionality
- Print support
- Responsive design
- Lombok Kosaido preset

---

**Enjoy your golf games in Lombok! 🏌️‍♂️⛳**
