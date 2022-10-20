---
description: Multiple attributes of Entities that help capture their various dimensions.
---

# Tags

!!! warning
	The idea of **`Tags`** is one we feel is important, but right now they are sort-of all over the place and we need to find a good balance between the [google-sheets.md](../../../learning/tools/google-sheets.md "mention") approach and something much more robust. We think [kumu.md](../../../learning/tools/kumu.md "mention") offers some options with JSON blueprints, but need to explore further.

`Tags` allow for the easy filtering of [entities.md](entities.md "mention") based on a single field with multiple keywords (e.g. `Kessel Run` is an `Entity` that might have the `Tags` `Military` `Air Force` `Software`, and so on.&#x20;

By clicking on or filtering by a `Tag` one can easily see all the `Entities` associated with it in the [.](./ "mention"), [graph.md](../graph.md "mention"), [map.md](../map.md "mention"), and [timeline.md](../timeline.md "mention").

### Problems with Tags

Unfortunately, executing this in [google-sheets.md](../../../learning/tools/google-sheets.md "mention") using [kumu.md](../../../learning/tools/kumu.md "mention") is sort-of a challenge because:

1. [kumu.md](../../../learning/tools/kumu.md "mention") uses `|` connectors in a single field to separate `Tags` (which means you cannot run a simple `Data Validation` rule against a list of keywords like we do with `Labels`, `Categories`, and `Connections`.
2. The whole idea of `Tags` depends on a common set of terms... but how do you know whether to use `Software` or `DevSecOps` or `Technology` or something else? Who makes these decisions and how do the uninitiated learn? (NOTE: We will keep this page updated with our hypotheses and approaches).

### Future Plans for Tags

We are very open to ideas and existing best practices here, so please [contact-us.md](../../contact-us.md "mention") if you have ideas or examples to share! We think our [partners.md](../../support/partners.md "mention") may be able to help with this as well.
