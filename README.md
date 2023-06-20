# Ansible Role: unbound

[![Lint](https://github.com/dcjulian29/ansible-role-unbound/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-unbound/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-unbound.svg)](https://github.com/dcjulian29/ansible-role-unbound/issues)

This an Ansible role to provision the Unbound DNS Server

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.unbound
  src: https://github.com/dcjulian29/ansible-role-unbound.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
