Role Name
=========

This is a role for installing and configuring LAMP server i.e Apache, MySQL and PHP.

Role Variables
--------------

The varuables used are :
```
mariadbroot_pw: "mysqlpass123" #-------database root password-------#
db_name: "wordpress"  #-------Wordpress database name-------#
db_user: "wordpress"  #-------WordPress username-------#
db_password: "wordpress"  #-------WordPress db password-------#
httpd_port: 80  #-------port for apache-------#
httpd_user: "apache" #-------apache user-------#
httpd_group: "apache"  #-------apache group-------#
domain_name: "wordpress.freeda-francis.tech"  #-------domain name-------#
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: amazon
      roles:
         - lamp
