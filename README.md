# Supported tags and respective `Dockerfile` links

-	[`8.0`, `8` (*8.0/Dockerfile*)](https://github.com/rwsdigital/odoo-docker/blob/master/8.0/Dockerfile)
-	[`9.0`, `9` (*9.0/Dockerfile*)](https://github.com/rwsdigital/odoo-docker/blob/master/9.0/Dockerfile)
-	[`10.0`, `10`, `latest` (*10.0/Dockerfile*)](https://github.com/rwsdigital/odoo-docker/blob/master/10.0/Dockerfile)

Latest Nightly Build Support + Werkzeug Real Client IP (Proxy Mode)
======

This is a fork of the official Docker image's repo. Odoo Docker image is based on versions of nightly build in some cases too old. With this repo you have Dockerfile that will download the latest nightly build version, so that all the security updates and bugfix will be downloaded in the Docker image built.
Furthermore, if you'll enable proxy mode in the odoo.conf and correctly configure nginx conf file, you'll see the correct client ip address in werkzeug log.
