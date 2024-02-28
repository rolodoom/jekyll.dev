# jekyll.dev

Jekyll development environment with Docker and Docker Compose.

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/rolodoom/jekyll.dev/main/LICENSE)

## Contents:

- [Requirements](#requirements)
- [Usage](#usage)
  - [Up and Running](#up-and-running)
  - [Setup Jekyll Project](#setup-jekyll-project)
- [Bugs and Issues](#bugs-and-issues)
- [License](#license)

## Requirements

- Latest versions of **Docker** and **Docker Compose** installed.
- On Linux you need [to add your user to the docker group](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user).

## Usage

### Up and Running

Clone the repo and create the folder structure for the laravel source code:

```bash
git clone https://github.com/rolodoom/jekyll.dev.git
cd jekyll.dev
mkdir -p src vendor/bundle
```

Start the services:

```bash
docker-compose up -d
```

### Setup Jekyll Project

Create Jekyll Project:

-->TODO

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/rolodoom/jekyll.dev/issues) here on GitHub.

## License

This code in this repository is released under the [MIT](https://raw.githubusercontent.com/rolodoom/jekyll.dev/main/LICENSE) license, which means you can use it for any purpose, even for commercial projects. In other words, do what you want with it. The only requirement with the MIT License is that the license and copyright notice must be provided with the software.
