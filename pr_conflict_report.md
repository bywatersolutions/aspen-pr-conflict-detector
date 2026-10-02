# Aspen PR Conflict Report

Found **18** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 8 PRs, 16 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @JonahCWilson, @librarianbryan, @lucasmontoya13, @tomascohen

**Files:** `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java`, `code/web/index.php`, `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php`

**PRs:**
- [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files
- [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box
- [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours
- [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration
- [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes
- [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API
- [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying
- [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L57-L61, L36-L42 | @Chloe070196, @tomascohen |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L283-L289, L41-L48 | @librarianbryan, @tomascohen |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L78-L91, L40-L42 | @Chloe070196, @Jacobomara901 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L99-L105, L41-L56 | @Jacobomara901, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php`, `code/web/index.php` | L40-L81, L58-L64 | @Jacobomara901, @lucasmontoya13 |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L108-L109 | @librarianbryan, @lucasmontoya13 |
| [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L36-L48 | @lucasmontoya13, @tomascohen |
| [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L36-L48 | @lucasmontoya13, @tomascohen |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L40-L48 | @Jacobomara901, @tomascohen |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L40-L56 | @Jacobomara901, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L34-L42 | @Chloe070196, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L56 | @librarianbryan, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L34-L42 | @Chloe070196, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L56 | @librarianbryan, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L42 | @Chloe070196, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying | `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java` | L2166-L2174 | @Jacobomara901, @JonahCWilson |

</details>

**[#4866](https://github.com/Aspen-Discovery/aspen-discovery/pull/4866)** ↔ **[#4870](https://github.com/Aspen-Discovery/aspen-discovery/pull/4870)** — `install/upgrade_26.10.00.sh` (L1-L9), `install/upgrade_debian_26.10.00.sh` (L1-L7) — @JonahCWilson, @lucasmontoya13

**[#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829)** ↔ **[#4875](https://github.com/Aspen-Discovery/aspen-discovery/pull/4875)** — `code/web/release_notes/26.11.00.MD` (L119-L121) — @gmcharlt, @reneeverly

