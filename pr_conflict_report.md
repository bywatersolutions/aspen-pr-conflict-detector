# Aspen PR Conflict Report

Found **45** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 20 PRs, 41 conflict(s)

**Authors:** @JonahCWilson, @gmcharlt, @kidclamp, @kylemhall, @lathomas64, @lucasmontoya13, @myr-onl, @olivia-openfifth, @samyoung-maker, @stephenrwicks

**Files:** `code/web/Action.php`, `code/web/interface/themes/responsive/GroupedWork/full-record.tpl`, `code/web/interface/themes/responsive/RecordDrivers/GroupedWork/result.tpl`, `code/web/release_notes/26.09.00.MD`, `code/web/sys/DBMaintenance/version_updates/26.09.00.php`

**PRs:**
- [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374
- [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit
- [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold"
- [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching
- [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root
- [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages 
- [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines
- [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page
- [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling
- [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits
- [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information
- [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request
- [#4733](https://github.com/Aspen-Discovery/aspen-discovery/pull/4733) DIS-2836: Add data attributes for Playwright tests
- [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes
- [#4739](https://github.com/Aspen-Discovery/aspen-discovery/pull/4739) DIS-2814 Add class names to search results and full record pages
- [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable
- [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row
- [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4733](https://github.com/Aspen-Discovery/aspen-discovery/pull/4733) DIS-2836: Add data attributes for Playwright tests | [#4739](https://github.com/Aspen-Discovery/aspen-discovery/pull/4739) DIS-2814 Add class names to search results and full record pages | `code/web/interface/themes/responsive/GroupedWork/full-record.tpl`, `code/web/interface/themes/responsive/RecordDrivers/GroupedWork/result.tpl` | L18-L24, L5-L5 | @myr-onl, @stephenrwicks |
| [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | `code/web/release_notes/26.09.00.MD` | L34-L36 | @JonahCWilson, @samyoung-maker |
| [#4733](https://github.com/Aspen-Discovery/aspen-discovery/pull/4733) DIS-2836: Add data attributes for Playwright tests | [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | `code/web/release_notes/26.09.00.MD` | L34-L36 | @JonahCWilson, @myr-onl |
| [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | [#4750](https://github.com/Aspen-Discovery/aspen-discovery/pull/4750) DIS-2776: Unavailable hold filters | `code/web/release_notes/26.09.00.MD` | L30-L30 | @JonahCWilson, @gmcharlt |
| [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L146 | @gmcharlt, @kylemhall |
| [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L140-L145 | @gmcharlt, @kylemhall |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/release_notes/26.09.00.MD` | L120-L122, L140-L143 | @JonahCWilson, @kylemhall |
| [#4733](https://github.com/Aspen-Discovery/aspen-discovery/pull/4733) DIS-2836: Add data attributes for Playwright tests | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L34-L40 | @myr-onl, @samyoung-maker |
| [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @gmcharlt, @samyoung-maker |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4742](https://github.com/Aspen-Discovery/aspen-discovery/pull/4742) DIS-2743: Make panel heading fully clickable | `code/web/release_notes/26.09.00.MD` | L137-L139 | @JonahCWilson, @samyoung-maker |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | `code/web/release_notes/26.09.00.MD` | L140-L143 | @JonahCWilson, @gmcharlt |
| [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L69-L73 | @gmcharlt, @olivia-openfifth |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L72-L73 | @JonahCWilson, @gmcharlt |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L108-L113 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L108-L108 | @gmcharlt, @lucasmontoya13 |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L108-L113 | @gmcharlt, @lathomas64 |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L107-L108 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L107-L108 | @JonahCWilson, @lucasmontoya13 |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L107-L113 | @JonahCWilson, @lathomas64 |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L102-L108 | @gmcharlt, @lucasmontoya13 |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L106-L108 | @gmcharlt, @lathomas64 |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4314](https://github.com/Aspen-Discovery/aspen-discovery/pull/4314) DIS-2192 Curl Wrapper rate limit | [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | `code/web/release_notes/26.09.00.MD` | L106-L108 | @lathomas64, @lucasmontoya13 |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | `code/web/release_notes/26.09.00.MD` | L72-L75 | @JonahCWilson, @olivia-openfifth |
| [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/Action.php` | L121-L122 | @JonahCWilson, @kylemhall |
| [#4242](https://github.com/Aspen-Discovery/aspen-discovery/pull/4242) DIS-2374 | [#4748](https://github.com/Aspen-Discovery/aspen-discovery/pull/4748) DIS-2789: AspenUsage counters use read-modify-write, losing page view counts and serializing every request on a single row | `code/web/sys/DBMaintenance/version_updates/26.09.00.php` | L41-L56 | @kidclamp, @kylemhall |

</details>

### Cluster 2 — 5 PRs, 4 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @K-Alette, @librarianbryan, @lucasmontoya13

**Files:** `code/web/interface/themes/responsive/Search/horizontal-searchbox.tpl`, `code/web/release_notes/26.08.00.MD`

**PRs:**
- [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method
- [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci
- [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box
- [#4746](https://github.com/Aspen-Discovery/aspen-discovery/pull/4746) DIS-2622: Allow configuration of Search types and Search sorts option
- [#4751](https://github.com/Aspen-Discovery/aspen-discovery/pull/4751) DIS-2851: Solr Docker volume freezes config across image upgrades, breaking analysis-extras after the Solr 9 bump

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box | [#4751](https://github.com/Aspen-Discovery/aspen-discovery/pull/4751) DIS-2851: Solr Docker volume freezes config across image upgrades, breaking analysis-extras after the Solr 9 bump | `code/web/release_notes/26.08.00.MD` | L18-L18 | @librarianbryan, @lucasmontoya13 |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box | `code/web/release_notes/26.08.00.MD` | L75-L76 | @Chloe070196, @librarianbryan |
| [#3573](https://github.com/Aspen-Discovery/aspen-discovery/pull/3573) DIS-1320: display and update primary contact method | [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci | `code/web/release_notes/26.08.00.MD` | L78-L81 | @Chloe070196, @Jacobomara901 |
| [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box | [#4746](https://github.com/Aspen-Discovery/aspen-discovery/pull/4746) DIS-2622: Allow configuration of Search types and Search sorts option | `code/web/interface/themes/responsive/Search/horizontal-searchbox.tpl` | L16-L30, L42-L43, L60-L65 | @K-Alette, @librarianbryan |

</details>

