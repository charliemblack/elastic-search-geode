This is a little sample to get users up and running with a typical Geode cluster quickly.

If you need to perform something different than those assumption feel free to fork the
project and do what you wish.

.
├── config
│   ├── site_a.properties    - The Properties for the Geode Cluster - Edit this file
│   └── site_a.xml           - The Cache Defintion to use with Geode
├── lib                      - Any libraries we might need can go here
├── scripts
│   ├── clear_data.sh        - Will remove the contents under the data directory
│   ├── start_geode.sh       - This starts up Geode
│   ├── start_locator.sh     - The command that gets run on a system to start a locator
│   ├── start_server.sh      - The command that gets run on a system to start a server
│   └── stop_geode.sh        - Stop Geode
