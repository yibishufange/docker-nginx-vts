NGINX VTS
=========

This project combines the alpine docker nginx (https://github.com/nginxinc/docker-nginx/) with the nginx-vts-module (from https://github.com/vozlt/nginx-module-vts) and the apk logrotate package.

There is no run of the logrotate package, it is expected to be run outside the container via a systemd timer or a cron job.


Thanks
------

- nginx team for providing the base image
- debian logrotate team for inspiration on the logrotate file configuration

