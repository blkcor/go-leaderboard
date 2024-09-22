# Real-Time Leaderboard
This project involves creating a backend system for a real-time leaderboard service. The service will allow users to compete in various games or activities, track their scores, and view their rankings on a leaderboard. The system will feature user authentication, score submission, real-time leaderboard updates, and score history tracking. Redis sorted sets will be used to manage and query the leaderboards efficiently.

## Features
- User Authentication: Secure registration and login using JWT tokens.
- Score Submission: Users can submit their scores for various games or activities.
- Real-Time Leaderboard: Instantaneous updates to leaderboards as new scores are submitted.
- Score History Tracking: Users can view their historical scores and progress over time.
- Efficient Leaderboard Management: Utilizes Redis sorted sets for fast and efficient leaderboard operations.
- Scalable Architecture: Designed to handle high traffic and large amounts of data seamlessly.

## Technologies
- Gin: Go web framework for building the backend API.
- GORM: ORM library for interacting with the Postgres database.
- Redis: In-memory data store for managing leaderboards and real-time updates.
- Postgres: Database for storing user information and score history.
- Websockets: Real-time communication between the server and clients.
- JWT: Secure authentication and authorization for users.
- Docker: Containerization for easy deployment and scaling.

## Reference
This project is a practice project reference from: https://roadmap.sh/projects/realtime-leaderboard-system

# Getting Started
## Prerequisites
- Go 1.18+

## Installation

1、Clone the repository
```bash
git clone https://github.com/blkcor/go-leaderboard
cd go-leaderboard
```

2、Install dependencies

```bash
go mod download
```

3、Editor Configuration
```toml
[example]
```

4、Run the application
```bash
go run main.go
```



