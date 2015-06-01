from opensuse:tumbleweed
maintainer Kevin Walter <kevin.walter.private@gmail.com>

run zypper addrepo http://download.opensuse.org/repositories/devel:/languages:/python/openSUSE_Tumbleweed/devel:languages:python.repo

run zypper --non-interactive --gpg-auto-import-keys install salt-master salt-api

run useradd -p 'NR9AEhcFVd8Y.' salt
add master /etc/salt/master

expose 4505 4506 8000

cmd salt-master -d && salt-api
