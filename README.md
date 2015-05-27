# docker-haskell - Docker containers for Haskell

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-haskell/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-haskell:6.12 ghc --version
The Glorious Glasgow Haskell Compilation System, version 6.12.1
docker run --rm mcandre/docker-haskell:6.12 cabal --version
cabal-install version 0.8.0
using version 1.8.0.2 of the Cabal library
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)

## Debian/Ubuntu

```
$ sudo apt-get install docker.io build-essential
```

## RedHat/Fedora/CentOS

```
$ sudo yum install docker-io
```

## non-Linux

* [VirtualBox](https://www.virtualbox.org/)
* [Vagrant](https://www.vagrantup.com/)
* [boot2docker](http://boot2docker.io/)

### Mac OS X

* [Xcode](http://itunes.apple.com/us/app/xcode/id497799835?ls=1&mt=12)
* [Homebrew](http://brew.sh/)
* [brew-cask](http://caskroom.io/)

```
$ brew cask install virtualbox vagrant
$ brew install boot2docker
```

### Windows

* [Chocolatey](https://chocolatey.org/)

```
> chocolatey install docker
```
