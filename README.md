# ATP Analytics / Comparison Dashboard

A lightweight, single-file interactive dashboard for comparing ATP tennis players across head-to-head records, titles, surface performance, and conditional win rates, covering **65,974 matches from 2000 to 2025**.

## Features

**Head-to-Head (H2H)**
Compare any two players across their full match history. Filter by tournament level (Grand Slams, Masters 1000, ATP 500, ATP 250, ATP Finals) or surface (Hard, Clay, Grass, Carpet). Click any match to reveal trivia and historical context.

**Titles**
Side-by-side breakdown of career title counts by tournament level for any two selected players.

**Surface**
Career win percentages by surface alongside head-to-head breakdowns per surface and per tournament tier.

**Conditional Stats**
Deep conditional win rates by round, surface, pressure scenarios, and more for any player pair.

## Tech Stack

- Pure HTML / CSS / JavaScript with zero dependencies and no build step
- All match data embedded as a single JSON object within the file
- Fully responsive design (works on mobile)

## Usage

No installation required. Open `index.html` in any modern browser:

```bash
git clone https://github.com/SMFawaz24/atp-analytics.git
cd atp-analytics
open index.html
```

## Data Coverage

| Attribute | Detail |
|---|---|
| Time range | 2000 to 2025 |
| Total matches | 65,974 |
| Players included | 50 ATP professionals |
| Tournament levels | Grand Slams, ATP Finals, Masters 1000, ATP 500, ATP 250 |
| Surfaces | Hard, Clay, Grass, Carpet |

Each match record includes date, tournament name, level, surface, round, score, sets played, and contextual trivia.

## Project Structure

```
atp-analytics/
├── index.html   # Entire app: UI, styles, data, and logic
└── LICENSE      # MIT
```

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Syed Mohammad Fawaz** - [@SMFawaz24](https://github.com/SMFawaz24)
