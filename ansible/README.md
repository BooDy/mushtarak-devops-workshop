PHP 7.1, MySQL, NginX, And Drupal 8.5.6 playbook.
===

Run:
```
$ ansible-playbook lamp-playbook.yml  --extra-vars "site_name=<site name> site_domain=<site domain name>"
```

The playbook will prepare a Drupal 8.5.6 & nginx installation on an ubuntu 16.04LTS machine.

You'll find your Drupal installation ready at /var/www/<site name>
