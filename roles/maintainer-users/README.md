Role Name
=========

Add / Update / Delete user account (password / ssh keys)

Requirements
------------

add_users setting in vars/main.yml
delete_users setting in vars/main.yml (optional)

Role Variables
--------------

add_users
delete_users

Dependencies
------------

sethostname
settime

Example Playbook
----------------

ansible-playbook -i host setup.yml 

License
-------

BSD

Author Information
------------------

scott.yen@light-morning.com
