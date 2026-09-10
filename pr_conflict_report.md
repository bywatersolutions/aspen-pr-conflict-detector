# Aspen PR Conflict Report

Found **16** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 9 PRs, 11 conflict(s)

**Authors:** @Jacobomara901, @K-Alette, @LiYanjun19, @gmcharlt, @kylemhall, @lucasmontoya13

**Files:** `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php`

**PRs:**
- [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci
- [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class 
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include
- [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability
- [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates
- [#4826](https://github.com/Aspen-Discovery/aspen-discovery/pull/4826) DIS-2893: Fix updateDatabase.php Smarty init order
- [#4833](https://github.com/Aspen-Discovery/aspen-discovery/pull/4833) DIS-2657: QA Changes

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4833](https://github.com/Aspen-Discovery/aspen-discovery/pull/4833) DIS-2657: QA Changes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L212-L239 | @K-Alette, @kylemhall |
| [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | [#4826](https://github.com/Aspen-Discovery/aspen-discovery/pull/4826) DIS-2893: Fix updateDatabase.php Smarty init order | `code/web/release_notes/26.09.00.MD` | L132-L132 | @Jacobomara901, @lucasmontoya13 |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L32-L32 | @Jacobomara901, @LiYanjun19 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L205-L205 | @Jacobomara901, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L205-L207 | @Jacobomara901, @gmcharlt |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L32-L33 | @Jacobomara901, @LiYanjun19 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L172-L178 | @Jacobomara901, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L141-L147 | @Jacobomara901, @gmcharlt |
| [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class  | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L32 | @Jacobomara901, @LiYanjun19 |
| [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L33 | @Jacobomara901, @LiYanjun19 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L202-L205 | @gmcharlt, @kylemhall |

</details>

### Cluster 2 — 6 PRs, 5 conflict(s)

**Authors:** @JonahCWilson, @gmcharlt, @librarianbryan, @lucasmontoya13, @reneeverly

**Files:** `code/web/release_notes/26.10.00.MD`, `code/web/sys/Storage/StorageSetting.php`

**PRs:**
- [#4825](https://github.com/Aspen-Discovery/aspen-discovery/pull/4825) DIS-2894: Upgrade Docker image to Debian trixie, OpenJDK 25, and native PHP 8.4
- [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes
- [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L108-L109 | @librarianbryan, @lucasmontoya13 |
| [#4825](https://github.com/Aspen-Discovery/aspen-discovery/pull/4825) DIS-2894: Upgrade Docker image to Debian trixie, OpenJDK 25, and native PHP 8.4 | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L103-L109 | @librarianbryan, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | `code/web/release_notes/26.10.00.MD` | L119-L121 | @gmcharlt, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | `code/web/release_notes/26.10.00.MD` | L115-L116 | @lucasmontoya13, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes | `code/web/sys/Storage/StorageSetting.php` | L9-L15 | @JonahCWilson, @lucasmontoya13 |

</details>

