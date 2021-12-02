# Ansible Playbooks

## 

## Troubleshooting

**Message *Missing python-apt***

Try again using `ansible_python_interpreter` argument:

```
ansible my-playbook.yml -e ansible_python_interpreter=/usr/bin/python --check
```

**Error *SUDO: a password is required***

You need to run the command with `sudo`
