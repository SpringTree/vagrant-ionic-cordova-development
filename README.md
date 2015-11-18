Ionic development setup for Cordova
===================================
The repository contains a VagrantFile to create an Ionic development environment

It uses the `ubuntu/trusty64` box from the list of [publicly available catalog of Vagrant boxes](https://atlas.hashicorp.com/boxes/search)
This box contains an Official Ubuntu Server 14.04 LTS (Trusty Tahr)

It will also install the following software:

* NodeJS 0.12
* git
* curl

The following NPM modules will be (globally) installed:

* bower
* ionic
* cordova
* yo (yeoman)
* generator-ionic-gulp (yeoman generator)