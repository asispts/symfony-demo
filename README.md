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

## Changelog
  ### [v3.1]
  - `PHP: v7.1`
  - `Symfony: v4.1`

  ### [v3.0]
  - `PHP: v7.1`
  - `Symfony: v4.0`

  ### [v2.0]
  - `PHP: v7.1`
  - `Symfony: v3.3`

  ### [v1.1]
  - `PHP: v5.6`
  - `Symfony: v3.3`

  ### [v1.0]
  - `PHP: v5.6`
  - `Symfony: v3.2`


[v3.1]: https://github.com/asispts/symfony-demo/releases/tag/v3.1
[v3.0]: https://github.com/asispts/symfony-demo/releases/tag/v3.0
[v2.0]: https://github.com/asispts/symfony-demo/releases/tag/v2.0
[v1.1]: https://github.com/asispts/symfony-demo/releases/tag/v1.1
[v1.0]: https://github.com/asispts/symfony-demo/releases/tag/v1.0
