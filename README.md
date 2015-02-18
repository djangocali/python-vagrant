# python-vagrant

A simply Vagrant instance to run python/django projects, this project can be executed under Linux, OSX or Windows.

### Requirements

* [Virtualbox] - To create virtual machines
* [Vagrant] - to create vagrant instance

### Set Up

Open your terminal and go to the project dir

This command creates or start the vagrant instance
```sh
$ vagrant up
```

This command allow to login on Linux virtual machine.

```sh
$ vagrant ssh
```
This installation creates a python virtualenv called: **env**, to use and install packages on it do the following:

```sh
$ workon env
(env)$ cd vagrant
(env)$ pip install package-name
```

To turn the vagrant instance off execute next command:

```sh
$ vagrant halt
```

and if you want to destroy the vagrant instance, execute next command

```sh
$ vagrant destroy 
```

[Virtualbox]:https://www.virtualbox.org/
[Vagrant]:https://www.vagrantup.com/

**Enjoy it and improve it!**
