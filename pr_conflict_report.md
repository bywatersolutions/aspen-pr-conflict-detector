# Aspen PR Conflict Report

Found **34** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 18 PRs, 34 conflict(s)

**Authors:** @JonahCWilson, @K-Alette, @LiYanjun19, @catsoup11789, @gmcharlt, @kidclamp, @kylemhall, @mdnoble73, @samyoung-maker

**Files:** `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php`

**PRs:**
- [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374
- [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching
- [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page
- [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon
- [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex 
- [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include
- [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings
- [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization
- [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents
- [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes
- [#4799](https://github.com/Aspen-Discovery/aspen-discovery/pull/4799) DIS-2852 Fix debug message when renewing non-renewable Symphony items
- [#4800](https://github.com/Aspen-Discovery/aspen-discovery/pull/4800) DIS-2879 - Fix Debug error showing explore more with CloudSource
- [#4801](https://github.com/Aspen-Discovery/aspen-discovery/pull/4801) DIS-2858 EBSCOhost don't link to all facets from combined results
- [#4803](https://github.com/Aspen-Discovery/aspen-discovery/pull/4803) DIS-2808: Process supplemental MFHD export for Evergreen

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | [#4803](https://github.com/Aspen-Discovery/aspen-discovery/pull/4803) DIS-2808: Process supplemental MFHD export for Evergreen | `code/web/release_notes/26.09.00.MD` | L29-L29 | @K-Alette, @catsoup11789 |
| [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents | [#4803](https://github.com/Aspen-Discovery/aspen-discovery/pull/4803) DIS-2808: Process supplemental MFHD export for Evergreen | `code/web/release_notes/26.09.00.MD` | L34-L35 | @K-Alette, @LiYanjun19 |
| [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | [#4803](https://github.com/Aspen-Discovery/aspen-discovery/pull/4803) DIS-2808: Process supplemental MFHD export for Evergreen | `code/web/release_notes/26.09.00.MD` | L32-L35 | @K-Alette, @LiYanjun19 |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4803](https://github.com/Aspen-Discovery/aspen-discovery/pull/4803) DIS-2808: Process supplemental MFHD export for Evergreen | `code/web/release_notes/26.09.00.MD` | L32-L35 | @K-Alette, @LiYanjun19 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4803](https://github.com/Aspen-Discovery/aspen-discovery/pull/4803) DIS-2808: Process supplemental MFHD export for Evergreen | `code/web/release_notes/26.09.00.MD` | L34-L35 | @K-Alette, @samyoung-maker |
| [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon | [#4801](https://github.com/Aspen-Discovery/aspen-discovery/pull/4801) DIS-2858 EBSCOhost don't link to all facets from combined results | `code/web/release_notes/26.09.00.MD` | L120-L124 | @K-Alette, @mdnoble73 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4801](https://github.com/Aspen-Discovery/aspen-discovery/pull/4801) DIS-2858 EBSCOhost don't link to all facets from combined results | `code/web/release_notes/26.09.00.MD` | L120-L122 | @kylemhall, @mdnoble73 |
| [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | [#4800](https://github.com/Aspen-Discovery/aspen-discovery/pull/4800) DIS-2879 - Fix Debug error showing explore more with CloudSource | `code/web/release_notes/26.09.00.MD` | L156-L161 | @K-Alette, @mdnoble73 |
| [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | [#4799](https://github.com/Aspen-Discovery/aspen-discovery/pull/4799) DIS-2852 Fix debug message when renewing non-renewable Symphony items | `code/web/release_notes/26.09.00.MD` | L163-L170 | @K-Alette, @mdnoble73 |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/release_notes/26.09.00.MD` | L102-L107 | @catsoup11789, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/release_notes/26.09.00.MD` | L15-L21 | @JonahCWilson, @catsoup11789 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents | `code/web/release_notes/26.09.00.MD` | L34-L40 | @LiYanjun19, @samyoung-maker |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/release_notes/26.09.00.MD` | L34-L38 | @LiYanjun19, @samyoung-maker |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L34-L40 | @LiYanjun19, @samyoung-maker |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex  | `code/web/release_notes/26.09.00.MD` | L40-L40 | @LiYanjun19, @samyoung-maker |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon | `code/web/release_notes/26.09.00.MD` | L118-L122 | @K-Alette, @kylemhall |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L34 | @LiYanjun19, @catsoup11789 |
| [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L35 | @LiYanjun19, @catsoup11789 |
| [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L20-L47, L97-L121 | @K-Alette, @catsoup11789 |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L34 | @LiYanjun19, @catsoup11789 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L96 | @catsoup11789, @kylemhall |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4798](https://github.com/Aspen-Discovery/aspen-discovery/pull/4798) DIS-2711: Add Aspen LiDA Themes | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L56 | @catsoup11789, @kidclamp |
| [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | [#4795](https://github.com/Aspen-Discovery/aspen-discovery/pull/4795) DIS-2878: Add support for Force Reindex to retrieve data from eContents | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L34 | @K-Alette, @LiYanjun19 |
| [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L35 | @K-Alette, @LiYanjun19 |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L34 | @K-Alette, @LiYanjun19 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L47 | @K-Alette, @kylemhall |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L47 | @K-Alette, @kidclamp |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L56 | @kidclamp, @kylemhall |

</details>

