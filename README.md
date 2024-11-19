# VILT docker-compose template

Docker containers for a VILT project on local

- Vuejs
- Inertia
- Laravel
- Tailwind

included containers

- Nginx
- Node
- Php 8.2
- Mysql
- phpMyAdmin
- Redis
- Opensearch clusters
- Opensearch-Dashboard
- Fluent-bit

## How to use

> composer create-project laravel/laravel PROJECT_NAME

1. replace PROJECT_NAME with your project name
2. replace NETWORK_NAME with your network name
3. copy .env.example to .env and provide your configs
4. docker-compose run -d

