ansible-serviio-common
========

Ansible role which installs [Serviio](http://serviio.org), a free media server.

Role Variables
--------------


Example Playbook
-------------------------

1) Install serviio

    - hosts: all
      roles:
      - ansible-serviio-common

Dependencies
------------

The Serviio media server has the following dependencies:
- Java 8
- FFmpeg package (incl. libRTMP, libASS, libx264 and libmp3lame) for their OS distributions or, ideally, compile FFmpeg

These dendencies can be installed using the following roles:
- [ansible-openjdk-common](https://github.com/mihaiparv/ansible-openjdk-common)
- [ansible-ffmpeg-common](https://github.com/mihaiparv/ansible-ffmpeg-common)

License
-------

BSD

Author Information
------------------

Parv Mihai