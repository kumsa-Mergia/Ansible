# Ansible Roles: Usage in Playbooks

This document focuses on how to effectively utilize Ansible Roles within your playbooks.

## Basic Usage

The simplest way to include a role in a playbook is by listing it under the `roles` key:

```yaml
---
- hosts: all
  become: true

  roles:
    - { role: 'role_name' }
