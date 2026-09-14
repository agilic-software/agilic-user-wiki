# Timesheets

*Version v9 • August 30, 2026 • Section 12: Time Tracking • For: WP Roster members*

> **Note:** Some details below — especially exact time-entry fields and approval steps — could not be fully confirmed from the application alone. Verify with your dev team before treating this as final.

Agilic Timesheets have two different functions: Allocation Management, to help with Pre-Planning by reserving capacity ahead of time, and Logging Time, to record actual hours worked.

## Allocation Management

Before work begins, the Owner/Driver can add a resource to the Roster with an overall Allocation — an Allocation Start, Allocation End, and total hours — to reserve capacity ahead of actual time logging. Allocation Hours, Start, and End can only be adjusted on the Work Package.

> **See also:** Allocations are set up as part of Pre-Planning — see [Pre-Planning Capabilities](/section-6-work-package-overview/pre-planning-capabilities.md) (Section 6).

Timesheets source of truth is located on individual Work Packages; however, users can see (and log time) on My View and Team Views. The Owner/Driver of the Team View can view and edit Timesheet Logged Hours on the Team View.

## Work Package Timesheet — Logging Time

Found inside a specific Work Package's Timesheet tab. This is where time gets logged against the work happening in that WP.

![Work Package Timesheet](media/12-001.png)

> **Note:** Not every user automatically has access to a Work Package's Timesheet — it depends on a permission check. If you don't see this tab, check with your Work Package's Owner or Driver. You must be on the WP Roster.

Only the WP Owner/Driver (and Org Admin) can see everyone's Allocations and time logging. Individuals can see Allocations and log time for themselves.

> **Note:** Only the Owner/Driver of the WP (or Org Admin) can update Allocations for a person.

**Step 1: Open the Timesheet**

From inside the Work Package, go to the Timesheet tab.

**Step 2: Log Your Time**

Record time against this Work Package. You can edit your time logged for this week and +/- 1 week. Beyond +/- 1 week, you will need to ask the Owner/Driver of the WP or your Team Owner/Driver to edit for you.

> **Note:** The Owner/Driver of the WP (or Org Admin) can edit logged time +/- 3 weeks.

![Log Time entry](media/12-002.png)

> **Tip:** Log time as you go rather than trying to reconstruct a full week at once — it's easier to be accurate, and item-level hours feed directly into that Work Package's Item Hours report.

## My Timesheet

From My View, go to the Timesheet. This is your personal timesheet — it will show you all the Work Package Timesheets you have access to. You can see your Allocations (if used) and log time directly to those Work Packages. You can edit your time logged for this week and +/- 1 week. Beyond +/- 1 week, you will need to ask the Owner/Driver of the WP or your Team Owner/Driver to edit for you.

![My Timesheet](media/12-003.png)

Use My Timesheet when you want to see your own logged time across every Work Package you're part of, rather than one WP at a time.

## Team Timesheet

From Team View, go to the Team Timesheet. This shows your personal timesheet as well as what your team members' Work Packages are. This will not show you your team members' Allocations or time logging information.

If you are the Owner/Driver of the Team (or an Org Admin), you will see all team member Allocations and can see/edit logged time for each team member.

> **Note:** The Owner/Driver of the Team (or Org Admin on the Team View) can edit logged time +/- 2 weeks.

![Team Timesheet](media/12-004.png)

## Org Admin Timesheet View

> **Not yet available:** This capability is on the roadmap but not currently available in the live product.

Org Admins can update Timesheets +/- 12 weeks. Every such update must be captured in Recent Activity (audit trail).

## Where Logged Time Data Shows Up

- Work Package → Reports → Item Hours — hours logged, broken down by item, for that Work Package
- Team View → Reports → Item Hours — your team's hours, across every Work Package
- My View → Reports → Item Hours — your own logged hours, across every Work Package
- Work Package → Timesheets — hours logged vs. Allocations, for that Work Package
- Team View → Timesheets — your own hours logged vs. Allocations, plus your team assignments, across every Work Package
- My View → Timesheets — your own hours logged vs. Allocations, across every Work Package

> **See also:** Item Hours reporting is covered in Item Hours (Section 15).
