---
description: >-
  The Organizations, Groups, Activities, Artifacts, and Individuals that make-up
  this project.
---

# Entities

Trying to understand [.](./ "mention") in this project requires a fundamental understanding of [data-structures.md](../../../learning/concepts/data-structures.md "mention") **** and [dimensionality.md](../../../learning/concepts/dimensionality.md "mention"), but since you may not want to jump straight into [Broken link](broken-reference "mention") or [concepts](../../../learning/concepts/ "mention") we'll just summarize [entities.md](entities.md "mention") as follows:

{% hint style="info" %}
[entities.md](entities.md "mention") **and** [connections.md](connections.md "mention") **are the two foundational building blocks of the** [.](./ "mention").
{% endhint %}

We go into a bit more detail about [entities.md](entities.md "mention") in the following two sections:

* [#types-of-entities](entities.md#types-of-entities "mention") - variations in what we use to ground [connections.md](connections.md "mention")
* [#filterable-attributes](entities.md#filterable-attributes "mention")- attributes that we use with visualizations&#x20;
* [#non-filterable-attributes](entities.md#non-filterable-attributes "mention") - attributes that help us learn more

## Types of Entities

When reviewing the existing work, we realized that there were a few different types of building blocks that characterized the national security ecosystem as it pertains to innovation.&#x20;

Below you will find each of them listed and defined with an example or two for context.

### Organization

{% hint style="success" %}
An **`Organization`** is a formally established body of individuals with documented responsibilities.
{% endhint %}

We recognize that this definition may be obvious, but want to set everyone up with a common understanding of our terms.&#x20;

To simplify the framework across different `Categories` we did not choose any `Entities` that might be used more specificially in a given context (e.g. `Staff` to indicate what type of `Entity` a `Government` `Organization` is, or `Startup` to indicate a more specific `Commercial` `Entity`).&#x20;

We make up for this choice by using [#tags](entities.md#tags "mention"), which are more modular and allow for simple `Entity` resolution with more nuanced contextual references (e.g. you can filter the [graph.md](../graph.md "mention") by all of the `Organizations` with `Staff` or `Startup` as one of the [#tags](entities.md#tags "mention")).

{% hint style="warning" %}
_**Note:** One of the beneficial aspects about starting with_ [.](./ "mention") _and being very specific about what we mean by different terms is that we can more easily make changes and updates based on_ [feedback.md](../../feedback.md "mention")_. We will continue to evaluate this_ `Type` _over time._
{% endhint %}

> **Example:** The `Defense Innovation Unit` is a `Government` office, `Stanford University` is an `Academic` institution, `Saildrone` is a `Commercial` company, and the `RAND Corporation` is a `Non-Profit`. Each is an `Organization` distinguished by [#categories](entities.md#categories "mention").

### Group

{% hint style="success" %}
**`Groups`** are similar to an **`Organizations`**, but more informal and not as widely recognized.
{% endhint %}

This type is valuable because some meaningful contributors to innovation in national security do so within such informal networks and relationships. Sometimes these evolve into more formal structures or `Organizations`, sometimes they originate in such `Organizations` or emerge from `Activities` - regardless, they will typically be more amorphous and less defined, yet worth characterizing.

Additionally, a project might be understood in some ways as a `Group` that probably includes `Activities` and produces some sort of `Artifact`.

> **Example:** The `Federal Innovators Salon` is gathering of government employees focused on innovation, but not a formal `Non-Profit` `Organization`. It also holds `Events`, which may or may not generate `Artifacts`.&#x20;

### Individual

{% hint style="success" %}
An **`Individual`** is a person involved in an **`Organization`**, **`Group`**, or **`Activity`** that is deemed important as a **`Data`** element and either has publicly accessable information available or consents to be included.
{% endhint %}

Social network analysis (SNA) is a very useful tool in understanding multiple facets of a movement or organization (in fact, [kumu.md](../../../learning/tools/kumu.md "mention") has a dedicated feature for just this purpose). While the [graph.md](../graph.md "mention") will support baseline network analysis across organizations, some of which is representative of underlying social networks, we know from our personal experience that the web of personal ties is much different than the lines draw by organizaitonal charts.

We see a couple use cases for this `Entity` type, both of which have pros and cons:

* **Public individuals**, such as government leaders or those in key organizational positions, whose tenure and activities can help enrich an understanding of why certain activities did or did not take place. The down-side of this is potentially giving too much weight to said individuals.
* **Private individuals**, typically those of lower power or who do not have a public-facing role, whose actions and connections often drive much of the ground-up drive behind innovative efforts. A potential con of this is not being able to represent enough of such individuals to accurately capture a network due to privacy concerns.

{% hint style="warning" %}
_**NOTE**: While we recognize that_ **`Individuals`** _are important to understanding certain aspects of innovation in national security, we want to be thoughtful about how they are integrated (for example, public vs. private figures and contact information)._
{% endhint %}

> **Example:** `Hondo Guerts` is an `Individual` whose tenure as the Assistant Secretary of the Navy for Research, Development, and Acquisition included the establishment of `NavalX`, a `Government` `Organization`, may benefit those studying innovation in national security.

### Activity

{% hint style="success" %}
An **`Activity`** is executed by an **`Organization`**, **`Group`**, or **`Individual`** to achieve a goal or end state.&#x20;
{% endhint %}

There are many different activities tied to national security as well as innovation. Some are linear processes, some are cycles, others are more like projects or events, but each must be initiated to achieve an outcome and comprise actions, not just individuals (which is what differentiates an `Activity` from a `Group`, since they are otherwise very similar).

> **Example:** The `Defense Entrepreneurs Forum` annual conference is an `Activity` geared toward the `Organization` mission of inspiring, connecting, and empowering people in the national security community.

### Artifact

{% hint style="success" %}
An **`Artifact`** is produced as part of an **`Activity`** by an **`Organization`**, **`Group`**, or **`Individual`** and contributes to an understanding of innovation in national security.
{% endhint %}

`Artifacts` are the sibling `Entities` to `Activities` and allow for a more nuanced understanding of an `Organization`, `Group`, or `Individual` in the form of physical or digital remnants.

> **Example:** `General Charles Brown` is an `Individual` whose tenure as Chief of Staff of the Air Force and associated `Artifact` generation in the form of memos to "Accelerate Change or Lose" may benefit those studying innovation in national security. [research](../../../learning/research/ "mention") is also useful as `Artifacts`.

### Repository

{% hint style="success" %}
A **`Repository`** is an **`Artifact`** collection tied to a national security-relevant **`Organization`**, **`Group`**, **`Individual`**, or **`Activity`**, especially one where the content is non-public.
{% endhint %}

`Repositories` store information, some of which may be in the form of `Artifacts`, though most will be so large or non-public that specific `Artifacts` are unlikely to be linked. `Repositories` are typically a data set or database, though the exact structure may be non-public or unknown.

> **Example:** `AFWERX` is a `Government` `Organization` that contracted with `Mobilize`, a `Commercial` `Organization`, to create `Vision`, a non-public web platform that includes a `Repository` of `US Air Force` innovation projects and activities, among other data holdings and features.

{% hint style="warning" %}
_**NOTE**: There are likely to be_ **`Repositories`** _whose existence or details would be contrary to this project's goal of supporting national security, so we want to approach any such inclusions holistically (for example, the inclusion of links or other potentially sensitive information that is not publicly available)._
{% endhint %}

## Filterable Attributes&#x20;

Now that we have an understanding of what [entities.md](entities.md "mention") are, we need to dig into a bit more what characterizes them - for this, we have a few different features or attributes, the most importance of which we use as filters to modify different visualizations in the [graph.md](../graph.md "mention"), [timeline.md](../timeline.md "mention"), and [map.md](../map.md "mention").

### Categories

{% hint style="success" %}
A **`Category`** is essentially an attribute with a singular value used to help organize or filter different **`Entities`**.
{% endhint %}

More is covered on these in the dedicated ensuing [categories.md](categories.md "mention") section, but for the purpose of this project, an `Entity` can only have one `Category`. Because this gets into serious questions about [dimensionality.md](../../../learning/concepts/dimensionality.md "mention") and even has potential implications for [ethics.md](../../support/ethics.md "mention"), we dive deeper into it in the next section.

The important thing to understand is that, like [#organization](entities.md#organization "mention") and [#tags](entities.md#tags "mention"), this attribute is malleable to meet the needs of the project. While we are defaulting to a more robust set of [#tags](entities.md#tags "mention") and fewer [#categories](entities.md#categories "mention"), this is largely driven by limitations of [kumu.md](../../../learning/tools/kumu.md "mention"), which only allows one set of multi-select fields.&#x20;

The option to sub-divide [#categories](entities.md#categories "mention") exists (e.g. making `Government - Staff` an option instead of just `Government`), but we want to give some time to work with users before diving too far into the weeds, since we know whatever the project starts with will inevitably change (and the [categories.md](categories.md "mention") page will be the one-stop shop for any such changes to be documented).

> **Example:** The `Defense Innovation Unit` cannot be both a `Government` `Entity` and a `Commercial` `Entity` - it must be one or the other, in this case `Government`.

### Tags

{% hint style="success" %}
**`Entities`** can have multiple **`Tags`**, which allow for greater understanding of their different dimensions by creating multiple facets through which to view them.
{% endhint %}

`Tags` are both powerful and confusing, which are really two sides of the same coin. To understand them further, we highly recommend learning about [dimensionality.md](../../../learning/concepts/dimensionality.md "mention"), but here's a quick synopsis.

Because `Entities` can have multiple `Tags`, they allow for flexible viewing, reducing complexity by filtering out `Entities` that do not meet the relevant criteria when such criteria can easily apply to multiple `Entities` and is not a defining characteristic in the same way `Categories` are set-up. This makes them powerful.

They are confusing, though, because of this same feature: who picks the `Tags` and what do they mean? Should `Tags` be defined by the nomenclature of a given `Organization` or their dictionary defition? This gets confusing quickly, so read on in [tags.md](tags.md "mention") for more.

> **Example:** The Defense Innovation Unit has `Defense`, `Military`, `Innovation`, and `Unit` tags in order to help visualize it alongside other `Entities` with the same tags.

### Range

{% hint style="success" %}
The **`Range`** is a time period or series of years where an **`Entity`** existed, used most with the **`Timeline`**.
{% endhint %}

While this feature will likely change over time, we believe there is value in seeing not only the current state of innovation in national security, but also its historical evolution. For this reason we need to capture [.](./ "mention") for the [timeline.md](../timeline.md "mention") and this field is where we do so.

{% hint style="warning" %}
_**NOTE**: This formatting is very specific to_ [kumu.md](../../../learning/tools/kumu.md "mention")_, which is our initial visualization tool, but as we move through various stages of the process the associated_ [.](./ "mention") _fields may change to accomodate other tools or approaches._
{% endhint %}

> **Example:** The Defense Innovation Unit has a `Range` of `2015..2022` because it was established in 2015 and continues to this day.

## Non-Filterable Attributes

In addition to the attributes listed above, which allow us to reduce the size or complexity of our [.](./ "mention") by filtering, there are other attributes which are essentially flat and do not further complicate the [dimensionality.md](../../../learning/concepts/dimensionality.md "mention") of an `Entity` (though they do still add dimensions).

What this functionally means is that some of these attributes might change over time or only apply to certain `Entities` based on whatever helps us better understand the [.](./ "mention").

Because these are simple and pretty intuitive, we do not go into much more detail. As much as possible, we try to reduce complexity and be cognizant of [dimensionality.md](../../../learning/concepts/dimensionality.md "mention") by not creating unique fields for `Organizations` in comparison to `Groups` or `Individuals`.

### All Entities

Any entity type can have the following non-filterable attributes:

* **Website**
* **LinkedIn**
* **Twitter**

Read on to learn more about [categories.md](categories.md "mention") and [tags.md](tags.md "mention")!

