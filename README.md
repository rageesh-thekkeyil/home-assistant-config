# Rageesh's Home Assistant Configuration Files 

This is my currently active set of configuration files for my [Home Assistant](https://home-assistant.io) running on Raspberry Pi.
If you are interested in following my progress be sure ⭐️ Star this repository.


## Configuration Organisation

I've limited the contents of configuration.yaml and utilised [packages](https://www.home-assistant.io/docs/configuration/packages/) to provide some grouping, in order to make it easier to understand and maintain.

Packages provide an simple way to encapsulate all the different configuration elements for a adding support for a given component or device. Rather than needing to update many different files the changes are kept contained in a single file per package.

## Core Hardware of Home Assistant Hub

- [Raspberry Pi 4 Model B 4GB RAM](https://www.raspberrypi.org/blog/8gb-raspberry-pi-4-on-sale-now-at-75/) - Core control system, running on [Hass.io](https://www.home-assistant.io/hassio/).


## Configuration File Status

This is a to-do item to set up a CI/CD using travisCI. If this successfully passes, then my Pi will update itself with the latest configuration automatically [link](https://github.com/shortbloke/home_assistant_config/blob/master/docs/build_deploy.md).


**Note: Private information is stored in secrets.yaml (not uploaded)**