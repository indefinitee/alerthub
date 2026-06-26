# AlertHub

AlertHub is a backend platform for processing incoming events, matching them against watchlists/rules, creating alerts, and tracking user actions.

## MVP

The first version allows users to:

- register and log in;
- create watchlists;
- add watchlist items;
- ingest external events;
- create alerts when incoming events match watchlist items;
- view and resolve alerts;
- store audit log for important actions.

## Tech Stack

- Go
- PostgreSQL
- pgx
- sqlc
- golang-migrate
- Docker Compose
