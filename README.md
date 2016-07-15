Role Name
=========

Collection of docker utils that rely on the 'docker' command

Requirements
------------

Requires Ansible 2.0 or higher.

Role Variables
--------------

Depends on the specific command being run.
Include
   * `docker_name`
   * `docker_dockerfile`
   * `docker_build_args`
   * `docker_base_dir`
   * `docker_domain_name`
   * `docker_volume_args`
   * `paths.docker` (path do docker command. probably `/usr/bin/docker`



Dependencies
------------

Probably docker :-)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: foo
      roles:
         - role: dieswaytoofast.docker_utils

License
-------

BSD

Author Information
------------------

Mahesh Paolini-Subramanya (@dieswaytoofast)
