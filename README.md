# Ansible Role: atom

Ansible role for installing Atom text editor.

[![Build Status](https://www.travis-ci.org/PyratLabs/ansible-role-atom.svg?branch=master)](https://www.travis-ci.org/PyratLabs/ansible-role-atom)

## Requirements

This role has been tested on Ansible 2.7.0+ against the following Linux Distributions:

  - CentOS 8
  - CentOS 7
  - Debian 10
  - SUSE/openSUSE 15.0
  - Ubuntu 18.04 LTS

## Disclaimer

If you have any problems please create a GitHub issue, I maintain this role in
my spare time so I cannot promise a speedy fix delivery.

## Dependencies

No dependencies on other roles.

## Example Playbook

Example playbook for installing the latest Atom Editor version globally:

```yaml
---
- hosts: workstation
  become: true
  roles:
    - role: xanmanning.atom
```

## License

[BSD 3-clause](LICENSE.txt)

## Author Information

[Xan Manning](https://xanmanning.co.uk/)
