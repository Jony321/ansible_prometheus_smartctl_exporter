## AndrewGodGivens /ansible_prometheus_ipmi_exporter 
============

An Ansible role which installs and configures Prometheus ipmi_exporter on Linux

============

## Requirements

Ansible 2.8+

============

## Role Variables

You can see all vars in defaults/main.yml vars file.

## Example Playbook

```yaml
- name: Ensure prometheus_ipmi_exporter
  hosts: prometheus_ipmi_exporters
  remote_user: root

  roles:
    - prometheus_ipmi_exporter
  
```
