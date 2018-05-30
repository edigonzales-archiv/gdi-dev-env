# gdi-dev-env

Rollen erstellen:
```
sudo -u postgres psql -d postgres -f create_roles.sql
```

Pub-DB-Dump einspielen:
```
pg_restore --role=postgres --exit-on-error -C -d postgres pub.dmp
```