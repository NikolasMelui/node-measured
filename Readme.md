# Measured

Node libraries for measuring and reporting application-level metrics.

Measured is heavily inspired by Coda Hale, Yammer Inc's [Dropwizard Metrics Libraries](https://github.com/dropwizard/metrics)

[![Build Status](https://secure.travis-ci.org/yaorg/node-measured.png?branch=master)](http://travis-ci.org/yaorg/node-measured) [![Coverage Status](https://coveralls.io/repos/github/yaorg/node-measured/badge.svg?branch=master)](https://coveralls.io/github/yaorg/node-measured?branch=master)

## Available packages

### [Measured Core](packages/measured-core)

**The core measured library that has the Metric interfaces and implementations.**

[![npm](https://img.shields.io/npm/v/measured-core.svg)](https://www.npmjs.com/package/measured-core) [![downloads](https://img.shields.io/npm/dm/measured-core.svg)](https://www.npmjs.com/package/measured-core)

### [Measured Reporting](packages/measured-reporting)

**The registry and reporting library that has the classes needed to create a dimension aware, self reporting metrics registry.**

[![npm](https://img.shields.io/npm/v/measured-reporting.svg)](https://www.npmjs.com/package/measured-reporting) [![downloads](https://img.shields.io/npm/dm/measured-reporting.svg)](https://www.npmjs.com/package/measured-reporting)

### [Measured Node Metrics](packages/measured-node-metrics)

**Various metrics generators and http framework middlewares that can be used with a self reporting metrics registry to easily instrument metrics for a node app.**

[![npm](https://img.shields.io/npm/v/measured-node-metrics.svg)](https://www.npmjs.com/package/measured-node-metrics) [![downloads](https://img.shields.io/npm/dm/measured-node-metrics.svg)](https://www.npmjs.com/package/measured-node-metrics)

### [Measured SignalFx Reporter](packages/measured-signalfx-reporter)

**A reporter that can be used with measured-reporting to send metrics to [SignalFx](https://signalfx.com/).**

[![npm](https://img.shields.io/npm/v/measured-signalfx-reporter.svg)](https://www.npmjs.com/package/measured-signalfx-reporter) [![downloads](https://img.shields.io/npm/dm/measured-signalfx-reporter.svg)](https://www.npmjs.com/package/measured-signalfx-reporter)

### Measured Datadog reporter

**Not implemented, community contribution wanted.**

### Measured Graphite reporter

**Not implemented, community contribution wanted.**


## Development and Contributing

See [Development and Contributing](https://github.com/yaorg/node-measured/blob/master/CONTRIBUTING.md)

## License

This project Measured and all of its modules are licensed under the [MIT license](https://github.com/yaorg/node-measured/blob/master/LICENSE).
