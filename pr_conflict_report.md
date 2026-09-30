# Aspen PR Conflict Report

Found **27** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 15 PRs, 27 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @JonahCWilson, @LiYanjun19, @gmcharlt, @librarianbryan, @lucasmontoya13, @reneeverly, @tomascohen

**Files:** `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java`, `code/web/index.php`, `code/web/interface/themes/responsive/js/aspen.js`, `code/web/interface/themes/responsive/js/aspen/admin.js`, `code/web/release_notes/26.10.00.MD`, `code/web/sys/Covers/BookCoverProcessor.php`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php`, `code/web/sys/Storage/StorageSetting.php`

**PRs:**
- [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes
- [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box
- [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours
- [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration
- [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes
- [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API
- [#4847](https://github.com/Aspen-Discovery/aspen-discovery/pull/4847) DIS-2937 Empty Format Field
- [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying
- [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex
- [#4863](https://github.com/Aspen-Discovery/aspen-discovery/pull/4863) DIS-2920: Add Sierra to Last Check In Date and format 
- [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system
- [#4867](https://github.com/Aspen-Discovery/aspen-discovery/pull/4867) DIS-2970: fix: event date covers must display up-to-date data

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L57-L61, L36-L42 | @Chloe070196, @tomascohen |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L283-L289, L41-L48 | @librarianbryan, @tomascohen |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L78-L91, L40-L42 | @Chloe070196, @Jacobomara901 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L99-L105, L41-L56 | @Jacobomara901, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system | `code/web/interface/themes/responsive/js/aspen.js`, `code/web/interface/themes/responsive/js/aspen/admin.js` | L7835-L7841, L1706-L1712 | @Jacobomara901, @lucasmontoya13 |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php`, `code/web/index.php` | L40-L81, L58-L64 | @Jacobomara901, @lucasmontoya13 |
| [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | [#4863](https://github.com/Aspen-Discovery/aspen-discovery/pull/4863) DIS-2920: Add Sierra to Last Check In Date and format  | `code/web/release_notes/26.10.00.MD` | L131-L136 | @LiYanjun19, @lucasmontoya13 |
| [#4847](https://github.com/Aspen-Discovery/aspen-discovery/pull/4847) DIS-2937 Empty Format Field | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD` | L59-L63 | @JonahCWilson, @tomascohen |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4847](https://github.com/Aspen-Discovery/aspen-discovery/pull/4847) DIS-2937 Empty Format Field | `code/web/release_notes/26.10.00.MD` | L59-L61 | @Chloe070196, @JonahCWilson |
| [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.10.00.MD` | L119-L121 | @gmcharlt, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.10.00.MD` | L115-L121 | @lucasmontoya13, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L108-L109 | @librarianbryan, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | `code/web/release_notes/26.10.00.MD` | L119-L121 | @gmcharlt, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | `code/web/release_notes/26.10.00.MD` | L115-L116 | @lucasmontoya13, @reneeverly |
| [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | [#4867](https://github.com/Aspen-Discovery/aspen-discovery/pull/4867) DIS-2970: fix: event date covers must display up-to-date data | `code/web/sys/Covers/BookCoverProcessor.php` | L1936-L1942 | @Chloe070196, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system | `code/web/interface/themes/responsive/js/aspen.js` | L17879-L17881 | @librarianbryan, @lucasmontoya13 |
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
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes | `code/web/sys/Storage/StorageSetting.php` | L9-L15 | @JonahCWilson, @lucasmontoya13 |

</details>

