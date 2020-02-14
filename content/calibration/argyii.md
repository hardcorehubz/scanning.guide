---
title: ArgyII CMS instructions
weight: 5
---

Download and install [ArgyII CMS from here][1].

Run the following command on your RAW image of the IT8 card called `scan.tif`, together with the `target.it8` that you got when you purchased the card.

```bash
scanin scan.tif target.it8

colprof -qh scanin_output
```

[1]: https://www.argyllcms.com/