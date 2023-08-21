FROM centos/httpd-24-centos8

CMD ab -dSrk -c 20 -n 50000000 http://${SCALE_SERVICE_HOST}:${SCALE_SERVICE_PORT}/index.php
