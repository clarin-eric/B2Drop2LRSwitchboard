# LR SWITCHBOARD -- EUDAT/B2DROP integration
Code Repository for the B2DROP plugin to bridge to the CLARIN Language Resources Switchboard.

# Module Description

This owncloud plugin allows users to connect their resources from their personal cloud store to the
CLARIN Language Resource Switchboard.  It extends the user interface of the B2DROP resources
list. For each resource, the '...' menu is extended to contain a menu item poiting to the LR
switchboard. Once activated, a new browser tab opens with the switchboard; it fetches the resource
from the cloud, and processes it as usual.

# Install

1. on your B2DROP server go to the <owncloud>/apps directory
2. git clone this repository
3. enable the app on the B2DROP/owncloud web interface

# Website

An temporary B2Drop instance has been set-up and is being served at:

The switchboard is currently being served at:

```http://weblicht.sfs.uni-tuebingen.de/owncloud ```

Please contact claus.zinn@uni-tuebingen.de for the login credentials so that you can test the b2drop
plugin.



# Status

This is a quick hack, getting inspirations from the B2Drop plugin b2sharebridge, see

```https://github.com/EUDAT-B2DROP/b2sharebridge.git ```.

Given the radical changes / deletions from the b2sharebridge code, its git log history has been
deleted.

The software is currently being developed.  Stay tuned.

