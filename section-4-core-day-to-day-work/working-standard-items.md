# Working Standard Items

*Version v18 • August 31, 2026 • Section 4: Core Day-to-Day Work • For: WP Roster members*

This guide covers everything you can capture on a single item, whether it lives in Define, Document, Do Work, or Deliver. All four Work Item Types share the same item detail structure — learn it once, and it applies everywhere.

> **See also:** For an overview of what each Work Item Type tab is for, see [Work Item Types](/section-4-core-day-to-day-work/work-item-types.md) (Section 4). For what's different about RIDE items specifically, see [Working RIDE Items](/section-4-core-day-to-day-work/working-ride-items.md) (Section 4).

## Getting There

From My Work, Team Work, or any Work Items tabs, select an item's ID (a clickable link) to open its detail — this opens a right-hand side panel with everything below, which also allows you to fully expand the item to a full page.

![Item detail panel](media/04d-001.png)

## What's in an Item's Detail View

**Basic Information**

The item's title, description, and core identifying details.

- **A Note about State vs. Status**
  - In Agilic we split what most tools call Status out into two distinct but related fields:

- State — the item's current stage in its workflow. The options for Item State are configurable in the Work Package Settings and can also be standardized for the organization in Org Admin Settings.

![Item State options](media/04d-002.png)

- Status — a point-in-time free-form update about the item, with a timestamp and who made it. Shows "---" if no status has been posted yet.
  - Note that images are not allowed in a Status — only text.
  - All Statuses are saved as Comments in the Comment section of the item.
  - You are able to tag people directly in any comment, including a status — this will make a link to the item appear on the user's My View in the Tagged section.

![Status field](media/04d-003.png)

**Assignees and Responsible**

Set who is Assigned (can be multiple people) and who is Responsible (only one person can be Responsible) for the item. This is how items show up on My View in the Assigned section.

Note: only people who are on the WP Roster can be Assigned or made Responsible for an item within that Work Package.

![Assigned and Responsible fields](media/04d-004.png)

**Milestones**

Any item (or RIDE) can be marked as a Milestone. A Milestone is a single moment in time. Selecting this will:

- Force the item to only recognize the Due Date and Target Date (it will ignore the Start Date)
- Add the options to:
  - Show On Roadmap — impacts some reporting options
  - Mark as Critical / Needs Escalation — only RIDEs and Milestones have this option. This option feeds the Stakeholder Report.

![Milestone options](media/04d-005.png)

**Baseline Planned and Manual Percent Complete / Manual State**

- Baseline Planned is used to capture your planned target dates and durations in a secure field, so you always can refer to what the original plan was, regardless of how many things changed or got added.
- Manual Percent Complete has no bearing on any fields besides Manual Status. This is intended to be available for Earned Value calculations. For visual ease we have placed the current Item State next to the Manual Status for easy comparison, even though they have no technical dependency on each other. Manual Status is based entirely on Manual Percent Complete.
  - 0% = Not Started
  - >0% and <100% = In Progress
  - 100% Complete = Complete

![Baseline and Manual Percent Complete](media/04d-006.png)

**Hours Summary (Planned vs. Logged)**

A comparison of planned hours against hours actually logged against the item, so you can see at a glance whether work is tracking to estimate.

![Hours Summary](media/04d-007.png)

- Selecting "View Details" will take you to the Estimation / Recorded Hours editing screen.

![Estimation/Recorded Hours screen](media/04d-008.png)

- **Note:** Only people Assigned to the item can add planned hours or log hours to the item.

> **See also:** When an item is marked Baseline Planned, this section also shows its Baseline Start, Baseline Finish, and Baseline Duration — see Work Package Planning Tools (Section 11).

**Subtasks**

Break the item down into smaller subtasks without creating entirely separate items.

- You can use subtasks as a checklist of things to do.

![Subtasks checklist](media/04d-009.png)

- You can also take a subtask and automatically create a new item from it.

![Create item from subtask](media/04d-010.png)

**Attachments**

Files or links attached directly to this item.

![Attachments](media/04d-011.png)

Note: file size is limited to 95MB.

**External Links**

You must connect an external drive in order to make use of this field. If you do not have an external drive connected, this is what you will see:

![No external drive connected](media/04d-012.png)

To connect an external drive, go to My Profile → Connectors and log in to your drive.

> **See also:** For connecting an external drive, see Personal Connectors in My View Overview (Section 8).

Once connected, you can then add links directly to your Drive by clicking the Add from Drive button.

![Add from Drive](media/04d-013.png)

**Relationships**

How this item connects to others:

- Associated — a breadcrumb link to similar content, with no schedule dependency
- Predecessor — items that come before this one, forming an actual schedule dependency that feeds into project timelines and reports like the PERT Chart, Gantt Chart, and Critical Path
- Successor — items that come after this one, forming an actual schedule dependency that feeds into project timelines and reports like the PERT Chart, Gantt Chart, and Critical Path
- RIDE — RIDE items that specifically impact this item can be added as a relationship here. This makes following up on blockers much easier.

![Relationships section](media/04d-014.png)

**Comments**

A running discussion thread on the item.

![Comments thread](media/04d-015.png)

> **Tip:** The Comment Triskele icon on an item's row (in the list view, without opening the full detail panel) lets you quickly add a comment, post a new status, or add a RIDE item directly associated with this item.

## Quick Reference

| Section | What it captures |
|---|---|
| Basic Information | Title, description, core details |
| Hours Summary | Planned hours vs. logged hours |
| State vs. Status | Workflow stage vs. point-in-time updates |
| Subtasks | Smaller breakdowns of the item |
| Attachments / External Links | Files and links on this item |
| Relationships | Associated, Predecessor, Successor links |
| Comments | Discussion thread |

## Related Tasks

RIDE items include everything above, plus Risk, Mitigation, and Decision Management processes specific to them — see [Working RIDE Items](/section-4-core-day-to-day-work/working-ride-items.md) (Section 4).
