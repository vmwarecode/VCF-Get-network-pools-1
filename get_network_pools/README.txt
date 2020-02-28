INTRODUCTION:
------------

This module contains script files to get network pools.

REQUIREMENTS:
------------

This module requires the following modules:

 * Python 3
   Libraries
  * requests
  * sys
  * json
  * time

 * The scripts must be run outside sddc-manager environment.

 * DNS resolution must be done for sddc-manager.


PREREQUSITES:
-------------

The following data is required

ID of the network


USAGE:
-----
Usage:	python get_network_of_network_pools.py <hostname> <username> <password>