# 05 — Open Questions

This document captures unresolved questions for product, UX, engineering, and stakeholder review.

## 1. Primary audience priority

Question:
Which audience should the homepage prioritize after login?

Options:
- contributors/developers
- analysts/readers
- presentation viewers/stakeholders
- role-based default landing by user permissions

Why it matters:
This affects default landing behavior, homepage emphasis, and prominence of modules.

## 2. Naming validation

Question:
Are the labels **Workspace**, **Explore**, and **Published Results** aligned with current stakeholder vocabulary?

Why it matters:
Naming should be intuitive to users while remaining acceptable to internal teams.

Follow-up:
If these labels are not acceptable, identify alternatives that are:
- clear
- task-based
- durable
- easy to distinguish

## 3. Is Home a neutral landing page or a role-specific dashboard?

Question:
Should the homepage be:
- a shared “chooser” page for all users, or
- a personalized dashboard with the three options embedded within it?

Why it matters:
This changes the density, layout, and balance between orientation and productivity.

## 4. Published results scope

Question:
What qualifies as a “published result”?

Possible interpretations:
- analyst-approved outputs
- publicly shareable results
- internal presentation views
- release snapshots
- report pages
- narrative dashboards

Why it matters:
This affects taxonomy, governance, and user expectations.

## 5. Transition model between Explore and Published Results

Question:
How does an analysis move from exploratory work to published output?

Questions to clarify:
- Is publishing explicit?
- Is there an approval workflow?
- Are snapshots immutable?
- Can published results link back to source queries or datasets?

Why it matters:
This relationship should be visible in the UX.

## 6. Shared dataset consistency

Question:
What metadata and terminology are shared across all three sections?

Need alignment on:
- dataset names
- version labels
- release dates
- status language
- permissions model
- object taxonomy

Why it matters:
Inconsistencies here will make the platform feel fragmented.

## 7. Permissions and visibility

Question:
Will all users see all three areas, or only the areas they have access to?

Options:
- show all areas, but gate restricted ones
- show only permitted areas
- show all areas with explanatory lock states

Why it matters:
This significantly affects navigation and onboarding.

## 8. Homepage right-rail content

Question:
What contextual modules should appear in the right rail?

Candidates:
- featured published result
- recent datasets
- announcements
- saved items
- help/docs
- release notes
- recent activity summary

Why it matters:
Right-rail content helps the page feel useful rather than purely navigational.

## 9. Search scope

Question:
Should the top search search across:
- datasets
- analyses
- published results
- documentation
- users/projects
- all of the above

Why it matters:
Search behavior strongly influences the platform’s mental model.

## 10. GitHub-style fidelity

Question:
How closely should the UI resemble GitHub’s logged-in homepage?

Options:
- lightly inspired
- structurally similar
- strongly derivative in layout patterns only
- very close in utility feel but adapted to domain

Why it matters:
This affects user familiarity, branding distinctiveness, and design system choices.

## Recommended next step

Use these questions in a cross-functional review to decide:
- naming
- landing behavior
- publishing flow
- permissions behavior
- homepage content priorities

After that, move to:
1. low-fidelity wireframes
2. content validation
3. clickable prototype
