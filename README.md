---
CPS: _
Title: Open Metadata Schema
Status: Open
Category: Metadata
Authors:
  - 
Proposed Solutions:
  - 
Discussions:
  - 
Created: 2025-01-07
License: _
---

## Abstract
Cardano's ecosystem benefits from a diverse set of off-chain metadata, enhancing the contextual information available for entities such as Pools, Assets, and DReps. 
However, this metadata is dispersed across multiple sources, making it challenging to locate and utilize—particularly for new developers. 
Furthermore, the lack of standardization in APIs and schemas across providers adds complexity, hindering consistent and efficient data integration.

## Problem
Building meaningful applications on Cardano required seamless access to off-chain data. 
However, the current state of off-chain metadata is highly fragmented, with no unified standards for APIs or schemas among providers. This lack of standardization creates several challenges for new developers:
1. Discovery: Developers must identify where off-chain data is stored (e.g., APIs, websites) and evaluate its relevance.
2. Intepretation: Developers need to understand the structure and meaning of the data to make it usable.
3. Integration: Accessing and storing data accross divers formats requires additional effort.
4. Consistency: Keeping data up-to-date and verifying its accuracy is complex and time-consuming.
5. Verification: Ensuring data accuracy and integrity becomes increasingly difficult with varied structures and sources. 

Currently, multiple providers offer off-chain data, each implementing its own APIs and schemas. Switching between providers often involves substrantial effort due to differences in data formats and structures, which undermines the ecosystem's decentralization and forces developers to rely on single providers.
Furthermore, the absence of a unified verification approach burdens developers with creating custom solutions to ensure the accuracy of off-chain data accross disparate sources. These challenges slow ecosystem growth, increase barriers for new developers, and reduces the overall resilience of Cardano's ecosystem.

## Goals
The following goals are intended to address the problems outlined above:
- Standardize the schema for off-chain metadata across providers
  - Including metadata for Pools, Assets, and DReps
- Define a unified API for accessing off-chain metadata

## Use Cases

## Open Questions