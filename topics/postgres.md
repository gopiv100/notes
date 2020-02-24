 # Postgres 
 
 ### Arch Linux installation

Install postgres in Arch Linux

`sudo pacman -S postgresql`

If you have sudo and are in sudoers

`sudo -iu postgres`

Otherwise use **su**

```
su

su -l postgres
```

### Initial Configuration
Initialise the database cluster

`[postgres]$ initdb --locale=en_SG.UTF-8 -E UTF8 -D /var/lib/postgresdata`

You can now start the database server using:

`pg_ctl -D /var/lib/postgres/ -l logfile start`

Create your first database/user
