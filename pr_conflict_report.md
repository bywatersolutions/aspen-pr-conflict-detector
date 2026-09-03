# Aspen PR Conflict Report

Found **13** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 11 PRs, 13 conflict(s)

**Authors:** @Jacobomara901, @JonahCWilson, @LiYanjun19, @gmcharlt, @kidclamp, @kylemhall

**Files:** `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php`, `code/web/sys/SystemVariables.php`

**PRs:**
- [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374
- [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci
- [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class 
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex 
- [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include
- [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents
- [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes
- [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability
- [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L32-L32 | @Jacobomara901, @LiYanjun19 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L205-L207 | @Jacobomara901, @gmcharlt |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L32-L33 | @Jacobomara901, @LiYanjun19 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L122-L122, L141-L146 | @Jacobomara901, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L141-L147 | @Jacobomara901, @gmcharlt |
| [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/release_notes/26.09.00.MD` | L34-L40 | @JonahCWilson, @LiYanjun19 |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/release_notes/26.09.00.MD` | L34-L40 | @JonahCWilson, @LiYanjun19 |
| [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex  | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/release_notes/26.09.00.MD` | L40-L40 | @JonahCWilson, @LiYanjun19 |
| [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class  | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L32 | @Jacobomara901, @LiYanjun19 |
| [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L33 | @Jacobomara901, @LiYanjun19 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L141-L146 | @gmcharlt, @kylemhall |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/sys/SystemVariables.php` | L71-L74 | @JonahCWilson, @kidclamp |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L56 | @kidclamp, @kylemhall |

</details>

