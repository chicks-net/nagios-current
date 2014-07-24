nagios-current
==============

Keep nagios current automatically by checking if any of the configs have changed and reloading.
The `current_nagios` script makes sure the configs are valid before trying to reload nagios.
This can save you many hours
of time -- particularly if you're automatically geneating a large portion of your nagios configs.

I'm going to toss my plugins in here too.  The first one checks for read-only filesystems.

TODO
----

* register plugin and current on https://www.monitoringexchange.org/

LICENSE
-------

The plugins, scripts, and other content in this repo is licensed under the GPL2.
