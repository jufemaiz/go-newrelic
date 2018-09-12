# go-newrelic-api

[![Build Status](https://travis-ci.org/paultyng/go-newrelic.svg)][Travis]
[![Go Report Card](https://goreportcard.com/badge/github.com/paultyng/go-newrelic)][Go Report Card]
[![GoDoc](http://img.shields.io/badge/godoc-reference-blue.svg)][Docs]

This is a Go library that provides access to the the [New Relic][New Relic]
[REST API][New Relic REST API].

## Getting Started

You'll need to get an API Key (note, some commands require an Administration API
Key).

## API Capabilities

### Alerts

- [Alert Policies][API Alert Policies]
- Conditions
  - [APM, Browser, Mobile][API Alert Conditions]
  - [External Services][API Alert Conditions External Services]
  - [Infrastructure][API Alert Conditions Infrastructure] (?)
  - [NRQL][API Alert Conditions NRQL]
  - [Plugins][API Alert Conditions Plugins]
  - [Synthetics][API Alert Conditions Synthetics]
- [Events][API Alerts Events]
- [Notification Channels][API Alert Notification Channels]

### Applications

- [Applications][API Applications]
- [Application Hosts][API Application Hosts]
- [Application Instances][API Application Instances]
- [Application Deployments][API Application Deployments]
- [Mobile Applications][API Mobile Applications]
- [Key Transactions][API Key Transactions]

### Servers

- [Servers][API Servers]

### Users

- [Users][API Users]


## Development

---

[API Alert Conditions]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#conditions
[API Alert Conditions Infrastructure]: #
[API Alert Conditions NRQL]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#conditions-nrql
[API Alert Conditions External Services]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#ext-services-conditions
[API Alert Conditions Synthetics]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#synthetics-conditions
[API Alert Conditions Plugins]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#plugins-conditions
[API Alert Notification Channels]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#channels
[API Alert Policies]: https://docs.newrelic.com/docs/alerts/rest-api-alerts/new-relic-alerts-rest-api/rest-api-calls-new-relic-alerts#policies
[Docs]: http://godoc.org/github.com/paultyng/go-newrelic
[Go Report Card]: https://goreportcard.com/report/github.com/paultyng/go-newrelic
[New Relic]: http://www.newrelic.com
[New Relic REST API]: https://docs.newrelic.com/docs/apis/rest-api-v2
[Travis]: https://travis-ci.org/paultyng/go-newrelic
