[![Build Status](https://travis-ci.org/getsubrosa/subrosa.svg)](https://travis-ci.org/getsubrosa/subrosa)

# About

Sub Rosa is a set of opinionated Ansible playbooks inspired by
[Sovereign](https://github.com/al3x/sovereign)
that can be used to run your own **secure**, personal cloud.  While Sovereign
gives you a variety of options and configurations, we're selecting a specific
suite of services that focuses on security and privacy while minimizing
dependencies in the name of maintainability.

# Usage

## Development

### Requirements

* [VirtualBox 4.3.18](http://download.virtualbox.org/virtualbox/4.3.18/)
* [Vagrant 1.7.2](http://www.vagrantup.com/download-archive/v1.7.2.html)
* [Ansible 1.8.2](http://releases.ansible.com/ansible/)

### Getting started

If your Vagrant machine isn't already up, `vagrant up` will start and provision
the vagrant environment.

If your Vagrant machine is already running, `vagrant provision` will provision
the running vagrant environment.

## Production
