# Sub Rosa

[![Build Status](https://travis-ci.org/getsubrosa/subrosa.svg)](https://travis-ci.org/getsubrosa/subrosa)

## Usage

If your Vagrant machine isn't already up, `vagrant up` will start and provision
the vagrant environment.

If your Vagrant machine is already running, `vagrant provision` will provision
the running vagrant environment.

## Services

### Core

  * **vpn**
    - [openvpn](https://openvpn.net)
  * **mail**
  * **calendar**
    - [owncloud](https://owncloud.org)
  * **contact**
    - [owncloud](https://owncloud.org)
  * **backup**
    - [tarsnap](https://tarsnap.com)

### Extra

  * **dropbox clone**
    - [owncloud](https://owncloud.org)
  * **blog**
    - [Ghost](https://tryghost.org)
  * **git**
    - [Gitolite](http://gitolite.com/gitolite/index.html)
    - [Gitlab](https://about.gitlab.com/)
  * **photos**
  * **todos**
  * **evernote clone**
  * **readitlater clone**
    - [wallabag](https://www.wallabag.org/)

## Features

### Must

  * secure
  * encrypted
  * easy to install
  * easy to maintain
  * mobile
  * documented
  * tested / dogfooded

### Should

  * minimize language / installation dependencies
  * multiple image installation paths

### Could

## TODO

## Ideas

  * [Create secure AMIs](https://github.com/kickstarter/build-ubuntu-ami)
  * [Best practices](http://docs.ansible.com/playbooks_best_practices.html)
  * [Dynamic inventory](http://docs.ansible.com/intro_dynamic_inventory.html)

## Similar

  * [https://github.com/al3x/sovereign](https://github.com/al3x/sovereign)

## Things to watch

  * [https://github.com/WhisperSystems/Flock/issues/19](https://github.com/WhisperSystems/Flock/issues/19) - Flock's ability to sync with OwnCloud
