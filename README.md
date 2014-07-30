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

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
