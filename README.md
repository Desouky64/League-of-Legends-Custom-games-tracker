# League of Legends Custom Game Tracker

> A comprehensive analytics tool for League of Legends custom games, offering detailed match history, player statistics, and performance tracking using the Riot Games API.

## Overview
The League of Legends Custom Game Tracker is a dedicated utility designed to capture, store, and analyze data specifically from custom matches—data that is often overlooked by mainstream tracking sites. Whether organizing local tournaments, tracking internal scrims, or analyzing team performance over time, this tool provides a centralized dashboard to log match details, calculate win rates, and break down individual player metrics. 

## Key Features
* **Automated Match Fetching:** Integrates with the Riot Games API to pull post-game data directly into the database.
* **Custom Leaderboards:** Ranks players based on custom parameters such as KDA, vision score, objective damage, and custom match win rate.
* **Historical Match Archive:** Stores a persistent history of in-house games to track long-term team and individual improvement.
* **Draft Analysis:** Records pick/ban phases to help teams identify champion synergies and draft trends.
* **Role-Specific Metrics:** Filters performance data by Top, Jungle, Mid, ADC, and Support roles.

## Tech Stack

| Component | Technology / Framework | Purpose |
| :--- | :--- | :--- |
| **Backend** | Python / Node.js *(Update as needed)* | Handles server logic and API requests |
| **Frontend** | React / Vue.js *(Update as needed)* | Delivers a responsive, interactive user interface |
| **Database** | PostgreSQL / MongoDB *(Update as needed)* | Stores player profiles, match histories, and team data |
| **External API**| Riot Games API | Fetches raw match data, champion assets, and player info |

## Getting Started

### Prerequisites
* A valid [Riot Games Developer API Key](https://developer.riotgames.com/).
* Node.js and npm (or Python environment) installed locally.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lol-custom-tracker.git
   ```
2. Navigate to the project directory and install dependencies:
   ```bash
   cd lol-custom-tracker
   npm install 
   ```
3. Create a `.env` file in the root directory and add your Riot API key and database credentials:
   ```env
   RIOT_API_KEY=your_development_api_key
   DB_CONNECTION_STRING=your_database_url
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Future Roadmap
- [ ] Implement automated Discord webhook notifications for post-match summaries.
- [ ] Add advanced data visualization charts for gold and experience leads over time.
- [ ] Build a tournament bracket generation feature for in-house events.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/lol-custom-tracker/issues).

## License
This project is licensed under the MIT License - see the LICENSE file for details.
