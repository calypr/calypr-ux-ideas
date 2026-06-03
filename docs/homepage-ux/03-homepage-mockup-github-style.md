# 03 — Homepage Mockup (GitHub-Style)

## Experience direction

The homepage should be modeled after the **logged-in GitHub.com home/dashboard experience**, not the marketing homepage.

That means:
- utility-first layout
- restrained visual design
- strong hierarchy
- card-based modules
- recent activity
- contextual sidebars
- minimal promotional language

## Layout model

Use a three-column layout:

- **Left rail** — primary navigation, shortcuts, recent items
- **Center column** — homepage content and core entry points
- **Right rail** — featured items, announcements, recent datasets, help

## Header

Recommended header contents:
- product logo / name
- global search
- primary nav links
- notifications
- help
- user profile menu

Suggested top nav:
- Workspace
- Explore
- Published Results
- Datasets
- Docs

## Homepage intro

Title:
**Home**

Primary message:
**One platform for contributing, exploring, and publishing data**

Supporting text:
Use the same trusted datasets to manage submissions, perform analysis, and share published findings.

## Primary choice area

The center column should include a “choose your workspace” section with three primary cards.

### Card 1 — Contribute & Build
Audience label:
_For contributors and developers_

Description:
Submit data, manage ingestion workflows, monitor pipeline health, and maintain data quality.

Primary CTA:
**Open workspace**

### Card 2 — Explore & Analyze
Audience label:
_For readers and analysts_

Description:
Search, query, filter, compare, and export shared datasets.

Primary CTA:
**Start exploring**

### Card 3 — Published Results
Audience label:
_For stakeholders and collaborators_

Description:
Browse curated findings, released analyses, and presentation-ready outputs.

Primary CTA:
**View published results**

## Wireframe

```text
┌──────────────────────────────────────────────────────────────────────────────┐
│ Logo   Search datasets, analyses, results...   Workspace Explore Results   │
├──────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│ ┌──────────────────┐  ┌───────────────────────────────────────────────────┐  ┌──────────────────────┐
│ │ Navigation       │  │ Home                                              │  │ Featured             │
│ │                  │  │                                                   │  │                      │
│ │ • Home           │  │ One platform for contributing, exploring,         │  │ Published result     │
│ │ • Workspace      │  │ and publishing data                              │  │ [View result]        │
│ │ • Explore        │  │                                                   │  │                      │
│ │ • Published      │  │ Use the same trusted datasets to manage           │  │ Recent datasets      │
│ │   Results        │  │ ingestion, perform analysis, and share findings.  │  │ • Dataset A          │
│ │ • Datasets       │  │                                                   │  │ • Dataset B          │
│ │ • Saved queries  │  │ ┌───────────────────────────────────────────────┐ │  │ • Release 2026-05    │
│ │ • Reports        │  │ │ Contribute & Build                            │ │  │                      │
│ │ • Docs           │  │ │ For contributors and developers               │ │  │ Announcements        │
│ │                  │  │ │ Submit data, manage pipelines, monitor jobs   │ │  │ • New publication    │
│ │ Recent           │  │ │ [Open workspace]                              │ │  │ • Schema update      │
│ │ • My analysis    │  │ └───────────────────────────────────────────────┘ │  │                      │
│ │ • Cohort import  │  │                                                   │  │                      │
│ │ • Release QA     │  │ ┌───────────────────────────────────────────────┐ │  │                      │
│ │                  │  │ │ Explore & Analyze                             │ │  │                      │
│ │                  │  │ │ For readers and analysts                      │ │  │                      │
│ │                  │  │ │ Query, filter, compare, and export data       │ │  │                      │
│ │                  │  │ │ [Start exploring]                             │ │  │                      │
│ │                  │  │ └───────────────────────────────────────────────┘ │  │                      │
│ │                  │  │                                                   │  │                      │
│ │                  │  │ ┌───────────────────────────────────────────────┐ │  │                      │
│ │                  │  │ │ Published Results                             │ │  │                      │
│ │                  │  │ │ For stakeholders and presentation audiences   │ │  │                      │
│ │                  │  │ │ View curated, presentation-ready findings     │ │  │                      │
│ │                  │  │ │ [View published results]                      │ │  │                      │
│ │                  │  │ └───────────────────────────────────────────────┘ │  │                      │
│ │                  │  │                                                   │  │                      │
│ │                  │  │ Recent activity                                   │  │                      │
│ │                  │  │ • New data release published                      │  │                      │
│ │                  │  │ • 2 pipeline jobs completed                       │  │                      │
│ │                  │  │ • Saved query updated                             │  │                      │
│ └──────────────────┘  └───────────────────────────────────────────────────┘  └──────────────────────┘
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

## Visual style guidance

### Tone
- trustworthy
- operational
- modern but restrained
- data-serious
- familiar to technical users

### UI characteristics
- white cards on light neutral background
- subtle borders
- modest corner radius
- minimal ornamentation
- compact spacing
- concise headings
- strong action buttons
- muted metadata labels

## Why this style works

This style supports both:
- **new users**, who need orientation
- **repeat users**, who need to resume work quickly

It also makes the platform feel:
- coherent
- credible
- active
- practical

rather than promotional or fragmented.

## Key UX principle

Do not make the homepage feel like three separate products sharing a logo.

Instead, make it feel like:
- one platform
- one data foundation
- three paths depending on user intent
