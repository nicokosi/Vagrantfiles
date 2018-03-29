# Vagrant files samples

## Pre-requisites

Install:
- `Vagrant` ([download](https://www.vagrantup.com/docs/installation/))
- `VirtualBox` ([download](https://www.virtualbox.org/wiki/Downloads)).

You may use your favourite package manager.
For instance, via Homebrew on macOS:
```sh
brew cask install vagrant
brew cask install virtualbox
```

## Start / pause / remove a virtual machine

Jump into a folder and run:
- `vagrant up` to start/resume a virtual machine
- `vagrant halt` to pause it
- `vagrant destroy` to remove it
- `vagrant status` to display virtual machine's status ,


`vagrant global-status --prune` lists all virtual machine states.

Run `vagrant help` for more info or browse [CLI documentation](https://www.vagrantup.com/docs/cli/).