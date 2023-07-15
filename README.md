Role Name
=========

Install GNOME keyring for Debian container on ChromeOS.
You can restrict the role to run only on ChromeOS with the check `when: "'ChromiumOS' in ansible_facts.system_vendor"`

Requirements
------------

...

Role Variables
--------------

...

Dependencies
------------

...

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      tasks:
      - name: Install Keyring on chromeos
        ansible.builtin.include_role:
          name: kowalski7cc.chromeos_keyring
        when: "'ChromiumOS' in ansible_facts.system_vendor"

License
-------

MIT

Author Information
------------------

Kowalski Dragon (kowalski7cc)