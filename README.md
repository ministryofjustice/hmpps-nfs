Role Name
=========

Role to install nfs server and client components


Role Variables
--------------

```yaml
# For the nfs server
is_nfs_server: boolean #default false
nfs_share: /path/to/export
allowed_ip_ranges: list of cidr blocks
```