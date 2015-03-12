nagios-current
==============

Keep nagios current automatically by checking if any of the configs have changed and reloading.
The `current_nagios` script makes sure the configs are valid before trying to reload nagios.
This can save you many hours
of time -- particularly if you're automatically generating most of your nagios configs.

plugins
-------

I'm going to toss my nagios/icinga plugins in here too.  They are:

* `check_read_only_fs` - alert on read-only filesystems

service naming convention
-------------------------

I would suggest that you name your services as follows:

* `app_` : app-level checks at the server level
* `meta_` : cluster-level checks (usually via localhost on the nagios server)
* `sys_` : system-level checks (disk, CPU, load, etc.)

TODO
----

* register plugin and current on https://www.monitoringexchange.org/

LICENSE
-------

The plugins, scripts, and other content in this repo is licensed under the GPL2.
