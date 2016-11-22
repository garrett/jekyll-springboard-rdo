---
title: Network Configuration Overview
authors: rkukura
wiki_title: Network Configuration Overview
wiki_revision_count: 3
wiki_last_updated: 2013-07-25
---

# Network Configuration Overview

Work in progress!

An all-in-one packstack deployment provides some basic default networking functionality for a single-node OpenStack cloud. Instances can communicate with other instances on the same node, they can create connections to the outside world, and floating IPs allow inbound connections to instances from the all-in-one node (but not the outside world). Anything beyond this requires additional configuration specific to the deployment. These pages are intended to provide an overview of the various options available, and how they can be implemented.

## Planning Your Deployment

Planning an OpenStack deployment's network configuration involves a number of decisions.

*   [Choose a networking solution](/networking/networking-solutions/)
*   [Choose type for tenant networks](Tenant Networks)
*   [Plan network interface usage](Network Interfaces)
*   [External connectivity options](/networking/external-connectivity/)
*   [Plugin configuration](Plugin Configuration)
*   [L2 agent configuration](L2 Agent Configuration)
*   [DHCP agent configuration](DHCP Agent Configuration)
*   [L3 agent configuration](L3 Agent Configuration)
*   [Metadata configuration](Metadata Configuration)
*   [Additional services](Addition Network Services)

## Deployment Options

### Packstack Deployment

### Manual Deployment
