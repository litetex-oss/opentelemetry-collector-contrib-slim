# opentelemetry-collector-contrib-slim

A slim fork of [opentelemetry-collector-contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib)

## Why?

Some parts of the original distribution contain not needed bloat that is removed here.

## What is removed?

* receiver
  * prometheusreceiver
    * Removed Kubernetes Integration (-30MB)

## How?
The updating logic can be found in the [sidecar repo](https://github.com/litetex-oss/opentelemetry-collector-contrib-manager).
