# cloud deployment

This collection of ansible playbooks creates my
* `nextcloud` instance
* ispmail instance (under development)
* my wordpress instance (under development)

Maybe it can be of use to someone else.

## config

no excessive documentation here. as for the `/host_vars/*/secrets.yml`, it could look like this:
```yaml
---
mysql_root_pw: "some root password"

hetzer_dns_api_token: "some api token"

nextcloud_db_user: nextcloud
nextcloud_db_schema: nextcloud
nextcloud_db_pass: "some local db password"
nextcloud_admin_user: admin
nextcloud_admin_pass: "some admin password"

nextcloud_bucket_name: my-bucket
nextcloud_bucket_key: 12345668
nextcloud_bucket_secret: feCajsaphItkoanessAvsidAfInerWiOtVank}Ot
nextcloud_bucket_host: s3.eu-central-1.wasabisys.com
nextcloud_bucket_region: eu-central-1
```
