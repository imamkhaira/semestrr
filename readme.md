# Semestrr Setup

## for Production use

1. Rename or symlink `docker-compose.prod.yml` into `docker-compose.yml`
2. copy env.example to .env then edit to your need.
3. run the project: `docker-compose up -d && docker compose logs --follow`
4. open the UI in your browser or configure your reverse proxy
5. done

## For Development

You are advised to use Unix-like system such as Linux, MacOS or Windows Subsystem Linux.
There is no plan to make this run in Windows natively.

1. Rename or symlink `docker-compose.dev.yml` into `docker-compose.yml`
2. copy env.example to .env then edit to your need.
3. run the dev containers: `docker compose up -d && docker compose logs --follow`
4. begin editing the project using remote container feature in your favourite IDE.
