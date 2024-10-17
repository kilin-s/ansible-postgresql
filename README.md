# Postgresql


## Examples

set vars

```yaml

psql_max_connections: 100


psql_users:
  - name: user1
    password: pass1
  - name: user2
    password: pass2


psql_dbs:
  - name: db1
    encoding: UTF-8
    lc_collate: en_US.UTF-8
    lc_ctype: en_US.UTF-8
    owner: user1
```