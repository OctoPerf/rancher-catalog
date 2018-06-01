# OctoPerf Enterprise-Edition

## 9.0.0 (1st June 2018)

**Major change**: As of 9.0.0 and above, [Rancher](https://rancher.com) is not used for load generators anymore. Please refer to documentation for more information.

## Docker Images

- `octoperf/docker-agent:9.0.0`: unified load generator and monitoring agent,
- `octoperf/enterprise-edition:9.0.0`: backend server,
- `octoperf/enterprise-ui:9.0.0`: frontend server,
- `octoperf/enterprise-documentation:9.0.0`: documentation server,
- `docker.elastic.co/elasticsearch/elasticsearch-oss:6.2.4`: database.

### Bug Fixes

- Importing Firefox 60 and above HAR could fail (#614)
- JMX Import was not properly importing timers (#619)
- Increase Extra Memory Percent to improve small machines usage (#620)

### Enhancements

- Rancher is no longer required to run OctoPerf EE (#609)
- Scenario and Results views feature a World Map
