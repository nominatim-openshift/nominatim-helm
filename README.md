# nominatim postgres

Attempts to install a database pod which will consist of:

- https://github.com/nominatim-openshift/nominatim-postgresql
- https://github.com/nominatim-openshift/nodejs-runsqlscript

NOTE:

Images are configured to build automatically in quay.io: 

- Nominatim / Postgres: https://quay.io/repository/ajarrett/nominatim-postgresql
- NodeJS Script Runner: https://quay.io/repository/ajarrett/nodejs-runsqlscript

Why?

To initialise a postgres database with postgis extensions installed.  The postgis extensions are enabled by running a post install hook job 
