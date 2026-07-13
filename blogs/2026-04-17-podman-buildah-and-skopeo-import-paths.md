---
title: "Podman, Buildah, and Skopeo import paths"
url: "https://blog.podman.io/2026/04/podman-buildah-and-skopeo-import-paths/"
date: "2026-04-17"
author: "Brent Baude"
feed_url: "https://blog.podman.io/feed/"
---
Several of the containers projects are going to change their go import paths. Some of this work had been when we made the monorepo container-libs; where we moved storage, common, and image into a singular repository. The moves that are taking place now are not nearly as extreme and the motivations are also different.
