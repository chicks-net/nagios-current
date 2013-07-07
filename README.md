nagios-current
==============

Keep nagios current automatically by checking if any of the configs have changed and reloading.
It makes sure the configs are valid before trying to reload.  This can save you hundreds of hours
of time -- particularly if you're automatically geneating a large portion of your nagios configs.

I'm going to toss my plugins in here too.  The first one checks for read-only filesystems.

TODO
----

* register plugin and current on https://www.monitoringexchange.org/
* pick a LICENSE
