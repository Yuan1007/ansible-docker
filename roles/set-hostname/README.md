Sethostname
=========

Set hostname by ansible_set_hostname variable

Requirements
------------

none

Role Variables
--------------

ansible_set_hostname=hostname

Dependencies
------------

none

Example Playbook
----------------

## Notice 
- if the ansible_set_hostname not set, will do nothing by defulat

declare host with ansible_set_hostname in host file

host example
```
[all:vars]
...

[dev-hosts]
10.1.169.159 ansible_set_hostname=some-host
10.1.169.159 ansible_set_hostname=some-host2


```

ansible-playbook -i host setup.yml

License
-------

BSD

Author Information
------------------

scott.yen@light-morning.com
