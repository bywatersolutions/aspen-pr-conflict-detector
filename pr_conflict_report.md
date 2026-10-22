# Aspen PR Conflict Report

Found **14** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 9 PRs, 9 conflict(s)

**Authors:** @Jacobomara901, @JonahCWilson, @b-lawlor, @gmcharlt, @lucasmontoya13, @reneeverly, @tomascohen

**Files:** `code/web/release_notes/26.11.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.11.00.php`

**PRs:**
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex
- [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4876](https://github.com/Aspen-Discovery/aspen-discovery/pull/4876) DIS-3016: Evergreen: improvements to support for preferred names
- [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes
- [#4882](https://github.com/Aspen-Discovery/aspen-discovery/pull/4882) DIS-2897: Add an S3-compatible/CDN storage backend for uploaded files
- [#4883](https://github.com/Aspen-Discovery/aspen-discovery/pull/4883) DIS-3049: Koha export branch update fails when repeatable_holidays table is missing
- [#4885](https://github.com/Aspen-Discovery/aspen-discovery/pull/4885) DIS-3084:  Fix for False-Positive 2FA Error Message
- [#4891](https://github.com/Aspen-Discovery/aspen-discovery/pull/4891) DIS-3091: Use event location mapping when filtering the events calendar

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | [#4883](https://github.com/Aspen-Discovery/aspen-discovery/pull/4883) DIS-3049: Koha export branch update fails when repeatable_holidays table is missing | `code/web/release_notes/26.11.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.11.00.php` | L283-L285, L2-L8 | @Jacobomara901, @tomascohen |
| [#4876](https://github.com/Aspen-Discovery/aspen-discovery/pull/4876) DIS-3016: Evergreen: improvements to support for preferred names | [#4891](https://github.com/Aspen-Discovery/aspen-discovery/pull/4891) DIS-3091: Use event location mapping when filtering the events calendar | `code/web/release_notes/26.11.00.MD` | L49-L53 | @b-lawlor, @gmcharlt |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4891](https://github.com/Aspen-Discovery/aspen-discovery/pull/4891) DIS-3091: Use event location mapping when filtering the events calendar | `code/web/release_notes/26.11.00.MD` | L269-L274 | @b-lawlor, @reneeverly |
| [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes | [#4885](https://github.com/Aspen-Discovery/aspen-discovery/pull/4885) DIS-3084:  Fix for False-Positive 2FA Error Message | `code/web/release_notes/26.11.00.MD` | L249-L250 | @JonahCWilson, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4882](https://github.com/Aspen-Discovery/aspen-discovery/pull/4882) DIS-2897: Add an S3-compatible/CDN storage backend for uploaded files | `code/web/release_notes/26.11.00.MD` | L115-L116 | @lucasmontoya13, @reneeverly |
| [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.11.00.MD` | L119-L121 | @gmcharlt, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.11.00.MD` | L115-L121 | @lucasmontoya13, @reneeverly |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | `code/web/release_notes/26.11.00.MD` | L119-L121 | @gmcharlt, @reneeverly |
| [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | [#4882](https://github.com/Aspen-Discovery/aspen-discovery/pull/4882) DIS-2897: Add an S3-compatible/CDN storage backend for uploaded files | `code/web/sys/DBMaintenance/version_updates/26.11.00.php` | L36-L48 | @lucasmontoya13, @tomascohen |

</details>

### Cluster 2 — 4 PRs, 4 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @JonahCWilson, @librarianbryan

**Files:** `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java`, `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php`

**PRs:**
- [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box
- [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours
- [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration
- [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L78-L91, L40-L42 | @Chloe070196, @Jacobomara901 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L99-L105, L41-L56 | @Jacobomara901, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying | `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java` | L2166-L2174 | @Jacobomara901, @JonahCWilson |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L42 | @Chloe070196, @librarianbryan |

</details>

**[#4866](https://github.com/Aspen-Discovery/aspen-discovery/pull/4866)** ↔ **[#4870](https://github.com/Aspen-Discovery/aspen-discovery/pull/4870)** — `install/upgrade_26.10.00.sh` (L1-L9), `install/upgrade_debian_26.10.00.sh` (L1-L7) — @JonahCWilson, @lucasmontoya13

