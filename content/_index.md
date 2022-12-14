---
date: 2000-01-01T00:00:00+00:00
title: Drone Autoscaler
author: bradrydzewski
---

The Drone Autoscaler is a standalone daemon that continuously polls your build queue and provisions or terminates server instances based on volume.

**Note:** a separate database (or database schema) is required for each autoscaler. They cannot share the same underlying database tables.

Choose your hosting provider to get started:

{{< link "/install/amazon" >}}
{{< link "/install/google" >}}
{{< link "/install/digitalocean" >}}
{{< link "/install/hetzner" >}}
{{< link "/install/packet" >}}
{{< link "/install/openstack" >}}
