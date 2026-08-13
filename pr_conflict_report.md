# Aspen PR Conflict Report

Found **24** potential conflict(s) across **1** repository.

## Aspen-Discovery/aspen-discovery

### Cluster 1 — 10 PRs, 18 conflict(s)

**Authors:** @JonahCWilson, @gmcharlt, @lucasmontoya13, @olivia-openfifth

**Files:** `code/web/release_notes/26.09.00.MD`

**PRs:**
- [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching
- [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root
- [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages 
- [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools
- [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines
- [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces
- [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page
- [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible
- [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page
- [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L105-L108, L137-L142 | @JonahCWilson, @gmcharlt |
| [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4717](https://github.com/Aspen-Discovery/aspen-discovery/pull/4717) DIS-2830: Overdrive _callUrl error handling | `code/web/release_notes/26.09.00.MD` | L105-L108 | @JonahCWilson, @lucasmontoya13 |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4703](https://github.com/Aspen-Discovery/aspen-discovery/pull/4703) DIS-2791: Add 'translateParameters' flag across login-related pages  | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L102-L108 | @gmcharlt, @lucasmontoya13 |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4716](https://github.com/Aspen-Discovery/aspen-discovery/pull/4716) DIS-2739: fix tagging of translatable strings in My Account holds page | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools | [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4715](https://github.com/Aspen-Discovery/aspen-discovery/pull/4715) DIS-2573: make additional My Account buttons keyboard-accessible | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools | [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4714](https://github.com/Aspen-Discovery/aspen-discovery/pull/4714) DIS-2618: fix HTML coding glitch in Evergreen Hold Notification Preferences page | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools | [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4713](https://github.com/Aspen-Discovery/aspen-discovery/pull/4713) DIS-2410: Evergreen - allow login if user password contains spaces | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools | [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4690](https://github.com/Aspen-Discovery/aspen-discovery/pull/4690) DIS-2780 Collection Spotlight Caching | [#4711](https://github.com/Aspen-Discovery/aspen-discovery/pull/4711) DIS-1871: fix crash recording payments of certain Evergreen fines | `code/web/release_notes/26.09.00.MD` | L137-L142 | @JonahCWilson, @gmcharlt |
| [#4702](https://github.com/Aspen-Discovery/aspen-discovery/pull/4702) DIS-2753: Run fewer cronjobs as root | [#4706](https://github.com/Aspen-Discovery/aspen-discovery/pull/4706) DIS-2798: Add PHPStan to Composer Dev Tools | `code/web/release_notes/26.09.00.MD` | L71-L75 | @JonahCWilson, @olivia-openfifth |

</details>

### Cluster 2 — 6 PRs, 6 conflict(s)

**Authors:** @Chloe070196, @Jacobomara901, @JonahCWilson, @librarianbryan

**Files:** `code/web/release_notes/26.08.00.MD`, `code/web/sys/Interface.php`

**PRs:**
- [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci
- [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box
- [#4645](https://github.com/Aspen-Discovery/aspen-discovery/pull/4645) DIS-2731: feat: minimal self reg
- [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold"
- [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class 
- [#4709](https://github.com/Aspen-Discovery/aspen-discovery/pull/4709) DIS-2740: fix: display self reg error message

<details>
<summary>Pairwise details</summary>

| PR A | PR B | Conflicting Files | Overlapping Lines | Authors |
|------|------|-------------------|-------------------|---------|
| [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box | [#4709](https://github.com/Aspen-Discovery/aspen-discovery/pull/4709) DIS-2740: fix: display self reg error message | `code/web/release_notes/26.08.00.MD` | L73-L76 | @Chloe070196, @librarianbryan |
| [#4593](https://github.com/Aspen-Discovery/aspen-discovery/pull/4593) DIS-2680: aspen.sql regeneration ci | [#4709](https://github.com/Aspen-Discovery/aspen-discovery/pull/4709) DIS-2740: fix: display self reg error message | `code/web/release_notes/26.08.00.MD` | L78-L79 | @Chloe070196, @Jacobomara901 |
| [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class  | `code/web/release_notes/26.08.00.MD` | L104-L105 | @Jacobomara901, @JonahCWilson |
| [#4645](https://github.com/Aspen-Discovery/aspen-discovery/pull/4645) DIS-2731: feat: minimal self reg | [#4661](https://github.com/Aspen-Discovery/aspen-discovery/pull/4661) DIS-2679: Refactor default database export into a PDO-based class  | `code/web/release_notes/26.08.00.MD` | L104-L107 | @Chloe070196, @Jacobomara901 |
| [#4645](https://github.com/Aspen-Discovery/aspen-discovery/pull/4645) DIS-2731: feat: minimal self reg | [#4646](https://github.com/Aspen-Discovery/aspen-discovery/pull/4646) DIS-2742: Array Offset Bug in "Titles on Hold" | `code/web/release_notes/26.08.00.MD` | L99-L105 | @Chloe070196, @JonahCWilson |
| [#4620](https://github.com/Aspen-Discovery/aspen-discovery/pull/4620) 26.08.00 DIS-2459 simplified search box | [#4645](https://github.com/Aspen-Discovery/aspen-discovery/pull/4645) DIS-2731: feat: minimal self reg | `code/web/sys/Interface.php` | L667-L672 | @Chloe070196, @librarianbryan |

</details>

