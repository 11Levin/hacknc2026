# Welcome to your Lovable project

This project was built with [Lovable](https://lovable.dev).


# College Fantasy Football

A college fantasy football website built for a hackathon, featuring teams from the Power 4 conferences and Notre Dame (68 teams). The goal is to bring the fantasy football experience to college football through drafting, roster management, trading, and weekly scoring.

## Features

- **Drafting:** Build a fantasy roster of college football players.
- **Bot Opponents:** Compete against AI-controlled fantasy teams.
- **Trading:** Trade players with other teams.
- **PPR Scoring:** Calculate weekly fantasy points using standard points-per-reception (PPR) scoring.
- **League Management:** Track team records, standings, rosters, and weekly scores.
- **Season Simulation:** Simulate the 2025 season to demonstrate the website's features.

## Data

The website will track:
- College teams and players
- Weekly schedules and opponents
- Player statistics, including yards, touchdowns, and receptions
- User accounts and fantasy rosters
- Leagues, records, and standings
- Weekly fantasy points

## Tech Stack

- **Database:** TigerData
- **AI:** Gemini for bot opponent logic
- **Frontend:** A modern, visually engaging interface with potential Frutiger Aero-inspired design

## League Rules

- **Teams:** Power 4 conferences + Notre Dame (68 teams)
- **Scoring:** Standard PPR (Point Per Reception)
- **Roster Positions:** QB, WR, RB, TE, K, D/ST
- **Season:** Week 0 excluded

## Development Roadmap

- [ ] Build the core website and database
- [ ] Implement fantasy drafting and roster management
- [ ] Add AI-controlled opponents
- [ ] Implement player trading
- [ ] Calculate weekly fantasy points
- [ ] Simulate the 2025 season for a demo
- [ ] Update player statistics and scores weekly, targeting Mondays

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

## Built with

- TanStack Start
- TypeScript
- React
- Tailwind CSS
