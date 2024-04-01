# Metabase Standalone

This is a docker-compose project that sets up a Metabase standalone instance along with a PostgreSQL database.

## Prerequisites

- Docker
- Docker Compose

## Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/metabase-standalone.git
    ```

2. Navigate to the project directory:

    ```bash
    cd metabase-standalone
    ```

3. Start the services:

    ```bash
    docker-compose up -d
    ```

4. Wait for the services to start up. You can check the logs for each service using the following command:

    ```bash
    docker-compose logs -f <service-name>
    ```

    Replace `<service-name>` with `metabase-standalone`, `postgres-app-db`, or `setup-postgres`.

5. Once the services are up and running, you can access Metabase by opening your web browser and navigating to [http://localhost:3000](http://localhost:3000).

## Credentials

username: a@b.com
password: metabot1

## Requirements

Just docker