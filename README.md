# yesod-quickstart

Yesod quickstart is a basic [Vagrant](http://vagrantup.com/)
configuration that will create an Ubuntu virtual machine with the
current [Haskell Platform](http://hackage.haskell.org/platform/).
It'll also setup [Cabal](http://www.haskell.org/cabal/) and [Yesod](http://www.yesodweb.com/).

It's using [Chef](http://www.opscode.com/chef/) to provision the VM.

## Requirements

1. Install VirtualBox: https://www.virtualbox.org/wiki/Downloads
2. Install Vagrant (**don't** use the Ruby Gem): http://downloads.vagrantup.com/
3. Install the [Berkshelf Vagrant plugin](https://github.com/RiotGames/vagrant-berkshelf):
   `vagrant plugin install vagrant-berkshelf`

## Usage

Once the requirements are installed, you can use this like any other Vagrant VM:

* To create the VM or start an existing VM run `vagrant up`
* To destroy a VM run `vagrant destroy`
* If you want to reboot the VM run `vagrant reload`
* A VM shutdown can be done with `vagrant halt`

If you need more information or want to tweak the configuration, have
a look at the [Vagrant Documentation](http://docs.vagrantup.com/v2/).
