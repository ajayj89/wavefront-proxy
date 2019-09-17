# Wavefront Java Top-Level Project [![Build Status](https://travis-ci.org/wavefrontHQ/wavefront-proxy.svg?branch=master)](https://travis-ci.org/wavefrontHQ/wavefront-proxy)

[Wavefront](https://docs.wavefront.com/) is a high-performance streaming analytics platform for monitoring and optimizing your environment and applications.

This repository contains several independent Java projects for sending metrics to Wavefront.

## Requirements
  * Java >= 1.8
  * Maven

## Overview
  * dropwizard-metrics: Wavefront reporter for [DropWizard Metrics](https://metrics.dropwizard.io).
    * This project is now obsolete. Please refer to the new [Wavefront Level 2 Dropwizard Metrics SDK](https://github.com/wavefrontHQ/wavefront-dropwizard-metrics-sdk-java)
  * java-client: Libraries for sending metrics to Wavefront via proxy or direct ingestion.
    * This project is now obsolete. Please refer to the new [Wavefront Level 1 Java SDK](https://github.com/wavefrontHQ/wavefront-sdk-java)
  * java-lib: Common set of Wavefront libraries used by the other java projects.
  * pkg: Build and runtime packaging for the Wavefront proxy.
  * proxy: [Wavefront Proxy](https://docs.wavefront.com/proxies.html) source code.
  * yammer-metrics: Wavefront reporter for Yammer Metrics (predecessor to DropWizard metrics).
  * examples: Sample code leveraging the libraries in this repository

  Refer the documentation under each project for further details.

## To start developing

```
$ git clone https://github.com/wavefronthq/wavefront-proxy ${directory}
$ cd ${directory}
$ mvn clean install -DskipTests
```

## Contributing
Public contributions are always welcome. Please feel free to report issues or submit pull requests.
