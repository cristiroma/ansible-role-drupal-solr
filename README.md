Role Name
=========

Install Apache Solr as system service with support for Drupal search_api_solr module

Requirements
------------

None.

Role Variables
--------------

```
drupal_solr4_home: "/opt/drupal-solr"
drupal_solr4_cores: [ 'test', 'prod' ]
```

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: cristiroma.drupal-solr, x: 42 }
```

License
-------

BSD

Author Information
------------------

@cristiroma
