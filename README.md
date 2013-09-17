# yesod-quickstart

Yesod quickstart is a basic [Vagrant](http://vagrantup.com/)
configuration that will create an Ubuntu virtual machine with the
current [Haskell Platform](http://hackage.haskell.org/platform/).
It'll also setup [Cabal](http://www.haskell.org/cabal/) and install [Yesod](http://www.yesodweb.com/).

This package will install [GHC 7.6.3](http://www.haskell.org/ghc/docs/7.6.3/html/users_guide/release-7-6-3.html)
and [The Haskell Platform 2013.2.0.0](http://www.haskell.org/platform/changelog.html).
GHC and the Haskell Platform will be compiled. The same applies to Yesod,
so expect the initial setup process to take 30 - 60 minutes (depending on your host machine and internet connection).

## Requirements

1. Install VirtualBox: https://www.virtualbox.org/wiki/Downloads
2. Install Vagrant using your package manager.
   **Don't use** the Ruby Gem.
   It's outdated and not compatible with Berkshelf Vagrant:
   http://downloads.vagrantup.com/
3. Install the [Berkshelf Vagrant plugin](https://github.com/RiotGames/vagrant-berkshelf):
   `vagrant plugin install vagrant-berkshelf`

## Usage

Once the requirements are installed, you can use this like any other Vagrant VM:

* Create the VM or start an existing VM: `vagrant up`
* Connect to the VM: `vagrant ssh`
* Destroy the VM: `vagrant destroy`
* Reboot the VM: `vagrant reload`
* Shutdown the VM: `vagrant halt`

If you need more information or want to tweak the configuration, have
a look at the [Vagrant Documentation](http://docs.vagrantup.com/v2/).
