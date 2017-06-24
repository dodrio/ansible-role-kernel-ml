# kernel-ml

[![Build Status](https://travis-ci.org/m31271n/ansible-role-kernel-ml.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-kernel-ml)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.kernel--ml-blue.svg)](https://galaxy.ansible.com/m31271n/kernel-ml)

Ansible role that setups kernel-ml for EL.

## Requirements

None.

## Role Variables

+ `kernel_ml_version`: `4.11.6`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.kernel-ml
```

## Thanks

+ [kernel-ml](http://elrepo.org/tiki/kernel-ml)
+ [How to Install or Upgrade to Latest Kernel Version in CentOS 7](https://www.tecmint.com/install-upgrade-kernel-version-in-centos-7/)

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
