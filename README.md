# THYME WebGIS
A webgis spatial directory of the THYME region Bioeconomy.

## Installation
Requires:
- PostreSQL
-- Create a DB that will be used to store data, give the appropriate user ownership of the DB
- PostGIS
-- [Learn more about PostGIS](http://postgis.net/workshops/postgis-intro/index.html)
- pgAdmin (optional)


## development stack (for now):
Client-side:
- HTML and CSS for layout and design
- JS for interaction and AJAX requests to server (add, remove, edit, load data)
Server-side:
- Apache directing requests and serving PHP results
- PHP processing (API) request types and querying and updating DB
Database:
- PostgreSQL
- PostGIS (a wrapper/extension to PostgreSQL for gis requests/operations)
