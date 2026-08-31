# Aspen PR Conflict Report

Found **56** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 22 PRs, 51 conflict(s)

**Authors:** @Chloe070196, @JonahCWilson, @K-Alette, @LiYanjun19, @gmcharlt, @kidclamp, @kylemhall, @lathomas64, @lucasmontoya13, @samyoung-maker, @stephenrwicks

**Files:** `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php`

**PRs:**
- [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method
- [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374
- [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit
- [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page
- [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling
- [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters
- [#4768](https://github.com/Aspen-Discovery/aspen-discovery/pull/4768) DIS-1199: Allow for on-order records without items to display (Symphony)
- [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon
- [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search
- [#4773](https://github.com/Aspen-Discovery/aspen-discovery/pull/4773) DIS-2822: Link publishers in search results
- [#4780](https://github.com/Aspen-Discovery/aspen-discovery/pull/4780) DIS-2649: Avoid matching names from two separate people when doing author searches
- [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup
- [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex 
- [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include
- [#4785](https://github.com/Aspen-Discovery/aspen-discovery/pull/4785) DIS-2817 Fix rounding error with Stripe payments
- [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings
- [#4790](https://github.com/Aspen-Discovery/aspen-discovery/pull/4790) DIS-2877: Fix Hoopla v2 SingleWork Extraction
- [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L116-L119, L41-L46, L65-L89 | @K-Alette, @kylemhall |
| [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/release_notes/26.09.00.MD` | L32-L38 | @JonahCWilson, @LiYanjun19 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/release_notes/26.09.00.MD` | L34-L38 | @LiYanjun19, @samyoung-maker |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/release_notes/26.09.00.MD` | L36-L38 | @Chloe070196, @LiYanjun19 |
| [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | [#4790](https://github.com/Aspen-Discovery/aspen-discovery/pull/4790) DIS-2877: Fix Hoopla v2 SingleWork Extraction | `code/web/release_notes/26.09.00.MD` | L32-L38 | @JonahCWilson, @LiYanjun19 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4790](https://github.com/Aspen-Discovery/aspen-discovery/pull/4790) DIS-2877: Fix Hoopla v2 SingleWork Extraction | `code/web/release_notes/26.09.00.MD` | L34-L38 | @LiYanjun19, @samyoung-maker |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4790](https://github.com/Aspen-Discovery/aspen-discovery/pull/4790) DIS-2877: Fix Hoopla v2 SingleWork Extraction | `code/web/release_notes/26.09.00.MD` | L36-L38 | @Chloe070196, @LiYanjun19 |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/release_notes/26.09.00.MD` | L118-L119 | @JonahCWilson, @K-Alette |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/release_notes/26.09.00.MD` | L104-L108 | @K-Alette, @gmcharlt |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/release_notes/26.09.00.MD` | L106-L113 | @K-Alette, @lathomas64 |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4785](https://github.com/Aspen-Discovery/aspen-discovery/pull/4785) DIS-2817 Fix rounding error with Stripe payments | `code/web/release_notes/26.09.00.MD` | L91-L95 | @gmcharlt, @stephenrwicks |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4785](https://github.com/Aspen-Discovery/aspen-discovery/pull/4785) DIS-2817 Fix rounding error with Stripe payments | `code/web/release_notes/26.09.00.MD` | L91-L95 | @gmcharlt, @stephenrwicks |
| [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L32-L38 | @JonahCWilson, @LiYanjun19 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L34-L40 | @LiYanjun19, @samyoung-maker |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/release_notes/26.09.00.MD` | L36-L42 | @Chloe070196, @LiYanjun19 |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex  | `code/web/release_notes/26.09.00.MD` | L40-L40 | @LiYanjun19, @samyoung-maker |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4783](https://github.com/Aspen-Discovery/aspen-discovery/pull/4783) DIS-1202: Fix OverDrive Products to Reindex  | `code/web/release_notes/26.09.00.MD` | L40-L42 | @Chloe070196, @LiYanjun19 |
| [#4780](https://github.com/Aspen-Discovery/aspen-discovery/pull/4780) DIS-2649: Avoid matching names from two separate people when doing author searches | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L120-L124 | @K-Alette, @lucasmontoya13 |
| [#4773](https://github.com/Aspen-Discovery/aspen-discovery/pull/4773) DIS-2822: Link publishers in search results | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L120-L124 | @K-Alette, @lucasmontoya13 |
| [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L120-L125 | @K-Alette, @lucasmontoya13 |
| [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L120-L124 | @K-Alette, @lucasmontoya13 |
| [#4768](https://github.com/Aspen-Discovery/aspen-discovery/pull/4768) DIS-1199: Allow for on-order records without items to display (Symphony) | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L124-L126 | @K-Alette, @lucasmontoya13 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L120-L122 | @kylemhall, @lucasmontoya13 |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4782](https://github.com/Aspen-Discovery/aspen-discovery/pull/4782) DIS 2867: Remove redundant background process check from backend startup | `code/web/release_notes/26.09.00.MD` | L120-L124 | @JonahCWilson, @lucasmontoya13 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4780](https://github.com/Aspen-Discovery/aspen-discovery/pull/4780) DIS-2649: Avoid matching names from two separate people when doing author searches | `code/web/release_notes/26.09.00.MD` | L118-L122 | @K-Alette, @kylemhall |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4780](https://github.com/Aspen-Discovery/aspen-discovery/pull/4780) DIS-2649: Avoid matching names from two separate people when doing author searches | `code/web/release_notes/26.09.00.MD` | L118-L124 | @JonahCWilson, @K-Alette |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4773](https://github.com/Aspen-Discovery/aspen-discovery/pull/4773) DIS-2822: Link publishers in search results | `code/web/release_notes/26.09.00.MD` | L118-L122 | @K-Alette, @kylemhall |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4773](https://github.com/Aspen-Discovery/aspen-discovery/pull/4773) DIS-2822: Link publishers in search results | `code/web/release_notes/26.09.00.MD` | L118-L124 | @JonahCWilson, @K-Alette |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search | `code/web/release_notes/26.09.00.MD` | L116-L122 | @K-Alette, @kylemhall |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search | `code/web/release_notes/26.09.00.MD` | L118-L124 | @JonahCWilson, @K-Alette |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search | `code/web/release_notes/26.09.00.MD` | L111-L113 | @K-Alette, @lathomas64 |
| [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon | `code/web/release_notes/26.09.00.MD` | L118-L122 | @K-Alette, @kylemhall |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4769](https://github.com/Aspen-Discovery/aspen-discovery/pull/4769) DIS-2826: Searching for call numbers with a colon | `code/web/release_notes/26.09.00.MD` | L118-L124 | @JonahCWilson, @K-Alette |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4768](https://github.com/Aspen-Discovery/aspen-discovery/pull/4768) DIS-1199: Allow for on-order records without items to display (Symphony) | `code/web/release_notes/26.09.00.MD` | L124-L124 | @JonahCWilson, @K-Alette |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | `code/web/release_notes/26.09.00.MD` | L34-L38 | @JonahCWilson, @samyoung-maker |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | `code/web/release_notes/26.09.00.MD` | L36-L38 | @Chloe070196, @JonahCWilson |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L118-L122 | @JonahCWilson, @kylemhall |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L36-L40 | @Chloe070196, @samyoung-maker |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L106-L108 | @gmcharlt, @lathomas64 |
| [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L35 | @K-Alette, @LiYanjun19 |
| [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search | [#4793](https://github.com/Aspen-Discovery/aspen-discovery/pull/4793) DIS-2792: Hoopla Indexer Optimization | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L35 | @K-Alette, @LiYanjun19 |
| [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L34 | @K-Alette, @LiYanjun19 |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4786](https://github.com/Aspen-Discovery/aspen-discovery/pull/4786) DIS-2657: Allow text sizes to be adjusted in Theme settings | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L46 | @K-Alette, @kidclamp |
| [#4772](https://github.com/Aspen-Discovery/aspen-discovery/pull/4772) DIS-2821: Allow Publisher to be removed from the Keyword search | [#4784](https://github.com/Aspen-Discovery/aspen-discovery/pull/4784) DIS-2784: Add Hoopla Records to Include | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L22-L34 | @K-Alette, @LiYanjun19 |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L56 | @kidclamp, @kylemhall |

</details>

### Cluster 2 — 4 PRs, 5 conflict(s)

**Authors:** @JonahCWilson, @LiYanjun19, @stephenrwicks

**Files:** `code/web/release_notes/26.09.00.MD`

**PRs:**
- [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching
- [#4788](https://github.com/Aspen-Discovery/aspen-discovery/pull/4788) DIS-2855: Enable Card Renewal dropdown disabling the wrong option
- [#4789](https://github.com/Aspen-Discovery/aspen-discovery/pull/4789) DIS-2853: "Aspen Events to Include" label
- [#4791](https://github.com/Aspen-Discovery/aspen-discovery/pull/4791) DIS-2668: Add checkbox list to Custom Form

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4789](https://github.com/Aspen-Discovery/aspen-discovery/pull/4789) DIS-2853: "Aspen Events to Include" label | [#4791](https://github.com/Aspen-Discovery/aspen-discovery/pull/4791) DIS-2668: Add checkbox list to Custom Form | `code/web/release_notes/26.09.00.MD` | L69-L74 | @LiYanjun19, @stephenrwicks |
| [#4788](https://github.com/Aspen-Discovery/aspen-discovery/pull/4788) DIS-2855: Enable Card Renewal dropdown disabling the wrong option | [#4791](https://github.com/Aspen-Discovery/aspen-discovery/pull/4791) DIS-2668: Add checkbox list to Custom Form | `code/web/release_notes/26.09.00.MD` | L69-L74 | @LiYanjun19, @stephenrwicks |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4791](https://github.com/Aspen-Discovery/aspen-discovery/pull/4791) DIS-2668: Add checkbox list to Custom Form | `code/web/release_notes/26.09.00.MD` | L74-L74 | @JonahCWilson, @LiYanjun19 |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4789](https://github.com/Aspen-Discovery/aspen-discovery/pull/4789) DIS-2853: "Aspen Events to Include" label | `code/web/release_notes/26.09.00.MD` | L74-L75 | @JonahCWilson, @stephenrwicks |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4788](https://github.com/Aspen-Discovery/aspen-discovery/pull/4788) DIS-2855: Enable Card Renewal dropdown disabling the wrong option | `code/web/release_notes/26.09.00.MD` | L74-L75 | @JonahCWilson, @stephenrwicks |

</details>

