# ansible-vmware

Role to create/delete/manage VMware objects. 
By default, it installs a virtual machine. 

## Requirements

Ansible VMware modules are written on top of pyVmomi. pyVmomi is the Python SDK for the VMware vSphere API that allows user to manage ESX, ESXi, and vCenter infrastructure. 

You can install pyVmomi using pip:

```
sudo pip install pyvmomi
```

## Role Variables

### Default variables

TODO

```
```

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: ansible-vmware
```

## License

BSD
