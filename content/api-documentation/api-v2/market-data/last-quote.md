---
title: Last Quote
weight: 30
---

{{< info-box >}}
This feature is currently beta and invite-only.
{{< /info-box >}}

The Last Quote API provides last quote details for a symbol.

{{< rest-endpoint resource="last-quote" method="GET" path="/v1/last_quote/stocks/{symbol}" >}}

## Response

### Example
{{< rest-entity-example name="last-quote-response" >}}

## Last Quote Entity

### Properties
{{< rest-entity-desc name="last-quote" >}}
