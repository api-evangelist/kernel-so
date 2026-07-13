---
title: "how to make firecracker fast(er) to start chromium in < 20ms"
url: "https://www.kernel.sh/blog/firecracker-faster"
date: "2026-06-05"
author: "Steven Miller"
feed_url: "https://www.kernel.sh/api/blog/rss"
---
kernel got our start running chromium in a firecracker vm. we spent the past 14 months making it even faster. we're sharing how we get the most out of firecracker using snapshots, copy-on-write forks, uffd paging, and hot pools.
