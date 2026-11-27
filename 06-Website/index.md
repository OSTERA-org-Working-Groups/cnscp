---
layout: home
title: Home
hero_title: "Connectivity Naming System using Connection Profiles (CNSCP) Working Group"
hero_text: "The purpose of this working group is to standardize the naming and contract layer for connections."
hero_buttons:
  - label: Work Items
    url: /work-items/
  - label: Read the Charter
    url: "https://github.com/OSTERA-org-Working-Groups/cnscp/blob/main/01-Governance/2026-10-13-wg-cnscp-charter.pdf"
    style: secondary
---

## Purpose and Scope

Identity says who you are. MCP and A2A say how to talk. CNS/CP says whether you may connect, and on what terms.

CNS/CP is a naming and contract layer for connections between systems that were never designed to work together. CNS resolves a name to a system the way DNS resolves a name to a host. A Connection Profile is the named contract behind that name: it defines exactly two roles, provider and consumer, what each side must supply, and the context an interaction has to satisfy before it is permitted. Two parties in different organizations can therefore discover each other, establish that the interaction is allowed, and bind — without a bilateral integration project first. Today that work is done with glue code written once per pair of systems and thrown away when either end changes. CNS/CP standardizes the binding rather than the messages.

{% comment %}
  Goals and Outcomes (optional). To show this section on the home page,
  delete the "comment" line above the heading and the "endcomment" line
  after it, then replace the example goals with the goals from the charter.
{% endcomment %}
{% comment %}
## Goals and Outcomes

* First goal of the Working Group.
* Second goal of the Working Group.

See [Work Items]({{ '/work-items/' | relative_url }}) for the current status of each.
{% endcomment %}

## Working Group Information

* **Chair:** {{ site.chair }}
* **Charter:** [Read the charter]({{ site.charter_url }})
* **Repository:** [{{ site.repo_url | remove: 'https://' }}]({{ site.repo_url }})
* **Published documents:** [{{ site.publications_url | remove: 'https://' }}]({{ site.publications_url }})

<!-- BEGIN STANDARD TEXT -->

## Participating

Participation is open to OSTERA members. However, anyone may comment on a draft during its Public Review. See [How to Participate](https://wg.ostera.org/participate/), and read the [Contributing Guidelines](https://github.com/OSTERA-org-Working-Groups/.github/blob/main/CONTRIBUTING.md) before you open an issue or a pull request.

## Policies

The official OSTERA policies, including the IPR and Copyright Policy, the Working Methods, and the Code of Conduct, are published at [ostera.org/policies/](https://ostera.org/policies/).

<!-- END STANDARD TEXT -->
