# Laura Graph Dummy – Public Companion Note

`laura_graph_dummy_publishable.json` is a publication-safe demonstration file for Laura's memory graph architecture.

The file is intentionally **structurally rich**. It does not merely show a flat schema or a minimal toy example, but preserves the kind of layered organization the real system uses:

- clusters
- subclusters
- nodes
- cross-module relations
- marker-like structures
- governance and self-model components
- references not only to nodes, but also to cluster and subcluster paths

## Why This File Is More Complex Than a Minimal Example

A very small dummy file would be easier to read, but it would also give a misleading impression of the architecture.

Laura's memory system is not a simple list of facts or a key-value store. It is closer to a **multi-layer semantic graph** in which:

- some nodes describe stable identity or governance structures
- some nodes represent affective or regulatory markers
- some relations connect concrete nodes
- some relations point to higher-level structural units such as subclusters
- different modules interact across abstraction levels

Because of that, this dummy file keeps a realistic degree of structural depth while replacing all private or personal content with synthetic placeholders.

## What Is Authentic and What Is Synthetic

Authentic:

- the overall graph logic
- the cluster/subcluster organization
- the style of node identifiers
- the presence of governance, self-model, social-memory and regulation layers
- the use of typed relations across modules
- the fact that marker-like structures can carry technical signatures and effect profiles

Synthetic or anonymized:

- all concrete contents
- all descriptions that could expose personal context
- all example values that would reveal actual memory content
- all relational meanings that would identify private interaction history

## Intended Use

This file is meant for:

- repository readers who want to understand the architecture
- researchers studying emergent memory structures in LLM systems
- developers building tooling, validators or visualizations for this graph format
- public explanation without disclosing private memory data

## Reading Tip

The easiest way to understand the file is to read it in this order:

1. `meta.schema_hints`
2. top-level `clusters`
3. one cluster with several subclusters such as `meta_cognition` or `social_memory`
4. the `relations` sections at subcluster, cluster and root level

This makes it easier to see that the graph is not only a container for memories, but also a representation of functional architecture.
