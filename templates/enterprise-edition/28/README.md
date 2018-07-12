# OctoPerf Enterprise-Edition

## 9.2.0 (12th July 2018)

**Docker Images**

- `octoperf/docker-agent:9.0.0`
- `octoperf/enterprise-edition:9.2.0`
- `octoperf/enterprise-ui:9.2.0`
- `octoperf/enterprise-documentation:9.2.0`
- `docker.elastic.co/elasticsearch/elasticsearch-oss:6.3.1`
- `octoperf/jmeter-standard:9.0.1`
- `octoperf/jmeter-webdriver:9.0.1`

**Bug Fixes**

- CSV variables used in WebDriver parameters aren't exported in JMX (#680)
- CSV variables used in WebDriver scripts aren't exported in JMX (#679)
- files named with Uppercase chars could not be found during test (#674)
- JMX Import: Scripts at test plan level are not imported (#663)

**Enhancements**

- Upgrade to Elasticsearch `6.3.1` (#678)
- Add support for WebDriver *parameters* field (#675)
- Virtual user validation is updating live during the run (#672)
- Increase maximum settable memory by profile to `128MB` (#667)
- AWS Provider: ability to configure memory, shutdown policy and cloud instances (#666)
- Cloud Providers: change zones from map to list to better support AWS Accounts with lots of VPCs (#662)
