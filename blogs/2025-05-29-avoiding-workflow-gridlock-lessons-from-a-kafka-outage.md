---
title: "Avoiding Workflow Gridlock: Lessons from a Kafka Outage"
url: "https://developers.mews.com/lessons-from-kafka-outage/"
date: "2025-05-29"
author: "Petr Koutný"
feed_url: "https://developers.mews.com/feed/"
---
A Kafka outage caused thousands of our Temporal workflows to get stuck before doing any meaningful work. We shipped a fix to decouple core logic from Kafka by running steps in parallel—using the patching API and replay tests to keep things safe. We also learned a few hard lessons about versioning, workflow longevity, and staying focused on what really matters.
