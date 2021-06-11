# Wordpress

> Wordpress blog platform using MySQL as database.

## How to access to wordpress

Once the application has been deployed, you will be able to get the endpoint asking for
application information executing:

```
$playground apps info my-wordpress
NAME            STATUS
my-wordpress    APP_OK

COMPONENT    STATUS    SCOPES    TRAITS
mysql-db     OK
wordpress    OK                  wp-ingress, wordpress-replication

COMPONENT    INGRESSES
wordpress    wordpress-<username>.apps.playground.napptive.dev

```

Click to [Ingress](http://wordpress-<username>.apps.playground.napptive.dev) link to access wordpress


## Admin area

You will access your admin dashboard by appending /wp-admin to yor wordpress link: http://wordpress-<username>.apps.playground.napptive.dev/wp-admin
with the following credentials:
User: user
Password: bitnami

## References
* https://wordpress.com/
* https://www.mysql.com/