ECGALAXY google_chrome
=======================

This role installs Google Chrome.

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
        - google_chrome

License
-------

EUPL-1.2

Author Information
------------------

ECGALAXY team.
