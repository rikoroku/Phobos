# README
[![CI](https://github.com/rikoroku/phobos/actions/workflows/ci.yml/badge.svg)](https://github.com/rikoroku/phobos/actions/workflows/ci.yml)

## Setup

```bash
$ docker-compose build
$ docker-compose run --rm app bundle exec rails db:setup
```

## Commands

```bash
# Starting rails server
$ docker-compose up

# Linting
$ docker-compose run --rm app bundle exec rubocop

# Testing
$ docker-compose run --rm app bundle exec rspec
```
