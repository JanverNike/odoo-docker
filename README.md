About this Repo
===============

A Docker Compose environment which runs Odoo in one container and a Postgres Database instance in another.



### Running with Docker Compose

1. Install [Docker and Docker Compose](https://docs.docker.com/compose/install/)
2. Run `docker-compose up -d` from the root of this project.
3. Access local `http://{docker_host}:8069` from your web browser to finish setting up Odoo ERP.




Goals
=====
* Add Odoo 11
* Provide SSL with [letsencrypt-nginx-proxy](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion)
* Provide newer smaler Postgres bindings (postgres:10-alpine)
* Add a docker-compose file
* Odoo 10 Build with release 20170803
* Odoo 10 Provide phonenumbers & py-Asterisk to enable Asterisk Click2dial
* Correct ownership for /var/lib/odoo 
* Provide as close to a 'drop in replacement' of the Official Docker image as possible.
(from a usability standpoint, e.g. creating the odoo user with the same uid number)
* Odoo 10 Provide newer versions of node, NPM and LESS (less bugs, better perf.)
* Odoo 10 Provide newer Python and Python packages. (less bugs, better perf.)
* Odoo 10 Provide optional Python packages to enable missing Odoo features (flanker email validation, workers>0 support)
* Provide a better developer and benchmarking suite (newrelic and watchdog)sourcetree



This is a fork of Docker image git repo [hibou-io/odoo-docker](https://github.com/hibou-io/odoo-docker).

Official Odoo Docker image git repo for [Odoo](https://registry.hub.docker.com/_/odoo/).

