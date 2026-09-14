# Work Package Settings

*Version v13 • August 31, 2026 • Section 6: Inside a Work Package • For: WP Owner/Driver, Org Admin*

WP-level configurations for the Work Package, Work Item Type, Item, Reporting, Labels, and Module Access sub-tabs.

> **See also:** For org-wide defaults that feed these settings, see [Org Settings](/section-2-setting-up-your-org/org-settings.md) (Section 2).

## Getting There

Inside a Work Package, go to the Settings tab.

![Settings tab navigation](media/06f-001.png)

## Work Package

WP State, WP Health, and WP Phase settings for this specific Work Package.

- **WP State** — the Work Package's current lifecycle state (e.g. Active, On Hold, Closed).
  - You can adjust the color of the background and the color of the text.
  - You can define if a WP State is in a System State of Open or Closed.
  - Upon saving the WP into this state, you can determine if there is an animation or not.
  - You can save as a new template or update the current template.

![WP State settings](media/06f-002.png)

- **WP Health** — a manually-set indicator (e.g. On Track, At Risk, Off Track) shown wherever this Work Package is referenced.
  - You can adjust the color of the background and the color of the text.
  - You can select the image that is used for WP Health on some reports.
  - You can save as a new template or update the current template.

![WP Health settings](media/06f-003.png)

- **WP Phase** — customize which Phases are available on this Work Package. Phases operate independently from the Gantt, PERT, and WBS — a Phase is a field on each item, so multiple Phases can run simultaneously (e.g. Control Phase alongside Execution).

![WP Phase settings](media/06f-004.png)

> **Note:** Phases are a field assigned to individual Items. As a result, WP Phases are available on Kanban boards as columns and can be grouped by in various reports.

## Work Item Type

Select who is Owner/Driver of a specific Work Item Type within this Work Package. These Work Item Types for this WP will then show up on the Owner/Driver's My Work → Owner/Driver section.

![Work Item Type ownership settings](media/06f-005.png)

## Item

Item creation defaults and item state settings.

- **New Item Creation Defaults** — you can set all Items, when they are created, to be marked as Planned (useful before the effort officially begins) or Not Planned (useful after the effort has officially kicked off and anything "new" is in addition to what was originally planned). Note: Planned or Not Planned is a checkbox on each individual Standard Item. RIDE Items do not have this option.
- **Item State** — customize the list of states an item can move through in this Work Package, and each state's background and text color, used throughout Kanban boards, reports, and item detail views.
  - You can define if an Item State is in a System State of Open or Closed.
  - You can define if an Item State is "Accomplished" (this is especially important for the Agile Scrum Module if you are using it). Note: for an Item to be "Accomplished" requires it to be in a Closed System State.
  - Upon saving the WP into this state, you can determine if there is an animation or not.

![Item State settings](media/06f-006.png)

## Reporting

Options for how certain fields are displayed in the WP Header.

- **Work Package Header** — controls which fields display in the header shown at the top of this Work Package, wherever it's referenced.
  - The default settings are to use:
    - Planned WP Start, Planned WP Complete
    - Anticipated Start, Anticipated Complete

![WP Header reporting settings](media/06f-007.png)

## Labels

This Work Package can see and use all global labels, and can add labels/categories dedicated to just this WP.

- Simple Labels — a single field. You can assign any number of these.
- UnBound Labels — a two-part label. You can assign any number of these.
- Bound Labels — also two-part, but you can only assign one of each type (e.g. Priority: High or Priority: Low, not both).
- All labels are available as columns in the Kanban boards.
- All Work Package-level labels can be modified here. You can adjust the names, label color, and text color.

Note: if there is a globe next to the display name, these were created at the org level and can not be modified here. You also can not duplicate org-level labels.

Note: if you change a label after it has been added to items, you may need to go back and re-apply those labels to the items.

![Labels settings](media/06f-008.png)

> **See also:** These are the same three label types configured org-wide in [Org Settings](/section-2-setting-up-your-org/org-settings.md) (Section 2).

## Module Access

Turn optional features on or off for this Work Package, if they're available and turned on within your organization — for example, Client Portal.

![Module Access settings](media/06f-009.png)

> **See also:** Turning on Client Portal here is the Work-Package-level step; it must also be enabled org-wide first — see Client Portal Module (Section 9) and [Org Settings](/section-2-setting-up-your-org/org-settings.md) (Section 2). Once on, manage it in [Work Package Client Portal Management](/section-6-work-package-overview/work-package-client-portal-management.md) (Section 6).
