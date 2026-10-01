---
title: "Getting Up to Speed with the Anthropogenic Impact Accounting Ontology"
date: 2026-09-26
summary: "An onboarding guide for teams in the IEEE ClimateChain Global Hackathon who want to work with interoperable impact data."
tags: ["onboarding", "hackathon"]
---

Welcome to the onboarding page for the Anthropogenic Impact Accounting Ontology (AIAO). We have set this up to help teams in the IEEE ClimateChain Global Hackathon get rolling with interoperable impact data. If your team is building climate ledgers, ESG reporting systems, or data exchange frameworks, consider implementing the AIAO Suite.

## Why use AIA

Standardising the semantics of impact data is a prerequisite for trustworthy, decentralised impact MRV infrastructure. Without a shared vocabulary, ledgers, analytics and audit tools cannot reason over data in a comparable way.

The AIA Ontology Suite is a tool for aggregating and consolidating impact accounting data across different standards and vocabularies. The ontologies are generic enough for anthropogenic impact accounting in almost any discipline and context, including climate action impact accounting.

With the AIA Ontology Suite we enable:

- the exchange of impact data
- the verification of impact evidence across platforms
- the semantically explicit linking of claims and evidence
- the reuse of common classes and properties
- the mapping of legacy schemas into a common model

## What the suite contains

The suite provides a comprehensive semantic framework for representing anthropogenic impact accounting data in a machine-readable format. It currently consists of four specialised ontologies, each published at a permanent W3ID address:

- [Anthropogenic Impact Accounting Ontology](https://w3id.org/aiao)
- [Claim Ontology](https://w3id.org/claimont)
- [Impact Ontology](https://w3id.org/impactont)
- [Information Communication Ontology](https://w3id.org/infocomm)

The ontology files at W3ID can be retrieved over HTTP by automated or manual means, so you can load them directly from code as well as open them in a browser.

### How does it work in practice?

The AIA ontology files are published with persistent W3ID identifiers and can be retrieved over HTTP by people or software. Applications can use AIA classes, properties and axioms in OWL, TTL or JSON-LD format, and can combine them with other ontologies. Browsers render the ontologies in human-friendly HTML format.

AIA provides a shared semantic model rather than prescribing a database or software platform. The beauty of semantic web technology is its composability. Systems can map their own data models to AIA terms so that information created in different systems can be interpreted and linked consistently. Validation rules, for example SHACL shapes, can be used alongside the ontology to check whether data meet application-specific requirements.

The ontology is therefore not itself a database, reporting platform or verification system. It provides a common language from which such systems can be built and through which independently developed systems can exchange information without first agreeing on the internal structure of each other's databases.

### What can you do with AIAO?

AIA can provide the semantic layer for systems that create, exchange, analyse or verify information about activities and their impacts.

It can be used in monitoring and evaluation systems, digital MRV platforms, impact registries, knowledge graphs, assurance systems and APIs. Existing systems can also map their internal data structures to AIA to improve interoperability without replacing their underlying databases. AIA can be used even where the application does not use semantic web technologies. For example, the relationships between entities and classes, each with their own properties in the ontologies that make up AIA, can be expressed in other data architectures such as RDBMS schemas.

### Example use cases

**Publish an impact claim**. Represent an activity, the indicators quantifying its inputs, outputs, outcomes and impacts, the methodologies used to calculate these indicators, the evidence on which the calculations are based and the resulting impact claim in machine-readable form.

**Trace claims to evidence**. Link a claim to the observations, calculations, sources and methodology that support it.

**Validate submissions**. Use SHACL or similar rules to test whether data and relationships that are required by a specific rule or standard are present.

**Integrate data** from different systems. Map heterogeneous data models to common AIA classes and properties so that information can be queried or combined.

**Represent methodologies**. Describe indicators, variables, calculation steps, baseline conditions and evidence requirements in a machine-readable form.

**Support independent verification**. Allow reviewers or software agents to inspect the indicators, methodologies, instruments, data and sources associated with a claim.

**Build federated registries**. Publish interoperable claims and evidence across multiple organisations without requiring a single central database.

### How-To's for existing data

Existing impact data can be mapped to the AIA Ontology Suite without changing the original source data. Practical examples are available for:

- Manual annotation – mapping an existing project and its data to AIA classes and properties without LLM assistance. [Manual annotation example](https://github.com/Accountable-Impact-Commons/aiao/tree/main/examples/1-gs3492)
- LLM-assisted annotation – using an LLM to help map existing project documentation and data to the ontologies. [LLM-assisted annotation example](https://github.com/Accountable-Impact-Commons/aiao/tree/main/examples/2-ecoregistry126)

Examples contributed by users are collected in the LFDT Community registry of annotated data. [Community registry of annotated data](https://lf-hyperledger.atlassian.net/wiki/spaces/CASIG/pages/828047391/Community+registry+of+annotated+data)

### Documentation and user resources

- The AIA Ontology Suite – overview of AIA and the companion ontologies, with links to the source repositories, HTML documentation and visualisations. [The AIA Ontology Suite](https://lf-hyperledger.atlassian.net/wiki/spaces/CASIG/pages/827261025/The+AIA+Ontology+Suite)
- AIA Resources – the main LFDT index for documentation and learning material. [AIA Resources](https://lf-hyperledger.atlassian.net/wiki/spaces/CASIG/pages/824574046/AIA+Resources)
- Ontology documentation – generated technical documentation for AIA classes, properties and axioms. [AIA HTML documentation](https://accountableimpactcommons.org/aiao/aiao.html)
- FAQ – background on standards, impact accounting and the objectives of the work. [AIA FAQ](https://lf-hyperledger.atlassian.net/wiki/spaces/CASIG/pages/828211210/FAQ)
- Theoretical expositions – background material on the conceptual foundations of AIA and semantic approaches to impact accounting. [Theoretical expositions](https://lf-hyperledger.atlassian.net/wiki/spaces/CASIG/pages/827293818/Theoretical+expositions)

## Contact & Support

For general information, see the rest of this site.

To chat, please join the [LFDT Discord](https://discord.gg/hyperledger). There's a channel for the [#accountable-impact-commons Lab](https://discord.com/channels/905194001349627914/1540006318125879346); activate it under “Channels and Roles”.
