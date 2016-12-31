# Rakushu Quickstart

## Installation

### RubyGems

https://rubygems.org/pages/download

### Homebrew

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### git

```bash
brew install git
```

### Docker

Install the two packages below.

- Docker for Mac
 - https://docs.docker.com/docker-for-mac/
- Docker Toolbox
 - https://github.com/docker/toolbox/releases/tag/v1.12.5

Please execute the following commands on Terminal.

```bash
$ gem install docker-sync
$ brew install fswatch
$ brew install unison
$ brew install rsync
```

## Getting Started

```bash
$ git clone git@github.com:rakushu-dev/rakushu.git
$ cd rakushu
$ docker-compose up
```

If you've got something like the following, you're ready to get on Rails 5 ! Access to **localhost:3000** with a web browser.

```bash
web_1  | => Booting Puma
web_1  | => Rails 5.0.0.1 application starting in development on http://0.0.0.0:3000
web_1  | => Run `rails server -h` for more startup options
web_1  | Puma starting in single mode...
web_1  | * Version 3.6.2 (ruby 2.3.1-p112), codename: Sleepy Sunday Serenity
web_1  | * Min threads: 5, max threads: 5
web_1  | * Environment: development
web_1  | * Listening on tcp://0.0.0.0:3000
```

There could be some other dependencies or environment that you specifically need to have. If you come across any trouble please inform @honake.

## Dependencies

- Ruby 2.3.1
- Rails 5.0.0
- PostgreSQL
- Docker
