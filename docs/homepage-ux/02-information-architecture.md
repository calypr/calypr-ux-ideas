# 02 — Information Architecture

## IA goal

Create a structure that communicates:
- one platform
- shared datasets
- multiple modes of use
- clear role-appropriate entry points

## Recommended top-level structure

- **Home**
- **Workspace**
- **Explore**
- **Published Results**
- **Datasets**
- **Docs**

## Section definitions

### Workspace
Audience:
- data contributors
- developers
- operators

Purpose:
- submit and manage data
- monitor ingestion and pipelines
- manage jobs, schemas, permissions, and system activity

Notes:
- This is the operational area
- “Workspace” is more user-friendly than “Dashboard” for a primary nav label

### Explore
Audience:
- data readers
- analysts
- researchers

Purpose:
- query and filter datasets
- compare results
- save searches
- export findings
- investigate data interactively

Notes:
- Prefer “Explore” over “Portal”
- “Portal” is vague and often overloaded

### Published Results
Audience:
- stakeholders
- collaborators
- presentation audiences
- users consuming finalized outputs

Purpose:
- browse curated findings
- access release-ready or publication-ready result views
- review approved reports and story-driven outputs

Notes:
- Prefer “Published Results” over “Presentation”
- “Presentation page” describes format, not user value

## Conceptual model

The platform supports a lifecycle:

1. **Contribute**
2. **Analyze**
3. **Publish**

That lifecycle should be reflected in language, navigation, and cross-links.

## Cross-navigation model

Users should be able to move between sections without feeling they are leaving the platform.

Recommended cross-links:

From **Workspace**:
- Open dataset in Explore
- View dataset details
- Publish approved result

From **Explore**:
- View source dataset
- Save as report
- Publish result
- Open related workspace item (if permissions allow)

From **Published Results**:
- View underlying dataset
- Open analysis workspace
- View methodology / source query

## Shared data principles

Because the same datasets appear in multiple modes, maintain consistency in:

- dataset names
- metadata labels
- filtering concepts
- terminology
- status labels
- release/version references

Avoid:
- renaming the same object differently in different sections
- using different filter logic in different modes without explanation
- making published outputs feel disconnected from underlying sources

## Role-aware behavior

If user roles are known after login, default users into the most likely area:

- contributors/developers → Workspace
- analysts/readers → Explore
- presentation viewers/stakeholders → Published Results

However:
- always allow switching
- do not hard-lock the experience unless permission boundaries require it

## IA summary

The structure should answer:
- what can I do here?
- where should I start?
- how do these three areas relate?

It should not force users to interpret internal product architecture.
