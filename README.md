Klar
=========

Klair it's a clair client. This role downloads the binary from [its github page](https://github.com/optiopay/klar).

Requirements
------------

None.

Role Variables
--------------

* `klar_version`: Klar version. [Default: 1.4.1]
* `architecture`: The binary architecture. The options are `osx-amd64` or `linux-amd64`. [Default: linux-amd64]

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: klar }
```

License
-------

GPL3

Author Information
------------------

alexperez [ EN ] paradigmadigital.com
