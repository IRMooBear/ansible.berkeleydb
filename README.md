Ansible BerkeleyDB
=========

Download, compile and install Berkeley DB v5.1

Requirements
------------

None

Role Variables
--------------
The BDB version, default to 5.1.29

    bdb_version: 5.1.29
    
MD5 checksum as provided by upstream at Oracle

    bdb_checksum: md5:a94ea755ab695bc04f82b94d2e24a1ef

Prefix for installation, default is standalone not shared

    bdb_prefix: /usr/local/BerkeleyDB.5.1

Turn on --disable-share flag   
 
    bdb_share: no
    
Turn on --with-cxx flag 
   
    bdb_cxx: yes
    
Turn on --with-pic flag
    
    bdb_pic: yes

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: irmoobear.berkeleydb }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
