Bene Role
=========

This Role Include

- Blacklist domain or  email on the Zimbra server  tags: blacklist  tags: remove
- Whitelist domain or email on the Zimbra Server   tags: whitelist
- DNS Setup and Installation tags:dns



Role Variables
--------------
# For whitelist and black List 
- domain:    The domain desire to block or whitelist
- email:     The email desire to block or whitelist

# For DNS
No variables are need it
Tags: dns


Dependencies
------------
No Dependencies at this moment need it


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      gather_facts: no
      roles: 
        - role: blacklist
          tags: blacklist
        - role: whitelist
          tags: whitelist
        - role: remove_blacklist
          tags: remove
        - role: dns
          tags: dns

License
-------

Property of IAG

Author Information
------------------

Mario Gamboa Pang
mario.gamboapang@iag.com.au
