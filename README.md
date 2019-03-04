# Magento-Landofile

This repository provides a `.lando` file for a local Lamp stack that can be used for Magento Commerce development.

## Prerequisites
- Docker installed.
- Dev With Lando installed.

## Usage
Just copy the .lando file into your Magento installation directory and use `lando start` to initialise the Docker images. Afterwards you can use the web interface to install your Magento instance.

## `lando magento`
There is an additional command `lando magento` that can be used to execute Magento commands on the `appserver`. E.g. use `lando magento cache:clean` to clean the caches. All arguments are being passed through to the appserver.
