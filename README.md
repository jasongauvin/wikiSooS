# Wiki

![Go](https://github.com/jasongauvin/wikiPattern/workflows/Go/badge.svg?branch=master)

This repository is to train on design patterns, this iteration is about the MVC design pattern.

---
## Install

With docker: 

Refer to [Docker-Setup](#docker-setup) to install with docker.


Without docker: 

If not, to run this project, you will need to install the following dependencies on your system:

- [go](https://golang.org/doc/install)

 ```sh
 ```

## Docker-Setup

Run `docker-compose up --build` then enter in the container with `docker-compose exec app /bin/sh`.

Create the binary of the app with `go build -o main .` then launch the binary with `./main`

## Branch naming convention

You branch should have a name that reflects it's purpose.

It should use the same guidelines as [COMMIT_CONVENTIONS](COMMIT_CONVENTIONS.md) (`feat`, `fix`, `build`, `perf`, `docs`), followed by an underscore (`_`) and a very quick summary of the subject in [kebab case][1].

Example: `feat_add-image-tag-database-relation`.

## Pull requests (PR)

Pull requests in this project follow two conventions, you will need to use the templates available in the [ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE) folder :

- Adding a new feature should use the [FEATURE_REQUEST](.github/ISSUE_TEMPLATE/FEATURE_REQUEST.md) template.
- Reporting a bug should use the [BUG_REPORT](.github/ISSUE_TEMPLATE/BUG_REPORT.md) template.

If your pull request is still work in progress, please add "WIP: " (Work In Progress) in front of the title, therefor you inform the maintainers that your work is not done, and we can't merge it.

The naming of the PR should follow the same rules as the [COMMIT_CONVENTIONS](COMMIT_CONVENTIONS.md)