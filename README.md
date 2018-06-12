# linux-setup

Ansible scripts to help me set up my personal linux set up, targeting:

* Ubuntu 18.04
* Fedora 28

## Prereqs
As these are ansible scripts, a necessary component is ansible. Note that this script assumes the user
will be running Gnome as their desktop environment. Most of the playbook should work regardless of whether it's gnome, kde, or something else, but obviously non-gnome components will not work when the environment is not gnome.

* Install:
    * ansible
* Run as:
    * yourself (i.e. the user you want to have specific user settings)

### Notes for Fedora

* Install:
    * python2-dnf

### Pre-reqs for Ubuntu

* Install:
    * python-apt

## Running

Simply run `ansible-playbook master-playbook.yml --ask-become-pass` to start the process. Note: this will prompt for the sudo password
