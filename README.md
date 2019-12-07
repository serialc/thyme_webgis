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
Collaboration/versioning:
- Github ([here](https://github.com/serialc/thyme_webgis))

Unit testing:
- Travis ([check](https://travis-ci.com/serialc/thyme_webgis))

Client-side:
- HTML and CSS for layout and design
- JS for interaction and AJAX requests to server (add, remove, edit, load data)

Server-side:
- Apache directing requests and serving PHP results
- PHP processing (API) request types and querying and updating DB

Database:
- PostgreSQL
- PostGIS (a wrapper/extension to PostgreSQL for gis requests/operations)

## To do list
- [ ] Make the admin area (.htaccess for now)
- [ ] Allow admin data upload
- [ ] Create API that retrieves data from DB, allow export
- [ ] Adapt front-end webmap to allow layer select and data export
