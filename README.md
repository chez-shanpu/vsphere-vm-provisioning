## Requirements
- ansible
- python >= 2.6
- PyVmomi

## Usage
1. Install dependencies
```bash
$ pip install pyvmomi
```

2. exec

```bash
# edit variable file
$ vi roles/common/vars/main.yaml

# exec
$ ansible-playbook provision.yaml 
```
