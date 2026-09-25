# Aspen PR Conflict Report

Found **43** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 19 PRs, 38 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @JonahCWilson, @LiYanjun19, @gmcharlt, @kylemhall, @librarianbryan, @lucasmontoya13, @reneeverly, @tomascohen

**Files:** `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java`, `code/web/index.php`, `code/web/interface/themes/responsive/js/aspen.js`, `code/web/interface/themes/responsive/js/aspen/admin.js`, `code/web/release_notes/26.10.00.MD`, `code/web/services/WebBuilder/AJAX.php`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php`, `code/web/sys/Storage/StorageSetting.php`

**PRs:**
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows
- [#4825](https://github.com/Aspen-Discovery/aspen-discovery/pull/4825) DIS-2894: Upgrade Docker image to Debian trixie, OpenJDK 25, and native PHP 8.4
- [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files
- [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row
- [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS
- [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes
- [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box
- [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours
- [#4839](https://github.com/Aspen-Discovery/aspen-discovery/pull/4839) DIS-2926 - Internationalisation: 'Noon' and 'Midnight' must be translatable
- [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration
- [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes
- [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API
- [#4847](https://github.com/Aspen-Discovery/aspen-discovery/pull/4847) DIS-2937 Empty Format Field
- [#4853](https://github.com/Aspen-Discovery/aspen-discovery/pull/4853) DIS-2950: Fix Web builder Markdown image uploads
- [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying
- [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex
- [#4861](https://github.com/Aspen-Discovery/aspen-discovery/pull/4861) DIS-2921: Fix property search for ILS Indexing Profiles
- [#4863](https://github.com/Aspen-Discovery/aspen-discovery/pull/4863) DIS-2920: Add Sierra to Last Check In Date and format 
- [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system | `code/web/interface/themes/responsive/js/aspen.js`, `code/web/interface/themes/responsive/js/aspen/admin.js` | L7835-L7841, L1706-L1712 | @Jacobomara901, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L57-L61, L36-L42 | @Chloe070196, @tomascohen |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L283-L289, L41-L48 | @librarianbryan, @tomascohen |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L78-L91, L40-L42 | @Chloe070196, @Jacobomara901 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L99-L105, L41-L56 | @Jacobomara901, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php`, `code/web/index.php` | L40-L81, L58-L64 | @Jacobomara901, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system | `code/web/interface/themes/responsive/js/aspen.js` | L17871-L17877 | @librarianbryan, @lucasmontoya13 |
| [#4839](https://github.com/Aspen-Discovery/aspen-discovery/pull/4839) DIS-2926 - Internationalisation: 'Noon' and 'Midnight' must be translatable | [#4864](https://github.com/Aspen-Discovery/aspen-discovery/pull/4864) DIS-2979: Migrate remaining hardcoded JS strings to the __() translation system | `code/web/release_notes/26.10.00.MD` | L200-L206 | @Chloe070196, @lucasmontoya13 |
| [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | [#4863](https://github.com/Aspen-Discovery/aspen-discovery/pull/4863) DIS-2920: Add Sierra to Last Check In Date and format  | `code/web/release_notes/26.10.00.MD` | L131-L136 | @LiYanjun19, @lucasmontoya13 |
| [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | [#4861](https://github.com/Aspen-Discovery/aspen-discovery/pull/4861) DIS-2921: Fix property search for ILS Indexing Profiles | `code/web/release_notes/26.10.00.MD` | L131-L136 | @LiYanjun19, @lucasmontoya13 |
| [#4847](https://github.com/Aspen-Discovery/aspen-discovery/pull/4847) DIS-2937 Empty Format Field | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/release_notes/26.10.00.MD` | L59-L63 | @JonahCWilson, @tomascohen |
| [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | [#4853](https://github.com/Aspen-Discovery/aspen-discovery/pull/4853) DIS-2950: Fix Web builder Markdown image uploads | `code/web/release_notes/26.10.00.MD` | L250-L250 | @LiYanjun19, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4847](https://github.com/Aspen-Discovery/aspen-discovery/pull/4847) DIS-2937 Empty Format Field | `code/web/release_notes/26.10.00.MD` | L59-L61 | @Chloe070196, @JonahCWilson |
| [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.10.00.MD` | L119-L121 | @gmcharlt, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/release_notes/26.10.00.MD` | L115-L121 | @lucasmontoya13, @reneeverly |
| [#4825](https://github.com/Aspen-Discovery/aspen-discovery/pull/4825) DIS-2894: Upgrade Docker image to Debian trixie, OpenJDK 25, and native PHP 8.4 | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/release_notes/26.10.00.MD` | L103-L105 | @Jacobomara901, @lucasmontoya13 |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L108-L109 | @librarianbryan, @lucasmontoya13 |
| [#4825](https://github.com/Aspen-Discovery/aspen-discovery/pull/4825) DIS-2894: Upgrade Docker image to Debian trixie, OpenJDK 25, and native PHP 8.4 | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/release_notes/26.10.00.MD` | L103-L109 | @librarianbryan, @lucasmontoya13 |
| [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | [#4830](https://github.com/Aspen-Discovery/aspen-discovery/pull/4830) DIS-2833: New cronjob to batch delete patrons that were removed from the ILS | `code/web/release_notes/26.10.00.MD` | L119-L121 | @gmcharlt, @reneeverly |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4829](https://github.com/Aspen-Discovery/aspen-discovery/pull/4829) DIS-2895: Add CSS classes for groupedStatus to horizontal format variations row | `code/web/release_notes/26.10.00.MD` | L115-L116 | @lucasmontoya13, @reneeverly |
| [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L36-L48 | @lucasmontoya13, @tomascohen |
| [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L36-L48 | @lucasmontoya13, @tomascohen |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L40-L48 | @Jacobomara901, @tomascohen |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows | [#4855](https://github.com/Aspen-Discovery/aspen-discovery/pull/4855) DIS-2964 Hide 856 URLs from logged-out patrons via a configurable regex | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L48 | @kylemhall, @tomascohen |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L40-L56 | @Jacobomara901, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L34-L42 | @Chloe070196, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L56 | @librarianbryan, @lucasmontoya13 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows | [#4843](https://github.com/Aspen-Discovery/aspen-discovery/pull/4843) DIS-2924: On-demand DSpace 7+ Open Archives cover resolution via REST API | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L56 | @kylemhall, @lucasmontoya13 |
| [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L34-L42 | @Chloe070196, @lucasmontoya13 |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L56 | @librarianbryan, @lucasmontoya13 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows | [#4842](https://github.com/Aspen-Discovery/aspen-discovery/pull/4842) DIS-2929: Header and footer customization options for themes | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L81 | @kylemhall, @lucasmontoya13 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows | [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L127 | @Jacobomara901, @kylemhall |
| [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L42 | @Chloe070196, @librarianbryan |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows | [#4834](https://github.com/Aspen-Discovery/aspen-discovery/pull/4834) DIS-2604: allow 24 hour time format for native events and library hours | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L42 | @Chloe070196, @kylemhall |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and creating duplicate daily rows | [#4832](https://github.com/Aspen-Discovery/aspen-discovery/pull/4832) DIS-2459 Simplified search box | `code/web/sys/DBMaintenance/version_updates/26.10.00.php` | L41-L56 | @kylemhall, @librarianbryan |
| [#4841](https://github.com/Aspen-Discovery/aspen-discovery/pull/4841) DIS-894: Omeka integration | [#4854](https://github.com/Aspen-Discovery/aspen-discovery/pull/4854) DIS-2860: Grouped works indexer batched querying | `code/reindexer/src/org/aspen_discovery/reindexer/GroupedWorkIndexer.java` | L2166-L2174 | @Jacobomara901, @JonahCWilson |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4853](https://github.com/Aspen-Discovery/aspen-discovery/pull/4853) DIS-2950: Fix Web builder Markdown image uploads | `code/web/services/WebBuilder/AJAX.php` | L578-L587 | @LiYanjun19, @lucasmontoya13 |
| [#4828](https://github.com/Aspen-Discovery/aspen-discovery/pull/4828) DIS-2897: Add S3/CDN storage driver for uploaded images and files | [#4831](https://github.com/Aspen-Discovery/aspen-discovery/pull/4831) DIS-2898:  Redundancy baseline fixes | `code/web/sys/Storage/StorageSetting.php` | L9-L15 | @JonahCWilson, @lucasmontoya13 |

</details>

### Cluster 2 — 4 PRs, 3 conflict(s)

**Authors:** @Jacobomara901, @catsoup11789, @gmcharlt

**Files:** `code/web/release_notes/26.09.00.MD`

**PRs:**
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability
- [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates
- [#4846](https://github.com/Aspen-Discovery/aspen-discovery/pull/4846) DIS-2790: Update updateHoldPickupPreferences for Polaris (User API)

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | [#4846](https://github.com/Aspen-Discovery/aspen-discovery/pull/4846) DIS-2790: Update updateHoldPickupPreferences for Polaris (User API) | `code/web/release_notes/26.09.00.MD` | L122-L122 | @Jacobomara901, @catsoup11789 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4821](https://github.com/Aspen-Discovery/aspen-discovery/pull/4821) DIS-2888: Tests run db updates | `code/web/release_notes/26.09.00.MD` | L205-L207 | @Jacobomara901, @gmcharlt |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4820](https://github.com/Aspen-Discovery/aspen-discovery/pull/4820) DIS-2608: Unit test portability | `code/web/release_notes/26.09.00.MD` | L141-L147 | @Jacobomara901, @gmcharlt |

</details>

**[#4845](https://github.com/Aspen-Discovery/aspen-discovery/pull/4845)** ↔ **[#4849](https://github.com/Aspen-Discovery/aspen-discovery/pull/4849)** — `code/web/release_notes/26.10.00.MD` (L162-L168) — @Chloe070196, @lucasmontoya13

**[#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690)** ↔ **[#4838](https://github.com/Aspen-Discovery/aspen-discovery/pull/4838)** — `code/web/release_notes/26.09.00.MD` (L15-L21) — @JonahCWilson, @catsoup11789

