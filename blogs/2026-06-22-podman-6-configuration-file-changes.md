---
title: "Podman 6 Configuration File Changes"
url: "https://blog.podman.io/2026/06/podman-6-configuration-file-changes/"
date: "2026-06-22"
author: "Paul Holzinger"
feed_url: "https://blog.podman.io/feed/"
---
Podman 6 is about to be released soon, so I would like to talk about the biggest change we made: a major rework of how we handle and parse our configuration files. This does not just affect Podman but also Buildah, Skopeo, and many other tools building on top of our underlying go.podman.io/image and go.podman.io/storage […]
