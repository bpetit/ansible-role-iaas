IAAS
====

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

- automate terraform init and providers installation

Author Information
------------------

Benoit Petit <bpetit@b0rk.in> (https://arawbase.com)
