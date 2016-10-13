# Lensity

> Finding connection with a human lens

## Team

  - __Product Owner__: [Josphine Eng](https://github.com/ChirpingMermaid)
  - __Scrum Master__: [Julie Truong](https://github.com/Truong-Julie)
  - __Development Team Members__: [Brian Kilrain](https://github.com/bkilrain)

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Docker Development](#docker-development)
    1. [Build Image](#build-image)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Compile React](#compile-react)
    1. [Seed Database Data](#seed-database-data)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> Some usage instructions

## Requirements

- Node 0.10.x
- Postgresql 6.1.x
- Webpack 1.13.x

## Docker Development

### Build Image

In root folder run:
```sh
docker build -t app .
```

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
```
### Compile React

From within the root directory run webpack:

```sh
webpack -watch
```

### Seed Database Data

From db/seeds directory:

Make sure postgres is running
Drop database and create empty database

```sh
drop database app;
// DROP DATABASE
create database app;
// CREATE DATABASE
```
Restart main server

Run seed.js using node
```sh
run node seeds.js
```

email: kumquat@gmail.com
pw: 123
* If pushing to redis server, uncomment out the redis line. Note* this has not been tested.


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
