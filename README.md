Role Name
=========

Lighthouse


Role Variables
--------------

|name                  | description|
-----------------------------------------------------------
|lighthouse_url        | URL for download lighthouse |

|lighthouse_dir|       | Directory where installed lighthouse |

|lighthouse_nginx_user | User use in nginx|




Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
 
  - name: Install lighthouse
    hosts: lighthouse
    become: true
    roles:
      - lighthouse

License
-------

MIT

Author Information
------------------

Yagudin Timue
