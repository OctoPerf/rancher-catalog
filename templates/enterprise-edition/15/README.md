# OctoPerf Enterprise-Edition

OctoPerf provides a complete **load testing service** for web and mobile applications. Simulate thousands of users browsing through your application.

## 7.4.0 (17th November 2017)

### Enhancements

- OctoPerf SLA : Service Level Agreement profiles are configurable in the Design / Monitoring and visible in the test reports.
- Load Injector monitoring : added threshold alarms when CPU usage is over 80%.
- HTTP Servers : Connection and Response Timeouts are now configurable per server.
- Correlation Rules Frameworks : updated the SAML and .Net frameworks.
- Virtual User Cleanup : when removing SLA profiles or HTTP Servers, empty containers are also removed.
- Report Trends : the analysis page show a trend graph if showing the response time and hits/errors counts for all selected reports.
- Frontend optimization : the design page and the search & replace for big Virtual Users (hundreds of actions) is now faster.
- HTTP headers auto-completion : common HTTP request actions header names are now suggested during edition.
- Test report summary : to quickly navigate in the report, a summary is displayed on the right.
- ElasticSearch upgrade to version 5.6.4.

### Bug Fixes

- Correlation rules injections 'with name' field is left to an empty string when it is cleared.
- The displayed number of items currently in the trash is wrong after an action is dropped back into the Virtual User.
- JMX import may throw a ClassCastException.

