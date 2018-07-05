# OctoPerf Enterprise-Edition

## 9.1.0 (2nd July 2018)

**Docker Images**

- octoperf/docker-agent:9.0.0
- octoperf/enterprise-edition:9.1.0
- octoperf/enterprise-ui:9.1.0
- octoperf/enterprise-documentation:9.1.0
- docker.elastic.co/elasticsearch/elasticsearch-oss:6.3.0
- octoperf/jmeter-standard:9.0.1
- octoperf/jmeter-webdriver:9.0.1

**Bug Fixes**

- Only Private docker providers can be created (#657)
- Fix licences panel in UI (#654)
- Properly import JMX when Authentication Manager is empty (#651)

**Enhancements**

- Improve Guided Tour (#653)
- Automatically detect and downloading JMeter Plugins when importing JMX (#652)
- Upgrade various internal libraries (#647 and #648)
- Upgrade to Elasticsearch 6.3.0 (#644)
- Cloud Providers: Support AWS Elastic IPs and DigitalOcean Floating IPs (#635)
