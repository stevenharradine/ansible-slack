# ansible-slack

Slack is a platform for team communication

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Tunables
--------
* `slack_dry_run:` (boolean) - should the slack notification fire?
* `slack_domain:` (string) - the slack domain to notify
* `slack_channel:` (string) - the slack channel to notify

Dependencies
------------
* none

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.slack

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* Steven Harradine
