vagrant-base-box
================

My base vagrant box. This package was first built using [protobox](http://getprotobox.com/)'s GUI but includes my own modifications and structure. Protobox's vagrant setup uses [ansible](http://www.ansible.com/).

Install
-------
*This package uses vagrant. Not sure what that is? Go [here](https://vagrantup.com/).*

* `mv data/config/common.yml-dist data/config/common.yml`.
* Edit `data/config/common.yml` to your liking.
* Add your dotfiles to `data/dot/` if needed.
* `vagrant up`
