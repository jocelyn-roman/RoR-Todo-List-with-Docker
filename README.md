# RUBY ON RAILS - TO DO LIST
This is a Ruby on Rails Web App for creating a To Do List using Docker.

## Authors

- **Jocelyn Roman**

## Setup & Dependencies

- Ruby 3.3.0
- Tailwind CSS
- PostgreSQL

## Instalation

### Prerequisites
- Docker


### Steps

1. Run `docker-compose build` 
2. Run `docker-compose run web rails db:create`
3. Run `docker-compose run web rails tailwindcss:install`
4. Run `docker-compose up` to start the container up and running.
5. Go to `http://localhost:3000` to access the web app.

#### Helpful commands
- `docker-compose run web rails tailwindcss:watch` to watch the changes for Tailwind CSS.