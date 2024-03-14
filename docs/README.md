# ansible-vslurm-admintools Documentation

## Configuration

## Playbooks

### add_user.yaml

Creates user accounts on the cluster with home directories in the mounted NFS directory.

Call it as follows:

```bash
ansible-playbook add_user.yaml --extra-vars "username=slurm-user-01 uid=301"
```
