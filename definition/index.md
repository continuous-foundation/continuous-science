---
title: Defining Continuous Science
---

Continuous science is an evolving response to a simple but urgent realization: science has changed, and the systems we use to share it have not.

Research today is computational, collaborative, data-rich, iterative, fast-paced. Yet the ways we evaluate, communicate, and credit that work remain largely static — often reducing rich, interactive, and iterative efforts into flattened PDFs and disconnected supplements. In response, continuous science offers a shift: from publishing as a single moment to communication as an ongoing process; from static articles to complete, connected, and reusable research objects; from one-size-fits-all journals to modular, interoperable systems designed with researchers in mind.

But what exactly is _continuous science_? It isn’t a single technology or standard. It’s a set of emerging practices, tools, and cultural shifts — many already underway — that emphasize iteration, integration, networks, and researcher-first infrastructure. And like the science it aims to support, the definition of continuous science is itself **continuous**: something we are refining together, based on real needs, working examples, and shared understanding.

This glossary collects terms that help describe and shape this evolving approach. It doesn’t aim to lock things in place, but to build shared language we can use to clarify our goals, align our efforts, and improve how science is done and shared.

We are defining Continuous Science not just to describe a movement, but to make its future more actionable, visible, and possible as well as to coordinate ongoing efforts in the community.

:::{glossary}

Continuous Science
: **Continuous Science** is an approach to scientific research and communication that emphasizes {term}`iteration <iterative>` and {term}`rapid <rapid>` sharing throughout the entire research lifecycle. Continuous Science supports early and often {term}`sharing <shared>` of {term}`complete <complete>` artifacts (either privately or {term}`openly <open>`), with tools and practices that promote the {term}`integration <integrated>` of data, code, and methods directly into scientific narratives. It prioritizes {term}`automation <automated>`, {term}`reproducibility <reproducible>`, and {term}`reuse <reusable>` — enabling researchers to {term}`collaboratively <collaborative>` build on each other's work more {term}`easily <assisted>`, receive timely feedback, and treat communication as an ongoing **process** rather than a final _product_.

:::

## Related Concepts

Our current working definition of **Continuous Science** is pulling together many actions and concepts in a related [glossary](./glossary.md). The core concepts that stand out are {term}`rapid <rapid>`, {term}`complete <complete>`, {term}`reusable <reusable>`, and {term}`automated <automated>`.

```{mermaid}
graph TD

  %% Core Pillars
  Rapid[Rapid]
  Complete[Complete]
  Reusable[Reusable]
  Automated[Automated]

  %% Rapid Branch
  Rapid --> Versioned
  Rapid --> Iterative
  Rapid --> Shared
  Rapid --> Collaborative

  %% Complete Branch
  Complete --> Reproducible
  Complete --> Structured
  Complete --> Integrated

  %% Reusable Branch
  Reusable --> Composable
  Reusable --> Granular
  Reusable --> Interoperable
  Reusable --> Networked

  %% Automated Branch
  Automated --> Assisted
  Automated --> Control

  %% Cross-principle links
  Shared --> Versioned
  Iterative --> Reproducible
  Iterative --> Versioned
  Reproducible --> Interactive
  Interactive --> Executable
  Executable --> Structured
  Structured --> Interoperable
  Structured --> Networked
  Shared --> Open[Open]
  Reusable --> FAIR[FAIR]

  %% Optional: show that this is part of continuous science
  Continuous[Continuous Science]
  Continuous --> Rapid
  Continuous --> Complete
  Continuous --> Reusable
  Continuous --> Automated

```
