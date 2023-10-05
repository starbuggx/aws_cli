ECGALAXY aws_cli role
=====================

This role installs the latest version of the AWS CLI.

Optionally the role can also install the [Session Manager plugin](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html).

Requirements
------------

- The `gpg` command, which can be provided by the `ecgalaxy.common_packages` role.

Role Variables
--------------

For the list of all the available variables check the files under `defaults/` and `vars/`.

Dependencies
------------

- Optional: ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.aws_cli

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
