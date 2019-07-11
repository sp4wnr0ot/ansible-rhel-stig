# Ansible Playbook - run-oscap
This is a playbook ansible to demo openscap execution, security check
Audit, Fix and be Merry!

http://www.open-scap.org/

# Requiriments
Be sure all those packages already installed

openscap scap-security openscap-utils openscap-scanner
In RHEL systems like 

```
$ sudo yum install openscap scap-security openscap-utils openscap-scanner -y
```

# To execute

```
$ sudo ansible-playbook --limit all -v run-oscap.yml
```
