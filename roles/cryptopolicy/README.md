Role Name
=========

Cryptopolicy

Requirements
------------

Newer versions of RHEL and Fedora have moved to a new combined crypto policy for various daemons like openssh. This role is for setting the policy level.

Role Variables
--------------

cryptopolicy_level - string with policy level, see comments in default vars.
cryptopolicy_reboot - boolean, whether to run the reboot handler


License
-------

BSD

Author Information
------------------

herd-the-cats
