from opensuse:tumbleweed
maintainer Kevin Walter <kevin.walter.private@gmail.com>

run zypper addrepo http://download.opensuse.org/repositories/devel:/languages:/python/openSUSE_Tumbleweed/devel:languages:python.repo

run zypper --non-interactive --gpg-auto-import-keys install salt-minion

cmd salt-minion
