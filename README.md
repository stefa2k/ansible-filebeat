# ansible-filebeat

## Variables
### Playbook
Name | Description | Mandatory
-----|-------------|----------
filebeat_yml | path to `filebeat.yml` | n
filebeat_system_yml | path to `system.yml` | n
filebeat_postgresql_yml | path to `postgresql.yml` | n
filebeat_connections | list of beats listeners (e. g. logstash) | n (default `localhost:5044`)
filebeat_version | version to install | n

### Hostvars
Name | Description | Mandatory
-----|-------------|----------
filebeat_system | enable `system` module (`yes`/`no`) | y
filebeat_postgresql | enable `postgresql` module (`yes`/`no`) | y
