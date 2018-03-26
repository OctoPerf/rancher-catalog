# OctoPerf Enterprise-Edition

## 8.2.0 (26th March 2018)

### Enhancements

- Design: Correlation rules frameworks update (#590)
- Design: Virtual user validation now display 4XX+ on record as errors (#270)
- Design: Copy/ paste refactor (#558)
- Design: Autocompletion in server configuration (#562)
- Design: Pin Validate Virtual User panel if one is running when opening a VU (#570)
- Design: Sanity Check displays an error on query parameter with empty name and value (#550)
- Monitoring: Support Prometheus monitoring (#500)
- Runtime: Reduce default memory used by JMeter to download large files (#581)
- Runtime: Custom load policy (#556 and #587)
- Analysis: Add 99 percentile to result table (#566)
- UI: Documentation lazy loading (#557)
- UI: Update fontawesome to latest version (#547)

## Bug Fixes

- JMX Import: Regexp Extractor with body unescaped should be imported as extractor on body (#580)
- Design: PUT request contains invalid chars in body (#582)
- Design: Selenium webdriver request tab not showing the URL accessed (#574)
- Design: PUT request body must be raw (Name/Value post parameters are ignored by JMeter in PUT / PATCH requests) (#573)
- Design: Https Server Port is 80 instead of 443 on JMX Import (#560)
- Design: Search and replace hangs (#565)
- Runtime: URL Parameter not encoded at replay by JMeter (#569)
- Runtime: M5.xlarge not available in all zones (#555)
- Runtime: JMX: If Controller is not properly configured (#561)
- Runtime: ThinktimeText is causing issues in JMX with DelayAction (#559)
- Analysis: Sent bytes always shows 0 in summary with containers (#567)
- Analysis: Result table sort on numeric values (#564)
