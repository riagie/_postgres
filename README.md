# PostgreSQL Shared Docker Service

A minimal PostgreSQL 12 Docker service intended for local development. This setup is designed to be shared across multiple projects using a common Docker network.

## Features

-   PostgreSQL 12
-   Configurable via `.env` file
-   Persistent data using Docker volumes
-   Built-in healthcheck
-   Compatible with external Docker Compose projects via `shared_network`
