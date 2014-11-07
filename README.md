vagrant-base-box
================

My base vagrant box. This package was first built using [protobox](http://getprotobox.com/)'s GUI but includes my own modifications and structure. Protobox's vagrant setup uses [ansible](http://www.ansible.com/).

Install
-------
*This package uses vagrant. Not sure what that is? Go [here](https://vagrantup.com/).*

* Move `vagrant/data/config/common.yml-dist` to `vagrant/data/config/common.yml`.
* Edit `vagrant/data/config/common.yml` to your liking.
* `cd vagrant/`
* `vagrant up`
