ECGALAXY google_chrome
=======================

This Ansible role installs Google Chrome.

Requirements
------------

None.

Role Variables
--------------

- `chrome_package`: google-chrome-stable
- `chrome_gpg_key_url`: https://dl-ssl.google.com/linux/linux_signing_key.pub

Redhat:

- `chrome_repo_url`: http://dl.google.com/linux/chrome/rpm/stable/$basearch

Debian:

- `chrome_repo_url`: http://dl.google.com/linux/chrome/deb/

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.google_chrome

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
