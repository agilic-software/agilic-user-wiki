# Role & Permission Matrix

*Version v23 • August 18, 2026 • Section 0*

"I'm a [role] — what can I actually do in Agilic?" This page answers that directly, organized by role rather than by feature. It consolidates permission facts scattered across Permissions for People (Section 2), Updating Permissions (Section 4), and the various Owner/Driver notes throughout Sections 6, 7, 8, and 12.

> **See also:** The authoritative source for each fact is linked in that role's section. If this page and a section document ever disagree, the section document wins — update this page to match.

## Every User (baseline, no special role needed)

- See any item or Work Package in the organization, except Secure ones — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Tag any item, follow any item — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Comment anywhere a comment field exists — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Access My View, My Team (if on a team), Global Search — [How to Navigate as a User](/section-1-new-user-orientation/navigate-as-user.md) (Section 1)
- Access your own Private Work Package — [Private Work Packages](/section-4-core-day-to-day-work/private-work-packages.md) (Section 4)

## Assigned or Responsible (on a specific item)

- Everything in "Every User," plus:
- Edit that item — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Add planned hours or log time to that item — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2), [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)

## WP Roster Member (added to a Work Package)

- Everything above, plus, for that specific Work Package:
- Edit items, be Assigned/Responsible on items — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Access that Work Package's Timesheet — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- View that WP's Allocations for yourself, and log your own time — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- Access and edit that WP's Client Portal information, if enabled — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)

## WP Owner/Driver

- Everything above for that Work Package, plus:
- Add / Remove People on the Roster — [Create Work Package / Add People to WP](/section-6-work-package-overview/create-work-package.md) (Section 6)
- Update every updatable field, including Settings, Objective, and WP Status — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- See everyone's Allocations and Time Logging on that WP's Timesheet — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- Update Allocations for people on that WP — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- Mark a Work Package or item as Secure (once implemented) — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Turn on the Client Portal module for this WP (Owner/Driver or Org Admin only) — [Work Package Client Portal Management](/section-6-work-package-overview/work-package-client-portal-management.md) (Section 6)

## Team Roster Member (added to a Team)

- Edit items, as appropriate for items you are Assigned/Responsible for — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Access that Team's Timesheet — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- View all WP's Allocations for yourself, and log your own time — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- View all Team Members' Assigned Work Packages — [My Team Overview](/section-7-my-team-overview/my-team-overview.md) (Section 7)

## Team Owner/Driver

- Everything a regular Team member can do, plus, for that Team:

> **Unconfirmed:** Likely Team Owner/Driver, but not explicitly stated — [My Team Overview](/section-7-my-team-overview/my-team-overview.md) (Section 7) flags this same gap.

- See everyone's Team Member information — [My Team Overview](/section-7-my-team-overview/my-team-overview.md) (Section 7)
- Edit Time Logging for people on the Team — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)

## Billing Admin (single user, org-wide)

- See and manage the Billing and AI Usage tabs in Org Admin — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Update the organization's subscription and payment methods — [Managing Billing & Subscription](/section-3-recurring-admin-tasks/managing-billing.md) (Section 3)
- Must already have Org Admin access to be made Billing Admin — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)

## Standard Permission Type Holders (WP Creator / Team Creator / Org Reporting)

- WP Creator — can create new Work Packages — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Team Creator — can create new Teams — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Org Reporting — can access org-level reporting — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Granted individually per person from Org Admin → Org People List — [Updating Permissions for People](/section-4-core-day-to-day-work/updating-permissions.md) (Section 4)

## Org Admin

- Everything every other role can do, everywhere — acts as Owner/Driver on every Work Package and Team — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)
- Manage People, Roles, Teams, Org Settings — [Adding & Managing People](/section-3-recurring-admin-tasks/adding-managing-people.md) (Section 3), [Org Settings](/section-2-setting-up-your-org/org-settings.md) (Section 2)
- Update anyone's Timesheet up to +/- 12 weeks, logged to Recent Activity (an enhancement, not yet built) — [Timesheets](/section-12-timesheets/timesheets.md) (Section 12)
- An organization can never have 0 Org Admins — [Permissions for People](/section-2-setting-up-your-org/permissions-for-people.md) (Section 2)

## External Client User

- A completely separate access model — never sees the internal application, only the Client Portal — [Client Portal — Getting Started](/section-9-client-portal/client-portal-getting-started.md) (Section 9)
- View milestones and status updates for their project — [Client Portal — Getting Started](/section-9-client-portal/client-portal-getting-started.md) (Section 9) (client-facing docs deliberately avoid the internal term "Stakeholder Report")
  - View shared milestones, RIDE items, and status updates curated by the project team
  - If enabled — comment and/or upload attachments; can always download shared attachments
- Managed by internal team members on the WP inside the Client Portal Module. The client must be added into Client Management in order to be given access to the Client Portal — [Work Package Client Portal Management](/section-6-work-package-overview/work-package-client-portal-management.md) (Section 6), [Managing Client Companies & Contacts](/section-10-client-management/managing-client-companies-contacts.md) (Section 10)

## Pending / Not Yet Implemented

> **Note:** Secure Work Packages and Secure Items are planned but not yet implemented — could be several months out. Everything above referencing Secure content describes the intended behavior, not current functionality.
