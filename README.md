Openshift Applier Replace
=========================

A pre/post role for [Openshift Applier](https://github.com/redhat-cop/openshift-applier) for replacing string(s) in file before (or after) being applied to Openshift.
The role is using the Ansible [replace](https://docs.ansible.com/ansible/latest/modules/replace_module.html) module.

Requirements
------------

[Openshift Applier](https://github.com/redhat-cop/openshift-applier)

Role Variables
--------------

| Variable name | Description                                                                                                        |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| file          | A file name or file glob for which to replace a string(s)                                                                      |
| regexp        | A regular expression to match (see [replace](https://docs.ansible.com/ansible/latest/modules/replace_module.html))             |
| replace       | The string that will replace the `regexp` (see [replace](https://docs.ansible.com/ansible/latest/modules/replace_module.html)) |

Dependencies
------------

None

License
-------

Apache

Author Information
------------------

Petter Abrahamsson <petter@jebus.nu>
