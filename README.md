# Overview

This repo contains various connectors built for the open source project [Kyma][1].

These connectors enable extending the application with Kyma by:

* Enabling delivery the webhooks/events from the application to Kyma
* Enabling serverless from Kyma to make API calls.

The connectors are based on the [Helm Broker add-ons](https://kyma-project.io/docs/components/helm-broker/) concept.

## Installation

Create a new `Add-Ons Configuration` in Kyma and provide the Git URL `git::https://github.com/abbi-gaurav/kyma-connectors.git//addons/index.yaml`.

## Full list of connectors

* [Github connector](./addons/github-connector-0.0.1)

[1]: https://kyma-project.io