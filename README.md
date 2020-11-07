# Elixir Phoenix Docker Template

Quick start for elixir and phoenix framework on docker.


Suggested alias: `alias dmix="docker-compose run --rm phoenix mix"`

## Setup
1. `docker-compose build`
2. `dmix phx.new . --app <APP_NAME>`
3. change dev database host to `db`
4. `dmix ecto.create`
5. `docker-compose up`
6. done
