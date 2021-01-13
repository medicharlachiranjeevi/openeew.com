# OpenEEW Documentation Website

This OpenEEW website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator, and hosted on Github.

### Setup

- Install [node](https://nodejs.org/en/download/) and [yarn](https://classic.yarnpkg.com/en/docs/install).
- Clone this repo.
- Run `yarn install`.

To run, 
```
yarn run start
```
### Deployment

```
$ GIT_USER=<username> yarn deploy
```
This command is a convenient way to build the website and push to the `gh-pages` branch with GitHub Pages hosting.

For Docker Setup
### Setup

- Install [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/).
- Clone this repo.
- Run `docker-compose build`.
- To run, 
```
    docker-compose run
```

### Deployment Using docker-compose 
```
    docker-compose exec web GIT_USER=<username> yarn deploy
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.


## License

This document site is licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).
