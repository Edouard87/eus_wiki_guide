# User Accounts

Ensure you are in the `/srv/www/wiki` directory before running any of these commands.

```bash
$ php maintenance/run.php createAndPromote username "password" --sysop
```

This will create a user with all the required permissions and promote them to a system admin.

