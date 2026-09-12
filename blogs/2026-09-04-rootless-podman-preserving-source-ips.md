---
title: "Rootless Podman: Preserving Source IPs"
url: "https://blog.podman.io/2026/09/rootless-podman-preserving-source-ips/"
date: "2026-09-04"
author: "Jan Rodak"
feed_url: "https://blog.podman.io/feed/"
---
Rootless Podman has a long-standing limitation reported since 2020: containers on bridge networks can’t see the real source IP of incoming connections. The `rootlessport` userspace proxy rewrites the source to the container’s own subnet address, breaking IP-based access control, logging, and rate limiting. Pesto, a new companion tool from the passt project solves this.
