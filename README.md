[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![CI](https://github.com/grycap/ansible-role-vnc/workflows/CI/badge.svg)](https://github.com/grycap/ansible-role-vnc/actions?query=workflow%3ACI)

# VNC + noVNC Role

This ansible role installs the VNC + noVNC software.

## Example Playbook

This an example of how to install this role:

    - hosts: server
      roles:
      - { role: 'grycap.vnc', vnc_password: 'some_pass' }

# Contributing to the role

In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.
Thanks
