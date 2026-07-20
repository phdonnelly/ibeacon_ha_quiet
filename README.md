### Please note: I no longer have the bandwidth to monitor or update this fork. A more full featured replacement is available here: https://github.com/agittins/bermuda

# ibeacon_ha_quiet
A quick and dirty fork of the built in ibeacon integration in HA that gives the users the ability to disable the generation of new entities

NB: this custom addon currently ignores beacons with random mac addresses entirely. The integration does not store a list of existing random mac beacons to compare against like it does for unique mac addresses; fixing this will required tweaking the _async_restore_from_registry code to address this.
