# Aspen PR Conflict Report

Found **39** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 14 PRs, 37 conflict(s)

**Authors:** @JonahCWilson, @gmcharlt, @lucasmontoya13, @olivia-openfifth

**Files:** `code/web/release_notes/26.09.00.MD`

**PRs:**
- [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching
- [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root
- [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages 
- [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools
- [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines
- [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible
- [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page
- [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling
- [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits
- [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information
- [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request
- [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L140-L143 | @JonahCWilson, @gmcharlt |
| [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L71-L73, L137-L143 | @JonahCWilson, @gmcharlt |
| [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L71-L72 | @JonahCWilson, @gmcharlt |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | [#4735](https://github.com/Aspen-Discovery/aspen-discovery/pull/4735) DIS-2840: PHPStan Baseline Bugfixes | `code/web/release_notes/26.09.00.MD` | L71-L75 | @JonahCWilson, @olivia-openfifth |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | `code/web/release_notes/26.09.00.MD` | L140-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | `code/web/release_notes/26.09.00.MD` | L140-L143 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4725](https://github.com/Aspen-Discovery/aspen-discovery/pull/4725) DIS-2834: Evergreen - Add agent parameter to login request | `code/web/release_notes/26.09.00.MD` | L140-L142 | @JonahCWilson, @gmcharlt |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L71-L73, L137-L143 | @JonahCWilson, @gmcharlt |
| [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L69-L73 | @gmcharlt, @olivia-openfifth |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4724](https://github.com/Aspen-Discovery/aspen-discovery/pull/4724) DIS-2832: Fix setting a location in Host Information | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L108-L111, L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L108-L108 | @gmcharlt, @lucasmontoya13 |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4722](https://github.com/Aspen-Discovery/aspen-discovery/pull/4722) DIS-1891: fix issue saving copied placard after certain trigger word edits | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L105-L108, L137-L142 | @JonahCWilson, @gmcharlt |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L105-L108 | @JonahCWilson, @lucasmontoya13 |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L102-L108 | @gmcharlt, @lucasmontoya13 |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible | `code/web/release_notes/26.09.00.MD` | L71-L72 | @JonahCWilson, @gmcharlt |
| [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible | `code/web/release_notes/26.09.00.MD` | L69-L72 | @gmcharlt, @olivia-openfifth |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | `code/web/release_notes/26.09.00.MD` | L137-L143 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Aspen Discovery CI - Static Analysis tools | `code/web/release_notes/26.09.00.MD` | L71-L75 | @JonahCWilson, @olivia-openfifth |

</details>

**[#4689](https://github.com/Aspen-Discovery/aspen-discovery/pull/4689)** ↔ **[#4737](https://github.com/Aspen-Discovery/aspen-discovery/pull/4737)** — `code/web/release_notes/26.08.00.MD` (L144-L149) — @JonahCWilson, @lucasmontoya13

**[#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646)** ↔ **[#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661)** — `code/web/release_notes/26.08.00.MD` (L104-L105) — @Jacobomara901, @JonahCWilson

