# Aspen PR Conflict Report

Found **15** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 13 PRs, 15 conflict(s)

**Authors:** @LiYanjun19, @gmcharlt, @kidclamp, @kylemhall, @mdnoble73, @samyoung-maker

**Files:** `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php`

**PRs:**
- [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374
- [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page
- [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex 
- [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include
- [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents
- [#4801](https://github.com/Aspen-Discovery/aspen-discovery/pull/4801) DIS-2858 EBSCOhost don't link to all facets from combined results
- [#4804](https://github.com/Aspen-Discovery/aspen-discovery/pull/4804) DIS-2849 - Display libraries and locations in object list
- [#4809](https://github.com/Aspen-Discovery/aspen-discovery/pull/4809) DIS-2535 - re-enable Grouped Works V3
- [#4810](https://github.com/Aspen-Discovery/aspen-discovery/pull/4810) DIS-2815 Move Audience Indexing to Child Documents

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4810](https://github.com/Aspen-Discovery/aspen-discovery/pull/4810) DIS-2815 Move Audience Indexing to Child Documents | `code/web/release_notes/26.09.00.MD` | L102-L108 | @gmcharlt, @mdnoble73 |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4809](https://github.com/Aspen-Discovery/aspen-discovery/pull/4809) DIS-2535 - re-enable Grouped Works V3 | `code/web/release_notes/26.09.00.MD` | L102-L107 | @gmcharlt, @mdnoble73 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4804](https://github.com/Aspen-Discovery/aspen-discovery/pull/4804) DIS-2849 - Display libraries and locations in object list | `code/web/release_notes/26.09.00.MD` | L116-L122 | @kylemhall, @mdnoble73 |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4804](https://github.com/Aspen-Discovery/aspen-discovery/pull/4804) DIS-2849 - Display libraries and locations in object list | `code/web/release_notes/26.09.00.MD` | L108-L108 | @gmcharlt, @mdnoble73 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4801](https://github.com/Aspen-Discovery/aspen-discovery/pull/4801) DIS-2858 EBSCOhost don't link to all facets from combined results | `code/web/release_notes/26.09.00.MD` | L120-L122 | @kylemhall, @mdnoble73 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents | `code/web/release_notes/26.09.00.MD` | L34-L40 | @LiYanjun19, @samyoung-maker |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L34-L40 | @LiYanjun19, @samyoung-maker |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex  | `code/web/release_notes/26.09.00.MD` | L40-L40 | @LiYanjun19, @samyoung-maker |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L56 | @kidclamp, @kylemhall |

</details>

