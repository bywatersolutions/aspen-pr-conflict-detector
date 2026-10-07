# Aspen PR Conflict Report

Found **10** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 5 PRs, 5 conflict(s)

**Authors:** @gmcharlt, @lucasmontoya13, @reneeverly, @tomascohen

**Files:** `code/web/release_notes/26.11.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.11.00.php`

**PRs:**
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex
- [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes
- [#4882](https://github.com/Aspen-Discovery/aspen-discovery/pull/4882) DIS-2897: Add an S3-compatible/CDN storage backend for uploaded files

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
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

