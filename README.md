# README
[![CI](https://github.com/rikoroku/phobos/actions/workflows/ci.yml/badge.svg)](https://github.com/rikoroku/phobos/actions/workflows/ci.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/2e6390a6758436bd9fa3/maintainability)](https://codeclimate.com/github/rikoroku/Phobos/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/2e6390a6758436bd9fa3/test_coverage)](https://codeclimate.com/github/rikoroku/Phobos/test_coverage)

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
