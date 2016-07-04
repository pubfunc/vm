# Yousemble Vagrant

Homestead machine configuration, using forked laravel/homestead 2.0 with port fixes.

The Homestead fork is a public repo on github: [yousemble/homestead](https://github.com/yousemble/homestead)

## Installation

#### 1. Install [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

#### 2. Clone this repo in *D:\dev\yousemble\vagrant*

```shell
cd /d/dev/yousemble
git clone git@bitbucket.org:yousemble/vagrant.git
```

> If you are not using the standard folder structure or you would like to
edit the Homestead.yaml file in some other way, please create your own branch.
> `git branch <branch>`


#### 4. Install Composer Deps

```shell
cd /d/dev/yousemble/vagrant
composer install
```

#### 3. Build the VM

```shell
vagrant up
```

> [atlas.hashicorp.com/laravel/boxes/homestead](https://atlas.hashicorp.com/laravel/boxes/homestead) Box version < 0.4.0
