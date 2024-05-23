# ansible-vslurm-admintools Documentation

## Configuration

## Playbooks

### useradd.yaml

Creates user accounts on the cluster with home directories in the mounted NFS directory.

Call it as follows:

```bash
ansible-playbook useradd.yaml --extra-vars "username=slurm-user-01 uid=5001"
```

### userdel.yaml

Removes a user account from the whole cluster.

Call it as follows:

```bash
ansible-playbook userdel.yaml --extra-vars "username=slurm-user-01 uid=5001"
```
