---
layout: single
permalink: /tools/kyara/
title: "Kyara"
excerpt: "Create and deploy fake users to simulate traffic on your apps."
author_profile: true
---

All sources are available on Github [Kyara repository][kyara-repository].

Have you ever faced the challenge of writing integration tests using Postman, or perhaps the even more daunting task of maintaining end-to-end tests that interact directly with a backend service? It's often a frustrating and complex task, frequently avoided by many. Enter Kyara, a tool whose name is derived from the Japanese word for 'character'. Kyara simplifies the process by generating simulated traffic that interacts with the user interface of the backend you're testing. While the contract between the UI and the backend might change over time, the UI flow often remains consistent. By focusing on testing against the UI flow, Kyara aims to keep your tests relevant and less prone to breaking over time.

Key Features of Kyara:

- Intuitive scenario definition using YAML, making it easy to set up and manage.
- Fully cloud-native, integrating seamlessly with modern cloud infrastructures.
- Capable of simulating user traffic to rigorously test both the front-end and back-end under heavy load conditions.
- Utilizes AI to adapt integration tests in response to changes in the interface, ensuring tests remain effective and current.

[kyara-repository]: https://github.com/Bloom-Perf/kyara
