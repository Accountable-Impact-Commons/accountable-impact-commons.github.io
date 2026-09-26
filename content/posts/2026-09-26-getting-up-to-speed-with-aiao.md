---
title: "Getting Up to Speed with the Anthropogenic Impact Accounting Ontology"
date: 2026-09-26
draft: true
summary: "An onboarding guide for teams in the IEEE ClimateChain Global Hackathon who want to work with interoperable impact data."
tags: ["onboarding", "hackathon"]
---

Welcome to the onboarding page for the Anthropogenic Impact Accounting Ontology (AIAO). We have set this up to help teams in the IEEE ClimateChain Global Hackathon get rolling with interoperable impact data. If your team is building climate ledgers, ESG reporting systems, or data exchange frameworks, consider implementing the AIAO Suite.

## Why use AIAO?

Standardising the semantics of impact data is a prerequisite for trustworthy, decentralized impact MRV infrastructure. Without a shared vocabulary, ledgers, analytics and audit tools cannot reason over data in a comparable way.

The AIA Ontology Suite is a tool for aggregating and consolidating impact accounting data across different standards and vocabularies. The ontologies are generic enough for anthropogenic impact accounting in almost any discipline and context, including climate action impact accounting.

With the AIAO Suite we enable:

- the exchange of impact data
- the verification of impact evidence across platforms
- the semantically explicit linking of claims and evidence
- the reuse of common classes and properties
- the mapping of legacy schemas into a common model

## What the suite contains

The Anthropogenic Impact Accounting Ontology Suite provides a comprehensive semantic framework for representing anthropogenic impact accounting data in a machine-readable format. The suite currently consists of four specialised ontologies, each published at a permanent W3ID address:

- [Anthropogenic Impact Accounting Ontology](https://w3id.org/aiao)
- [Claim Ontology](https://w3id.org/claimont)
- [Impact Ontology](https://w3id.org/impactont)
- [Information Communication Ontology](https://w3id.org/infocomm)

The ontology files at W3ID can be retrieved over HTTP by automated or manual means, so you can load them directly from code as well as open them in a browser.

<!-- TO EXPAND: "How does it work in practice" paragraph.
     From Kit's pad: "Somebody with technical expertise needs to fill in this
     section." The pad's stub read: "The ontology files at W3ID can be accessed
     via http by automated or manual means..."
     Worth covering: content negotiation at the W3ID redirect, which
     serialisations are served (Turtle, RDF/XML, JSON-LD), and a short worked
     snippet loading an ontology from code. -->

<!-- TO EXPAND: "What" section, i.e. products or services that can be developed.
     Kit's pad lists these as bullets still to be written:
       - What can you do with AIAO
       - Example use cases
       - Integration on a software level
       - Links to How-To's for existing data
       - Links to documentation and user resources
     The "Worked examples" section below covers the fourth bullet only. -->

## Worked examples

Our GitHub repository provides guides for annotating your data with AIAO, whether you want to do it [manually](https://github.com/Accountable-Impact-Commons/aiao/tree/main/examples/1-gs3492) or [with LLM assistance](https://github.com/Accountable-Impact-Commons/aiao/tree/main/examples/2-ecoregistry126).

## Contact and support

For general information, see the rest of this site.

To chat, join the [LFDT Discord](https://discord.gg/hyperledger). There is a channel for the [#accountable-impact-commons Lab](https://discord.com/channels/905194001349627914/1540006318125879346), which you can activate under Channels and Roles.
