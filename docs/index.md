---
hide:
- navigation
- toc
- tags
---
<h1></h1>
<img src="img/ORB-logo-black@3x.png" alt="Orb" width="500"/>


<iframe align="right" width="918" height="546" src="https://www.youtube.com/embed/XzpSckJzxxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Open source, dynamic edge observability.

[Get Started with Orb](install/){ .md-button .md-button--primary }

<br> <br> <br> <br>
<br> <br> <br> <br>

***

# Why Orb?

## Distributed Deep Network Observability
Orb manages a [fleet](about/#fleet) of **[agents](about/#agent)** deployed across distributed, hybrid infrastructure: *containers*, *VMs*, *servers*, *routers*, and *switches*. 
The agent taps into traffic streams and extracts real-time insights, resulting in light-weight, actionable metrics.

## Streaming Analysis at the Edge
Based on the [pktvisor observability agent](https://pktvisor.dev), **Orb's goal is to push analysis to the edge**, where high-resolution data can be analysed in real time without the need to send raw data to a central location for batch processing. [Current analysis](https://github.com/ns1labs/pktvisor/wiki/Current-Metrics) focuses on L2-L3 Network, DNS, and DHCP with more analyzers in the works.

## Real-time Agent Orchestration
Orb uses Internet of Things (IoT) principles to allow the observability agents to connect out to the Orb central control plane, avoiding firewall problems. Once connected, agents are controlled in real time from the Orb Portal or REST API, orchestrating observability [policies](about/#policies) designed to precisely extract the desired insights. Agents are grouped and addressed based on [tags](about/#agent-group).

## Flexible Integration With Modern Observability Stacks
Orb was built to integrate with modern observability stacks, supporting [Prometheus](https://prometheus.io/) natively and
designed to support arbitrary [sinks](about/#sinks) in the future. Collection and sinking of the metrics from the agents
is included—there is no need to run additional data collection pipelines for Orb metrics.

## Portal and REST API Included
Orb includes a modern, responsive UI for managing *Agents*, *Agent Groups*, *Policies*, and *Sinks*. Orb is API-first, and all platform functionality is available for automation via the [well documented REST API](docs/#working-with-api-docs).

## Open Source, Vendor Neutral, Cloud Native
Orb is free, open source software (FOSS) released under Mozilla Public License (MPL). It's a modern microservices application that can be deployed to any Kubernetes service in private or public cloud. It does not depend on any one vendor to function, thus avoiding vendor lock-in.

***

# Backed by NS1
**Orb** was born at [NS1 Labs](https://ns1.com/labs), where we're committed to making [open-source, dynamic edge observability a reality](https://ns1.com/blog/orb-a-new-paradigm-for-dynamic-edge-observability).

