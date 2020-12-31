FROM httpd:2.4-alpine

ARG WEB_USER
ARG WEB_GROUP
ARG APACHE_ROOT_DIR

COPY httpd-vhosts.conf ${APACHE_ROOT_DIR}/conf/extra/httpd-vhosts.conf
COPY httpd.conf ${APACHE_ROOT_DIR}/conf/httpd.conf
