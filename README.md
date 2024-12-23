# Semestrr Setup

## for Production use

1. Rename or symlink `docker-compose.prod.yml` into `docker-compose.yml`
2. copy `env.example` to `.env` then edit to your need.
3. run the project: `docker-compose up -d && docker compose logs --follow`
4. open the UI in your browser or configure your reverse proxy
5. done

## For Development

You are advised to use Unix-like system such as Linux, MacOS or Windows Subsystem Linux.
There is no plan to make this run in Windows natively.

1. Rename or symlink `docker-compose.dev.yml` into `docker-compose.yml`
2. copy `env.example` to `.env` then edit to your need.
3. run the dev containers: `docker compose up -d && docker compose logs --follow`
4. begin editing the project using remote container feature in your favourite IDE.

# About Semestrr
`Semestrr` is an Academic Management System (AMS) designed to enable students 
to manage their courses effectively throughout a semester. 
An academic management system is a comprehensive software solution 
designed to simplify and streamline administrative and academic processes within educational institutions.

Semestrr offers a cost-effective academic management solution is tailored for schools and universities,
eliminating the need for institutions to develop their own systems while being far more affordable over its competitor.

# Project Stack

## Frontend
1. TypeScript - a typed superset of JavaScript
2. Next.JS - a React based frontend framework
3. Tailwind - a CSS styling tool

## Backend
1. Golang
2. Echo v4 - routing and http library
3. GORM - Object Relational Mapper
4. migrate - Database migration tool
5. MariaDB - relational database management system

## Deployment:
1. Docker
2. Linux


