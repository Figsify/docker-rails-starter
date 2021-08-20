# RoR Docker Development Starter Template

## New Installation

#### 0. Create .env file
`mv .env.example .env`

#### 1. Init Rails Project
`docker-compose run --no-deps app rails new . --force ---database=<database>`

#### 2. Update Database Config
`mv example.database.yml app/config/database.yml`

#### 3. Start
`docker-compose up --build`