---
layout: single
permalink: /tools/mochi/
title: "Mochi"
excerpt: "Simple and reliable HTTP Mock server written in RUST."
author_profile: true
classes: wide
---

Project available on Github [Mochi repository][mochi-repository].

In the routine operations of a performance testing consultant, it's a frequent practice to substitute actual dependencies with mock components to focus solely on the element being tested. Typically, this involves the use of a basic HTTP server that consistently delivers the same response. In the majority of scenarios, about 95%, these simple servers with limited routes are sufficient, eliminating the need for a full-scale application, complete with version-controlled repositories, Dockerfiles, and Docker registries, which might not be optimally performant. Ideally, a tool should exist that can effortlessly launch such a server with minimal configuration, providing essential features like metrics and logs for easy monitoring and troubleshooting of the mock environment.

This is the motivation behind the development of Mochi. Our goal was to create a tool that is not only quick and straightforward to configure for the vast majority of use cases but also capable of addressing the remaining 5% with additional features that are currently under development.

Key Features of Mochi:

- Designed to cater to 95% of use cases with an extremely user-friendly configuration process.
- Developed using Rust and Tokio for speed and high efficiency.
- Fully cloud-native, complete with a Docker image for seamless integration.
- Equipped with metrics that can be easily monitored via an existing Grafana dashboard.
- Includes advanced latency configuration options, enabling common latency profiles like the 'snowball effect'.

[mochi-repository]: https://github.com/Bloom-Perf/mochi
