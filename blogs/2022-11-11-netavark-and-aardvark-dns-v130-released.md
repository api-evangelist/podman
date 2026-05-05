---
title: "Netavark and Aardvark-dns v1.3.0 released"
url: "https://podman.io/blogs/2022/11/11/nvav1.3"
date: "Fri, 11 Nov 2022 00:00:00 GMT"
author: ""
feed_url: "https://podman.io/blogs/rss"
---
<p><img alt="podman logo" class="img_ev3q" height="61" src="/assets/images/podman-ce586c2894883ad9c353492b5e1893a8.svg" width="228" /></p><h1>Netavark and Aardvark-dns v1.3.0 release</h1><p>We have cut new releases of the network stack components for <a href="https://github.com/containers/netavark/releases/tag/v1.3.0" rel="noopener noreferrer" target="_blank">netavark</a>
and <a href="https://github.com/containers/aardvark-dns/releases/tag/v1.3.0" rel="noopener noreferrer" target="_blank">aardvark-dns</a>. Both netavark and aardvark-dns
versions 1.3.0 were released. As the process works, the upstream releases will slowly work their way into
Linux distributions.</p><p>A basic summary of changes for both are as follows:</p><h3 class="anchor anchorWithHideOnScrollNavbar_WYt5" id="v130-netavark">v1.3.0 Netavark<a class="hash-link" href="#v130-netavark" title="Direct link to v1.3.0 Netavark">​</a></h3><ul><li>Housekeeping and code cleanup</li><li>macvlan: remove tmp interface when name already used in netns</li><li>Add support for route metrics</li><li>netlink: return better error if ipv6 is disabled</li><li>macvlan: fix name collision on hostns</li><li>Ignore dns-enabled for macvlan (BZ2137320)</li><li>better errors on teardown</li><li>allow customer dns servers for containers</li><li>do not set route for internal-only networks</li><li>do not use ipv6 autoconf</li></ul><h3 class="anchor anchorWithHideOnScrollNavbar_WYt5" id="v130-aardvark-dns">v1.3.0 Aardvark-dns<a class="hash-link" href="#v130-aardvark-dns" title="Direct link to v1.3.0 Aardvark-dns">​</a></h3><ul><li>allow one or more dns servers in the aardvark config</li></ul>
