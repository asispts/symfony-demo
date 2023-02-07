# Dockerize Symfony Demo Application

This is just a repository to dockerize every version of [symfony/demo](https://github.com/symfony/demo) application. Nothing special.

## Why?
Because:
  1. All of my projects use `docker`,
  2. I don't have any installed web server in my computer,
  3. I know there is a `symfony` binary app, but I don't want to install it globally,
  4. You can run/test/view every version of `symfony/demo` without polluting your system.

## Requirement
  - `docker`
  - `docker-compose` (optional)

## Usage
  There's no need to configure anything to run the application. Run this command
  ```
  docker-compose up -d
  ```
  then access the application in your browser at http://localhost:8080.
