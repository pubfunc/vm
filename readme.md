# Pubfunc Vagrant

Localized Homestead machine configuration, using laravel/homestead.

## Installation

#### 1. Install [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

#### 2. Clone this repo

```shell
git clone git@bitbucket.org:pubfunc/vm.git
```

> If you are not using the standard folder structure or you would like to
edit the Homestead.yaml file in some other way, please create your own branch.
> `git branch <branch>`


#### 4. Install Composer Deps

```shell
composer install
```

#### 3. Build the VM

```shell
vagrant up
```

> [atlas.hashicorp.com/laravel/boxes/homestead](https://atlas.hashicorp.com/laravel/boxes/homestead) Box version < 0.4.0
