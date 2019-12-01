freehck.k8s_namespace
=========

Manage k8s namespaces.

Description
-----------

This role just creates or removes kubernetes namespace.

Role Variables
--------------

`k8s_namespace_name`: namespace name, mandatory parameter

`k8s_namespace_state`: namespace state, `present`/`absent`, default `present`

Example
-------

    - role: freehck.k8s_namespace
      k8s_namespace_name: "my-namespace"
      k8s_namespace_state: "present"

Install
-------

This role can be installed from [Ansible Galaxy](https://galaxy.ansible.com/):

`ansible-galaxy install freehck.k8s_namespace`

License
-------

MIT

Author Information
------------------

Dmitrii Kashin, <freehck@freehck.ru>

