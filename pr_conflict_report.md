# Aspen PR Conflict Report

Found **13** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 7 PRs, 9 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @JonahCWilson, @librarianbryan, @lucasmontoya13

**Files:** `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java`, `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php`

**PRs:**
- [#4390](https://github.com/Aspen-Discovery/aspen-discovery/pull/4390) DIS-2508: db transaction for native events registration
- [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files
- [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box
- [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours
- [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration
- [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying
- [#4881](https://github.com/Aspen-Discovery/aspen-discovery/pull/4881) DIS-3026: Fit generated cover text on 3:4 canvases

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L78-L91, L40-L42 | @Chloe070196, @Jacobomara901 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L99-L105, L41-L56 | @Jacobomara901, @librarianbryan |
| [#4390](https://github.com/Aspen-Discovery/aspen-discovery/pull/4390) DIS-2508: db transaction for native events registration | [#4881](https://github.com/Aspen-Discovery/aspen-discovery/pull/4881) DIS-3026: Fit generated cover text on 3:4 canvases | `code/web/release_notes/26.10.00.MD` | L173-L175 | @Chloe070196, @lucasmontoya13 |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L108-L109 | @librarianbryan, @lucasmontoya13 |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4881](https://github.com/Aspen-Discovery/aspen-discovery/pull/4881) DIS-3026: Fit generated cover text on 3:4 canvases | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L40-L47 | @Jacobomara901, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4881](https://github.com/Aspen-Discovery/aspen-discovery/pull/4881) DIS-3026: Fit generated cover text on 3:4 canvases | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L34-L42 | @Chloe070196, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4881](https://github.com/Aspen-Discovery/aspen-discovery/pull/4881) DIS-3026: Fit generated cover text on 3:4 canvases | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L47 | @librarianbryan, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L42 | @Chloe070196, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying | `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java` | L2166-L2174 | @Jacobomara901, @JonahCWilson |

</details>

### Cluster 2 — 3 PRs, 3 conflict(s)

**Authors:** @gmcharlt, @lucasmontoya13, @reneeverly

**Files:** `code/web/release_notes/26.11.00.MD`

**PRs:**
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.11.00.MD` | L119-L121 | @gmcharlt, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4878](https://github.com/Aspen-Discovery/aspen-discovery/pull/4878) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.11.00.MD` | L115-L121 | @lucasmontoya13, @reneeverly |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | `code/web/release_notes/26.11.00.MD` | L119-L121 | @gmcharlt, @reneeverly |

</details>

**[#4866](https://github.com/Aspen-Discovery/aspen-discovery/pull/4866)** ↔ **[#4870](https://github.com/Aspen-Discovery/aspen-discovery/pull/4870)** — `install/upgrade_26.10.00.sh` (L1-L9), `install/upgrade_debian_26.10.00.sh` (L1-L7) — @JonahCWilson, @lucasmontoya13

