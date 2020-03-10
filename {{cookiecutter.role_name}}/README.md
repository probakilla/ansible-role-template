# {{cookiecutter.role_name|upper}}

{{cookiecutter.description}}

## Role Variables

Stored in defaults folder

```
```

## Howto use this role

This role needs to be included in a playbook
You can install it with *Galaxy*

```bash
ansible-galaxy install -r requirements.yml
```

requirements.yml
```
- src: probakilla.{{cookiecutter.short_name}}
```

# Requirements

- Ansible 2.4+

# Example playbook using this role

You can include this role in an ansible playbook file like this:

```
- hosts: all
  roles:
    - role: probakilla.{{cookiecutter.short_name}}
      tags: mytags
```
