# League of Legends Custom Game Tracker

> A comprehensive analytics tool for League of Legends custom games, utilizing AI-powered screenshot analysis to extract, store, and track detailed match history and player statistics.

## Overview

The League of Legends Custom Game Tracker is a dedicated utility designed to capture, store, and analyze data specifically from custom matches—data that is often overlooked by mainstream tracking sites. Instead of relying on traditional game APIs, this tool uses advanced AI vision to read post-match screenshots. Whether organizing local tournaments, tracking internal scrims, or analyzing team performance over time, this tool provides a centralized dashboard to log match details, calculate win rates, and break down individual player metrics.

## Key Features

* **AI-Powered Data Extraction:** Simply upload a post-match screenshot. The integrated AI API automatically captures player stats, KDA, champion info, and match results, feeding the data directly into your online database.

* **Custom Leaderboards:** Ranks players based on custom parameters such as KDA, vision score, objective damage, and custom match win rate.

* **Historical Match Archive:** Stores a persistent history of in-house games to track long-term team and individual improvement.

* **Frictionless Entry:** No need for players to link accounts or authenticate with Riot; if you have the screenshot, you have the data.

* **Role-Specific Metrics:** Filters performance data by Top, Jungle, Mid, ADC, and Support roles.

## Tech Stack

| Component | Technology / Framework | Purpose | 
 | ----- | ----- | ----- | 
| **Backend** | Python / Node.js *(Update as needed)* | Handles server logic, image processing, and API requests | 
| **Frontend** | React / Vue.js *(Update as needed)* | Delivers a responsive, interactive user interface for uploading images | 
| **Database** | PostgreSQL / MongoDB / Firebase *(Update as needed)* | Stores player profiles, match histories, and team data | 
| **External API** | AI Vision API *(e.g., OpenAI GPT-4V, Google Cloud Vision)* | Processes screenshots to extract raw post-match text and data | 

## Getting Started

### Prerequisites

* A valid API Key for your chosen AI Vision service (e.g., OpenAI).

* Node.js and npm (or Python environment) installed locally.

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/lol-custom-tracker.git
   
   ```

2. Navigate to the project directory and install dependencies:

   ```
   cd lol-custom-tracker
   npm install 
   
   ```

3. Create a `.env` file in the root directory and add your AI API key and database credentials:

   ```
   AI_VISION_API_KEY=your_ai_api_key_here
   DB_CONNECTION_STRING=your_database_url
   
   ```

4. Start the development server:

   ```
   npm run dev
   
   ```

## Future Roadmap

* \[ \] Implement bulk screenshot uploading for processing multiple games at once.

* \[ \] Add automated Discord webhook notifications for post-match summaries.

* \[ \] Build a tournament bracket generation feature for in-house events.

## Contributing

Feel free to try it on :https://desouky64.github.io/League-of-Legends-Custom-games-tracker/


## License

This project is licensed under the MIT License - see the LICENSE file for details.
