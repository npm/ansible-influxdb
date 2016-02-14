# ansible-influxdb
Set up InfluxDB using Ansible, together with users, databases and grants.

## Usage

### Variables

  * `influxdb_version` - InfluxDB version
  * `influxdb_admin_users` - array of admin users to create
  * `influxdb_users` - array of users to create
  * `influxdb_databases` - array of databases to create
  * `influxdb_grants` - array of grants to create
  * `influxdb_peers` - array of peers to set up
