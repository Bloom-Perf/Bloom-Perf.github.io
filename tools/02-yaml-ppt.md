---
layout: single
permalink: /tools/yaml-ppt/
title: "YAML Puppeteer"
excerpt: "A scenario oriented API to control a browser with puppeteer."
author_profile: true
classes: wide
---

Project available on Github [YAML Puppeteer repository][yaml-pptr-repository].

Puppeteer is a powerful tool, offering control over a browser via a JavaScript API. While it's incredibly versatile, it is also quite low-level and necessitates familiarity with the rapidly evolving JavaScript ecosystem. More importantly, it requires writing code instead of simply crafting scenarios. In the context of traffic simulation, the real value lies in the functional aspect - describing user interactions with the interface, rather than programming the simulation itself. This is where yaml-pptr comes into play. It provides an API to define scenarios in a more accessible and user-friendly way, which are then executed in a browser using the Puppeteer library.

Key Features of Yaml-pptr:

- Maintains a high-level approach, abstracting away the complexities of direct programming.
- Emphasizes a scenario-based methodology, allowing users to outline a session starting with a connection followed by a series of interactive steps.
- Lightweight design, ensuring ease of use and integration.

[yaml-pptr-repository]: https://github.com/Bloom-Perf/yaml-pptr