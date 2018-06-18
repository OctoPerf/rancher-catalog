# OctoPerf Enterprise-Edition

## 9.0.1 (18th June 2018)

**Docker Images**

- `octoperf/docker-agent:9.0.0`: unified load generator and monitoring agent,
- `octoperf/enterprise-edition:9.0.1`: backend server,
- `octoperf/enterprise-ui:9.0.1`: frontend server,
- `octoperf/enterprise-documentation:9.0.1`: documentation server,
- `docker.elastic.co/elasticsearch/elasticsearch-oss:6.2.4`: database.

**Bug Fixes**

- JMX: Server is imported as https with port 80 (#646)
- `ServerAgentService.isIdle` should ignore Exited containers (#643)
- Stale Tests are not finished after xx minutes (#642)
- Windows process monitor 404 (#639)
- JMX Import Issue with Test Fragments (#633)
- Do not import headers starting with `:` (#630)
- JMeter script tries to send agent logs (#629)
- Disabled Agent Seen as Down (#628)
- Agent Randomly appears as disconnected when high-availability is enabled (#627)

**Enhancements**

- Upgrade various external libraries (#641)
- Improve Test Initialization logs (#632)
