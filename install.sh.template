#!/bin/bash
mkdir -p /lib/systemd/system
mkdir -p /usr/local/lib
cp lxcfs.service /lib/systemd/system/lxcfs.service
cp lxcfs /usr/local/bin/lxcfs
cp -rf lxcfs /usr/local/lib/
chmod ａ+x lxcfs /usr/local/bin/lxcfs
systemctl enable lxcfs.service
systemctl restart lxcfs.service
