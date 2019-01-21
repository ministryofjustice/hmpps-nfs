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
# For the nfs client
is_nfs_client:boolean #default false
nfs_mount_dir: /path/to/mount #default /data
nfs_mount_owner: owner of mounted dir #default hmpps_sys_user
nfs_server_name: dns prefix of nfs server #default nfs
nfs_server_dir: /server/path #default /data
```
