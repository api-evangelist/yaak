---
title: "Readable Streaming Responses for LLM APIs and GraphQL Operation Names"
url: "https://yaak.app/changelog/2026.5.0"
date: "2026-07-21"
author: "Gregory Schier"
feed_url: "https://yaak.app/rss.xml"
---
This release adds readable streaming responses for LLM APIs , support for GraphQL operation names , a time-grouped response history , and performance work including SQLite WAL mode and a fix for constant CPU usage when Git syncing inside large repos. Readable streaming responses for LLM APIs LLM APIs like OpenAI and Anthropic stream their responses as server-sent events, which makes the actual message hard to read. Yaak now assembles the model’s output into a single readable view that updates as tokens stream in.
