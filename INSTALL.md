# This is my Docker Compose Laravel Fork

### Preparation step

#### Clone new project
> git clone https://github.com/aschmelyun/docker-compose-laravel.git dclf

#### - cleanup src & stop other docker containers
> docker compose up -d --build app

#### - remove src from this repository to handle it later in separate project
> git rm -r --cached /src

#### Installation step
> docker compose run --rm composer create-project laravel/laravel .