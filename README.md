dominoctl
=========

Script for start/stop IBM Domino server on CentOS 7

 +service file for firewalld
 +service file for systemd
 +logrotate config


Config
======

/etc/domino.conf


Usage
=====

dominoctl {start|stop}

OR via systemd

systemctl {start|stop} domino
