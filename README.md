# docker-haskell - Docker containers for Haskell

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-haskell/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-haskell:latest ghc --version
The Glorious Glasgow Haskell Compilation System, version 7.6.3
docker run --rm mcandre/docker-haskell:latest cabal --version
cabal-install version 1.16.0.2
using version 1.16.0 of the Cabal library
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
