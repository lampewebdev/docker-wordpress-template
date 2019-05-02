# How to run wordpress with docker

## Make plugins installation work

Add this to `wp-config.php` to install plugins without ftp access

```PHP
/* Make WordPress install plugins directly */
define('FS_METHOD', 'direct');
```
