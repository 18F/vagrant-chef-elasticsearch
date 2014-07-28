# Vagrant Chef Elasticsearch

Simple default install for a Elasticsearch machine using Vagrant and Chef.

## Requirements

* Vagrant version 1.6.0 or greater.
* vagrant-librarian-chef

## Installation

`vagrant plugin install vagrant-librarian-chef`

## Usage

`vagrant up`

* Vagrant will spin up a single virtual machine with Elasticsearch running at 192.168.33.10
* You can then access Elasticsearch at 192.168.33.10:9200

Sometimes for some reason the Elasticsearch service doesn't start up. You can fix this with:

* `vagrant ssh`
* `sudo service elasticsearch start`