# Ansible Playbooks

## 

## Troubleshooting

** I got the message *Missing python-apt* **

Try again using `ansible_python_interpreter` argument:

```
ansible my-playbook.yml -e ansible_python_interpreter=/usr/bin/python --check
```

** I got the error *SUDO: a password is required* **

You need to run the command with `sudo`
