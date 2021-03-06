---
layout: page
title: Istio Adapter
name: Istio
version: v1.3
port: 10000/tcp
project_status: stable
image: /docs/assets/img/service-meshes/istio.svg
---
# Meshery Adapter for {{ page.name }}

| Adapter Status |
| :------------: |
| [{{ page.project_status }}]({{ page.github_link }})|

## Sample Applications

The Meshery adapter for ({{ page.title }}) includes a handful of sample applications. Use Meshery to deploy any of these sample applications.

## Features
1. Lifecycle management of Istio
1. Lifecycle management of sample applications
1. Configuration best practices
1. Custom service mesh configuration

1. Prometheus and Grafana connection

The Meshery adapter for Istio will connect to Istio's Prometheus and Grafana instances running in the control plane (typically found in the `istio-system` namespace).