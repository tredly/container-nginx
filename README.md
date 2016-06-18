# nginx Container for Tredly

Version 1.0.2 June 18 2016

## Installation

Requires Tredly 1.0.0-rc.1 <https://github.com/tredly/tredly> or later

### Modifying container options

By default, the container name is "wordpress". Change this by changing containerName in the Tredlyfile prior to building this container.

Many other options can be changed in the Tredlyfile

### nginx configuration

The nginx configuration files have a number of non standard settings. If you wish to use a completely default installation of nginx, do not copy the nginx.conf file into the container (comment the line out).

The Tredlyfile has a number of extra configuration options in regards to URL configuration. SSL configuration and SSL folder copying can be removed if you do not need to use SSL.

## License

Tredly is released under the [MIT License](http://www.opensource.org/licenses/MIT).
