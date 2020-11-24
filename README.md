IAAS
====

**WARNING**: I don't actively maintain this role. May be buggy. Consider it as an experimentation rather than a ready to go tool.

This role provider multiple infrastructure deployment and provisioning on multiple platforms/cloud providers. It is based on [Terraform](https://terraform.io) and Ansible templates.

Requirements
------------

This role requires Terraform to be installed. You can set the iaas_tf_install variable to yes to let this role install terraform for you.

Role Variables
--------------

TODO: defaults

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: iaas
      roles:
         - { role: iaas, iaas_tf_install: yes }

License
-------

BSD

Todo
----

- automate terraform init and providers installation [x]
- fix `<driver name='qemu' type='raw'/>` to `<driver name='qemu' type='qcow2'/>` when base image is qcow2

Author Information
------------------

Benoit Petit <bpetit@b0rk.in> (https://bpetit.nce.re)
