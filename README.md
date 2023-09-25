# apache2

## Purpose of this Cookbook

This is a base Apache 2 cookbook for use on Ubuntu 20.04 in order to demonstrate the Inspec Test and how to move it from the traditional `\test\integration\default` path to the `\compliance\profile\apache2` path in order to use this for both integration testing as well as the Compliance Phase.

## Description of the current cookbook

* This cookbook was created with the `chef generate cookbook apache2` command and pushed to a [github repo](https://github.com/snohio/apache2)
* It is a basic cookbook that simply installs Apache2 for a Ubuntu (18/20/22) server.
* The default_test that was created by the generate was modified to check for the root user (removed the skip) and that port 80 IS listening and removed that skip as well.
* The kitchen.yml file was modified a little to just specify Ubuntu 20 using the default Vagrant driver.

## Demonstration Steps to move your default_test to a
