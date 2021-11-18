ECGALAXY aws_cli
=======================

This role installs the latest version of the AWS CLI.
Optionally the role can also install the [Session Manager plugin](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html).

Requirements
------------

None.

Role Variables
--------------

For the list of all the available variables check the files under `defaults/` and `vars/`.

Dependencies
------------

- ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.common_packages
        - ecgalaxy.aws_cli

License
-------

EUPL-1.2

Author Information
------------------

ECGALAXY team.
