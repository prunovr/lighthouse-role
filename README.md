# Ansible-Lighthouse role

![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/prunovr/lighthouse-role)

Simple lighthouse deploy and management role.

## Requirements

---

### Ansible

It was tested on the following versions:

* 2.12

### Operating systems

* Ubuntu 20.04

## Role Variables

---

You can specify git url.

```yaml
  lighthouse_git_url: "https://github.com/VKCOM/lighthouse.git"  
```

You can specify location dir for lighthouse.

```yaml
  lighthouse_location_dir: "/usr/local/lib/lighthouse"
```

## Dependencies

To work this role, the presence of the established Clikhouse server

## Example Playbook

---

Just include this role in your list. For example:

```yaml
  - host: all
    roles:
      - lighthouse-role
```

## License

---

MIT
