# Terminology Index & Dictionary

*Version v23 • August 18, 2026 • Section 0*

This is a living index and dictionary of Agilic-specific terms used throughout the training documentation. Each entry gives a short definition and points to the section where it's covered in full detail.

> **Note:** Updated as of Sections 1–4, 6, 7, 8, 9, 10, 11, 12, 13, and 14. Section 5 (AI Agent) is not yet built into this index, so AI Assistant terminology below reflects only what's referenced elsewhere, not a dedicated pass.

## A–D

| Term | Definition | Covered In |
|---|---|---|
| **4D Framework** | Agilic's structure for a Work Package's four standard Work Item Types: Define, Do Work, Document, and Deliver (plus RIDE as a fifth, related type). | Section 4, Section 6 |
| **Accomplishments** | A personal achievements-tracking screen under My Profile. | Section 8 |
| **AI Summary** | An AI-generated, executive-level deep-dive analysis of a Work Package, retained for reference and audit. | Section 6 |
| **AI Usage** | The Billing Admin-only area tracking token usage and cost, both live and historical. | Section 3 |
| **Assigned** | 1) A tab within My List showing items assigned to you. 2) A separate, unused scaffold screen elsewhere in the app with no real logic — not a real feature. | Section 8 |
| **Baseline Planned** | A snapshot of an item's plan at a specific moment. When marked Baseline Planned, an item's current Planned Start, Planned Finish, and Duration are copied and stored as Baseline Start, Baseline Finish, and Baseline Duration, for later comparison against what actually happens. Can be applied item-by-item or in bulk from an Active WBS. | Section 11 |
| **Billing Admin** | A permission flag narrower than general Org Admin access — controls visibility into the Billing and AI Usage tabs. Only 1 person can hold this at a time, and they must already have Org Admin access. Set in Org Admin → Billing Admin. | Section 1, Section 2 |
| **Client Company** | An external organization your organization works with via Client Portal, managed under Client Management. | Section 10 |
| **Client Management** | The label shown in the left-hand navigation menu for the area where Org Admins manage Client Companies and Client Contacts. Only appears when Client Portal is enabled for the organization. | Section 10 |
| **Client Contact** | An individual external user ("guest user") belonging to a Client Company. | Section 10 |
| **Client Portal** | The simplified, external-facing experience for client users, distinct from the internal application. | Section 9, Section 10 |
| **Comment Triskele** | An icon that opens a quick Comment/Status editor without opening the full item. Behavior differs by location: on an item's row in list view, it offers Comment, new Status, and Add RIDE; on a Kanban card, it offers only Comment and new Status (no Add RIDE option there). | Section 4, Section 13 |
| **Decision Management** | A feature on a work item (especially RIDE items) for creating Decision Requests and formally tracking how they were resolved — who decided, when, and why. | Section 4, Section 6 |
| **Define** | One of the four standard Work Item Types — what's needed to make sure Deliver items are correct (requirements/acceptance criteria). | Section 4, Section 6 |
| **Deliver** | One of the four standard Work Item Types — what needs to be delivered to achieve the Work Package's objective. The default/landing type. | Section 4, Section 6 |
| **Do Work** | One of the four standard Work Item Types — the actual task/execution tracking. | Section 4, Section 6 |

## E–M

| Term | Definition | Covered In |
|---|---|---|
| **Hours Summary** | An item's comparison of planned hours vs. hours actually logged. Only people Assigned to the item can add planned hours or log time. | Section 4 |
| **Forward Pass / Backward Pass** | PERT Chart calculations that automatically adjust a Work Package's schedule — Forward Pass recalculates based on Start Dates, Backward Pass recalculates based on End Dates. | Section 11 |
| **Impacted Item** | An item directly affected by a specific RIDE item, linked via the RIDE item's Relationships. Distinct from an Associated item, which is just a breadcrumb with no direct impact. | Section 4 |
| **Labels** | Org-wide or per-Work Package categories/tags, of three types: Simple (single field, unlimited), UnBound (two-part, unlimited), and Bound (two-part, only one per type — e.g. Priority:High or Priority:Low, not both). | Section 2 |
| **Item Hours** | A report showing logged time hours broken down by item, at either the Work Package or personal (My View) level. | Section 6, Section 8, Section 12 |
| **Kanban** | A visual board of items, organized into columns. Agilic has five distinct Kanban boards — WP Kanban (one Work Package), Team Kanban (one team), My Kanban (just you), Org Kanban (Items), and Org Kanban (Work Packages) — see Kanban Boards for how they differ. | Section 13 |
| **Milestone** | A key date/checkpoint tracked on a Work Package's Summary tab. | Section 6 |
| **Mitigation** | The section of a RIDE item where you document the Mitigation Plan and Completion Notes. | Section 4 |
| **Module Access** | Setting (org-wide or per-WP) that turns optional features, such as Client Portal, on or off. | Section 2, Section 6 |

## N–R

| Term | Definition | Covered In |
|---|---|---|
| **InActive (User)** | The status given to a person who's leaving the organization but whose account can't be fully deleted (because they've made updates in the system). Prevents login and removes them from the license count, without erasing their history. | Section 4 |
| **Objective** | The stated purpose of a Work Package, set at creation and shown on the Summary tab. | Section 4, Section 6 |
| **Org Admin Access** | A permission flag determining whether someone can see and use the Org Admin area at all. Automatically granted to the Primary Contact when an organization is first created; an organization can never drop below 1 person with this access. | Section 1, Section 2 |
| **Owner/Driver** | The lead role(s) on a Work Package or Team, shown prominently on Summary and Team Summary views. | Section 6, Section 7 |
| **Planning** | Standard project planning, done once you have your team assembled and are ready to plan out the schedule: Task Relationships, PERT Chart, Gantt Chart, Work Breakdown Structure (WBS), and Baseline Planned. Distinct from Pre-Planning, which comes before this stage. | Section 6, Section 11 |
| **Pre-Planning** | Setting up a Work Package to succeed before you have your full team or are ready to plan out the schedule: defining the Work Package itself (Objective, Scope, Value if Completed, Impact if Not Done), Scope Change Control, WP Sub-Tasks, Attachments, Role Placeholders, and Allocations. Distinct from Planning, which is the scheduling stage that follows. | Section 6, Section 12 |
| **PERT Chart** | Program Evaluation and Review Technique chart — visualizes task sequencing and timing dependencies in Planning. | Section 6 |
| **Private Work Package** | A dedicated Work Package automatically given to every user, with a PRVT-prefixed WP ID assigned when the user is added to Agilic. Functions like a full Work Package (the user is its default Owner/Driver) but is completely private — no one else in the organization can see it — and supports custom Work Item Type naming for personal use. | Section 4, Section 8 |
| **RIDE** | Risks, Issues, Dependencies, and Escalations — unforeseen work tracked with a built-in decision-making process. | Section 4, Section 6 |
| **Role Placeholder** | A role that exists in the system but isn't yet filled by a real person — useful for planning ahead for a hire. Can be defined org-wide or by an individual Work Package. | Section 1, Section 2, Section 3, Section 11 |
| **Roster** | The membership list for a Work Package or a Team — who has visibility/access to that specific WP or Team. | Section 4, Section 6, Section 7 |

## S–Z

| Term | Definition | Covered In |
|---|---|---|
| **Secure Item** | A single item marked private within an otherwise non-secure Work Package — visible only to the WP's Owner/Driver, that item's Responsible/Assigned people, and Org Admins. Only the Owner/Driver or an Org Admin can mark an item Secure. Excluded from Kanban boards, searches, and reports for unauthorized users. **Not yet implemented.** | Section 1, Section 2 |
| **Secure Work Package** | A Work Package whose entire contents are hidden from everyone except its Owner/Driver and roster. Only the WP ID and title stay visible to others. Only the Owner/Driver or an Org Admin can mark a WP Secure. **Not yet implemented.** | Section 1, Section 2 |
| **Scope Change Control** | A dedicated section on Work Package Management for tracking scope changes after the Work Package is underway. | Section 6 |
| **Segment** | The older term for what's now called a Work Item Type — Define, Do Work, Document, Deliver, or RIDE. Still used in a few places (e.g. Segment Item Subtask); "Work Item Type" is the current preferred term. | Section 4, Section 6, Section 14 |
| **Stakeholder Report** | The confirmed name for what was previously called "Work Package Report" (at the single-WP level) and "Stakeholder Summary" (at the My View/My Team rollup level) — now the same name at every level. Shows a Work Package's state and status, plus escalated RIDE items and milestones. | Section 1, Section 2, Section 6, Section 7, Section 8 |
| **Standard Item** | Any work item that isn't RIDE — one living in Define, Do Work, Document, or Deliver. All Standard Items share the same item detail structure (Basic Information, Hours Summary, State vs. Status, Subtasks, Attachments, Relationships, Comments). | Section 4 |
| **Standard Permission Types** | Four org-level capabilities granted per person from Org Admin → Org People List: WP Creator, Team Creator, Org Reporting, and Admin (full Org Admin access). | Section 1, Section 2 |
| **State vs. Status** | Two distinct fields on an item: State is its current workflow stage; Status is a point-in-time update with a timestamp and who posted it (shows "---" if none yet). | Section 4 |
| **Success Matrix** | A Planning tool for tracking work against defined success criteria. | Section 6 |
| **Team** | A standing group of people, separate from any single Work Package, with its own purpose and roster. | Section 3, Section 7 |
| **Team Code** | A required, exactly-4-character identifier for a Team, set in Team Admin. | Section 3, Section 7 |
| **Timesheet** | Time-tracking with two functions: Allocation Management (Owner/Driver assigns a Roster resource an overall allocation with a start/end, for Pre-Planning) and Logging Time (anyone on the Roster logs time directly against the WP). Source of truth lives on the Work Package; My View and Team Timesheets are personal/team-scoped views of that same data. | Section 12 |
| **Wiki** | The renamed successor to a Work Package's "Documents" tab — file/document storage for the Work Package. Distinct from Attachments and External Links on Work Package Management, which is scoped to guidance documentation for defining the WP. | Section 1 |
| **Work Breakdown Structure (WBS)** | The default Planning view — breaks a Work Package down into its component pieces. | Section 6 |
| **WP Phases** | A field on each item, independent of the Gantt, PERT, and WBS tools. Since it's a field, Phases can appear on Kanban boards and be used for report groupings. Multiple Phases can run simultaneously. | Section 11 |
| **WP Sub-Tasks** | A checklist-style breakdown of work at the Work Package Management level, similar to Item Subtasks but scoped to the whole WP rather than a single item. Can be converted into full Items. | Section 11 |
| **Work Item Type** | The current term for what a Work Package's work is organized into: Define, Do Work, Document, Deliver, or RIDE. Supersedes "Segment" in most current documentation. | Section 1, Section 4 |
| **Work Package (WP)** | The core unit of work in Agilic — anything from a large multi-team project to a single task. | Section 4, Section 6 |
