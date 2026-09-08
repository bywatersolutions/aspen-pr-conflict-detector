# Aspen PR Conflict Report

Found **17** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 9 PRs, 14 conflict(s)

**Authors:** @Jacobomara901, @JonahCWilson, @LiYanjun19, @gmcharlt, @kylemhall, @lucasmontoya13

**Files:** `code/web/release_notes/26.09.00.MD`

**PRs:**
- [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci
- [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class 
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include
- [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes
- [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability
- [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates
- [#4826](https://github.com/Aspen-Discovery/aspen-discovery/pull/4826) DIS-2893: Fix updateDatabase.php Smarty init order

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | [#4826](https://github.com/Aspen-Discovery/aspen-discovery/pull/4826) DIS-2893: Fix updateDatabase.php Smarty init order | `code/web/release_notes/26.09.00.MD` | L132-L132 | @Jacobomara901, @lucasmontoya13 |
| [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L27-L32 | @Jacobomara901, @JonahCWilson |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L32-L32 | @Jacobomara901, @LiYanjun19 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L205-L207 | @Jacobomara901, @gmcharlt |
| [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L27-L33 | @Jacobomara901, @JonahCWilson |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L32-L33 | @Jacobomara901, @LiYanjun19 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L172-L178 | @Jacobomara901, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L141-L147 | @Jacobomara901, @gmcharlt |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/release_notes/26.09.00.MD` | L32-L33 | @JonahCWilson, @LiYanjun19 |
| [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class  | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/release_notes/26.09.00.MD` | L27-L32 | @Jacobomara901, @JonahCWilson |
| [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci | [#4815](https://github.com/Aspen-Discovery/aspen-discovery/pull/4815) DIS-2887 Baseline bugfixes | `code/web/release_notes/26.09.00.MD` | L27-L33 | @Jacobomara901, @JonahCWilson |
| [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class  | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L32 | @Jacobomara901, @LiYanjun19 |
| [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L33 | @Jacobomara901, @LiYanjun19 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L202-L204 | @gmcharlt, @kylemhall |

</details>

### Cluster 2 — 4 PRs, 3 conflict(s)

**Authors:** @JonahCWilson, @gmcharlt, @lucasmontoya13, @reneeverly

**Files:** `code/web/release_notes/26.10.00.MD`, `code/web/sys/Storage/StorageSetting.php`

**PRs:**
- [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | `code/web/release_notes/26.10.00.MD` | L119-L121 | @gmcharlt, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | `code/web/release_notes/26.10.00.MD` | L115-L116 | @lucasmontoya13, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes | `code/web/sys/Storage/StorageSetting.php` | L9-L15 | @JonahCWilson, @lucasmontoya13 |

</details>

