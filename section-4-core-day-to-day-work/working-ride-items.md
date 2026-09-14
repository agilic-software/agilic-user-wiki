# Working RIDE Items

*Version v18 • August 31, 2026 • Section 4: Core Day-to-Day Work • For: WP Roster members*

RIDE stands for Risks, Issues, Dependencies, and Escalations — the unforeseen work that comes up through a project's lifecycle. RIDE items are one of the Work Item Types, and their item detail includes everything a standard item has, plus RIDE-specific processes for managing risk and decision making.

RIDE items work primarily like Standard Items, but have a few differences.

> **See also:** RIDE items include everything covered in [Working Standard Items](/section-4-core-day-to-day-work/working-standard-items.md) (Basic Information, Hours Summary, State vs. Status, Subtasks, Attachments, Relationships, Comments) — this guide only covers what's different.

## Getting There

Inside a Work Package, go to the RIDE tab — one of the Work Item Type tabs, alongside Define, Do Work, Document, and Deliver.

![RIDE tab](media/04b-001.png)

## Creating a RIDE Item

It does not matter what you are dealing with — Risk, Issue, Dependency or Escalation — you typically need to follow the same process:

- Document the item
- Link it to relevant information using Relationships
- If you use RISK processes, add Likelihood, Impact, and Impact Date as needed. These are all located in the Mitigation Management section and show up on many different screens that show RIDE items.
- Request a Decision when needed. This is found in the Decision Management section of the RIDE.

**Step 1: Create the RIDE Item**

Adding a new RIDE item is similar to adding a Standard item. Add a New RIDE and enter the initial information of what this is and why it's important. Create and go to Detail in order to see all the sections of the RIDE.

![Create a new RIDE item](media/04b-002.png)

**Step 2: Assign Responsibility**

Set who's Responsible for the item and who it's Assigned to, so it doesn't sit unowned.

## What's Different About a RIDE Item

> **Note:** RIDE items have Risk, Mitigation, and Decision Making processes built in — on top of everything a standard item has.

## Working an Existing RIDE Item

**Step 3: Link to Impacted Items**

Use Relationship links to directly relate a RIDE item to other items:

- Impacted Items are items directly impacted by this RIDE item.
- Associated Items are breadcrumbs to help see what other items may have relevant information but are not directly impacted by this RIDE.

> **Tip:** Using Relationships makes it easy to find related information and to also see how many items are affected by a specific Risk, Issue, Dependency, or Escalation.

![Impacted Items relationship](media/04b-003.png)

Note: the items in Impacted Items show you which items are all impacted by this specific RIDE.

**Step 4: Mitigation**

The Mitigation section of the RIDE gives you a place to document what the Mitigation Plan is, as well as a section for Completion Notes.

- Likelihood: can be None, Low, Medium or High
- Impact: can be None, Low, Medium or High
- Impact Date: is the expected date the impact could occur

![Mitigation section](media/04b-004.png)

**Step 5: Track the Decision**

Use Decision Management to formally track what decision(s) are needed and how those decision requests were resolved — especially useful for Escalations, where leadership needs a clear record of what was decided, when, by whom, and why.

- You can add a Decision Request specifying what the decision needed is.
- Once the Decision Request is created, you can manage the decision within the RIDE and set up auto-notifications for those people involved in the decision, as well as stakeholders to notify when the decision request is resolved.
- There could be multiple decisions needed from a single RIDE. You can add multiple Decision Requests so the entire history can be seen in one location.

![Decision Management](media/04b-005.png)

## Escalating Internally without Using Decision Management

Every RIDE item can be marked for Escalation.

![Escalation flag](media/04b-006.png)

This data field is pulled into all relevant Kanban Boards and makes the RIDE visible on the Stakeholder Report.

> **See also:** For the different Kanban boards across Agilic, see Kanban Boards (Section 13).

## Escalating to a Client

If this Work Package has an external Client Portal, an admin can escalate specific RIDE items so the client sees them — without exposing your full internal RIDE list. This is managed from Client Portal Management → Control → Client RIDE Management, not from the RIDE tab itself.

On the Client Portal → Control → RIDE Management, find the RIDE you want to share with your client and mark it as "Show On Client Portal." It does not have to be marked as Critical / Needs Escalation.

![Client Portal RIDE Management](media/04b-007.png)

## Keeping an Eye on RIDE Items

- The Work Package Management landing page has a dedicated RIDE Management section showing what needs attention.

![RIDE Management on WP landing page](media/04b-008.png)

- The Stakeholder Report shows the WP's escalated RIDE items and milestones alongside overall state and status.

![Stakeholder Report RIDE section](media/04b-009.png)

- WP Reporting → Charts → RIDE Charts includes the RIDE Heat Map, Decision Chart, and Mitigation Chart.

![RIDE Charts](media/04b-010.png)

- Work Items → RIDE shows all RIDE items for this Work Package.

![RIDE tab list view](media/04b-011.png)

- My View and Team Views have similar capabilities, filtered by who is Assigned / Reporting on the RIDE items.
