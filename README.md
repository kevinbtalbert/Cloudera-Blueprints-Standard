# Cloudera Blueprint: [Blueprint Name]

> Copy this template repo as the starting point for a new blueprint. Keep business and onboarding content here. Populate catalog and website fields in [`METADATA.yaml`](METADATA.yaml). At a minimum, the Blueprint should have these fields. Feel free to add additional ones as you see fit for your Blueprint. After reading this, the user should walk away with an understanding of how the Blueprint works, its purpose, and how to deploy it themself. Once the repo is complete, Cursor/AI can fill a lot of this in for you.

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Use Case](#use-case)
- [Key Features](#key-features)
- [Quickstart](#quickstart)
- [Architecture / Software Components](#architecture)
- [Target Audience](#target-audience)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Hardware Requirements](#hardware-requirements)
- [Documentation](#documentation)

## Overview

[comment]: <> (Why: First impression for catalog visitors and GitHub readers. Answer "what is this and why Cloudera?" in one scannable paragraph. Audience: executives, architects, and developers browsing the catalog.)

[One paragraph: what this blueprint does, who it is for, and the Cloudera platform value.]

## Demo

[comment]: <> (Why: Proof that the blueprint works end-to-end. A Reprise or recorded walkthrough lowers adoption friction for SEs and customers who won't clone the repo first. Audience: sales, SEs, and evaluators.)

[Link to reprise demo walking through blueprint solution]

## Use Case

[comment]: <> (Why: Connects technical components to a business problem. Helps catalog filters and internal reviewers assess industry fit and alignment. Audience: solution architects and customer stakeholders validating relevance.)

[Problem statement and primary business outcome.]

## Key Features

[comment]: <> (Why: Scannable differentiators for the catalog detail page and README skimmers. Keep these outcome-oriented, not implementation details. Audience: architects comparing blueprints and developers scanning for capabilities.)

- [Feature 1]
- [Feature 2]
- [Feature 3]

## Quickstart / Guide

[comment]: <> (Why: The minimum path from clone to working demo. Reduces time-to-first-success for developers and SEs running the blueprint in a lab. Link out to Reprise or docs if setup is long. Audience: hands-on implementers.)

1. Clone the repository.
2. Insert additional steps here or link to another page / Reprise with setup steps.

## Architecture / Software Components

[comment]: <> (Why: Shows how Cloudera products and supporting services fit together. Helps platform teams validate dependencies and security review scope. Audience: architects, platform engineers, and technical reviewers.)

Briefly describe the software components and sketch an architecture diagram of the components use. Illustration does not need to be incredibly complex but should illustrate the architecture of the project and its relevant components.
Sample architecture sketch example: https://github.com/cloudera/CML_AMP_LLM_Chatbot_Augmented_with_Enterprise_Data/blob/main/images/rag-architecture.png

## Target Audience

[comment]: <> (Why: Sets expectations for skill level and role so readers self-select before investing in deployment. Also guides catalog positioning and demo narrative. Audience: blueprint authors and catalog curators; indirectly helps readers.)

- [Persona 1 — e.g., ML engineer, data engineer, solution architect]
- [Persona 2]

## Repository Structure

[comment]: <> (Why: Orients new contributors and forked repos to where code, deploy configs, and metadata live. Keeps blueprint repos consistent across the catalog. Audience: developers extending the blueprint and reviewers auditing repo completeness.)

| Path | Description |
| --- | --- |
| `assets/` | Diagrams, screenshots, sample media |
| `deploy/` | Deployment configs (Docker Compose, Helm, scripts) |
| `docs/` | Extended documentation |
| `METADATA.yaml` | Catalog metadata for the Cloudera blueprint website |
| etc... |

## Prerequisites

[comment]: <> (Why: Surfaces blockers before someone starts deployment—entitlements, API keys, tooling. Reduces failed installs and support churn. Audience: developers and SEs preparing an environment.)

Describe the software components and tools required to use the Blueprint.
(e.g. Cloudera platform access / entitlement, API keys, Tools such as git, Docker, etc.)

## Hardware Requirements

[comment]: <> (Why: Sets realistic expectations for demo vs. production sizing. Helps SEs pick lab instances and customers plan capacity. Audience: platform engineers and infrastructure teams provisioning environments.)

| Deployment | Minimum |
| --- | --- |
| [Launchable / demo] | [CPU, RAM, storage] |
| [Production / enterprise] | [CPU, RAM, GPU, storage] |

## Documentation

[comment]: <> (Why: Points to deeper material without bloating the README. Optional but valuable for complex blueprints. Audience: implementers who need runbooks, API refs, or video overviews beyond the quickstart.)

Example documentation below. Incorporate what makes sense. Not a required field.
- [Link to extended docs in `docs/`]
- [Link to Cloudera product documentation]
- [Youtube video overview of Blueprint]
