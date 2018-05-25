# OctoPerf Enterprise-Edition

## 9.0.0-rc1 (25th May 2018)

**Major change**: As of 9.0.0 and above, [Rancher](https://rancher.com) is not required anymore.

### Docker Images

- `octoperf/enterprise-edition:9.0.0-rc1`: backend server,
- `octoperf/enterprise-ui:9.0.0-rc1`: frontend server,
- `octoperf/enterprise-documentation:9.0.0-rc1`: documentation server,
- `docker.elastic.co/elasticsearch/elasticsearch-oss:6.2.4`: database.

### Bug Fixes

- Importing Firefox 60 and above HAR could fail (#614)

### Enhancements

- Rancher is no longer required to run OctoPerf EE (#609)
- Scenario and Results views feature a World Map
