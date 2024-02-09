# NLW Expert (Node.js) - Rocketseat 🚀
This project is a real-time research application built on Node.js. With this system, users can create polls and vote while watching real-time updates of rankings among different options.

## Requisites ⚙
Before getting started, ensure you have the following:

- Docker
- Node.js

## Setup Instructions 🛠
Follow these steps to set up the application:

- Clone the repository.
- Install dependencies using npm install.
- Set up PostgreSQL and Redis using docker compose up -d.
- Copy the .env.example file to .env with the command cp .env.example .env.
- Run the application using npm run dev.
- Test the application. (We recommend using Hoppscotch for testing.)

## HTTP

### POST `/polls`

Create a new poll.

### GET `/polls/:pollId`

Return data from a single poll.

### POST `/polls/:pollId/votes`

Add a vote to specific poll.

## WebSockets

### ws `/polls/:pollId/results`
