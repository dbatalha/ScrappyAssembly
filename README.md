# Scrappy Assembly

## Description

Scrappy Assembly is a project aimed at creating the environment necessary for assembly using a scrappy approach.

## Prerequisites

- Docker
- Docker Compose

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/scrappy-assembly.git
    ```

2. Navigate to the project directory:

    ```bash
    cd scrappy-assembly
    ```

3. Set up the environment variable `MONGO_DB_VOL` to specify the MongoDB data volume path. Replace `/Users/danielbatalha/data` with the desired path on your system.

    ```bash
    export MONGO_DB_VOL=/Users/danielbatalha/data
    ```

## Usage

### Docker Compose

1. Ensure the environment variable `MONGO_DB_VOL` is set.

2. Run the following command to start the services defined in the docker-compose file:

    ```bash
    docker-compose up
    ```

3. To stop the services, press `Ctrl + C`, and then run:

    ```bash
    docker-compose down
    ```

