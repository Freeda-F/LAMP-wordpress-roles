Role Name
=========

In wordpress role, we will downloading the latest wordpress, extracting its contents and setting up the custom wp-config.php file to complete its installation

Role Variables
--------------

The variables used are :
```
domain_name: "wordpress.freeda-francis.tech"  #-------domain name-------#
wp_url: "https://wordpress.org/latest.tar.gz"  #-------WordPress download URL-------#
```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: amazon
      roles:
         - wordpress

