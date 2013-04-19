munin_puppetdb
==============

Munin plugin to graph data from PuppetDB.

The plugin will try to connect to localhost:8080 as the default value.
To override this, add the following to your config


    [puppetdb_*]
    env.host MyServer
    env.port 8080
