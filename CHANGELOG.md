# Changelog

## v0.3.8 - Fix:
- Add tradeTags to ammunitions

## v0.3.7 - Fix:
- Naming fix

## v0.3.6 - Fix:
- Range weapon fix

## v0.3.5 - Language:
- Languages files : English and French

## v0.3.4 - Fix:
- Replaced the injection of one-handed weapon tags (melee) with valid logic using PatchOperationConditional + PatchOperationAdd.

## v0.3.3 - Fix:
- Fixed Royalty noble apparel recognition for commander sets
- High Commander now satisfies noble apparel requirements up to Archon/Archotech ranks
- Shield Commander now satisfies noble apparel requirements up to Archon/Archotech ranks
- Fixed High Commander apparel interaction causing forbid/haul errors
- Added DLC-safe Royalty compatibility with no effect when Royalty is not active
- Completed CE rebalance pass for selected Doberkin clothing items
- Rebalanced gloves, boots, backpacks, battery packs, masks, and casual apparel
- Improved CE consistency across protection, utility, and intended equipment role

## v0.3.2 - Fix:
- Fixed incorrect CE armor scaling (values too low)
- Recalibrated armor to match CE RHA expectations
- Shield Commander now comparable to Recon armor
- High Commander now provides meaningful protection
- Global armor rebalance for CE consistency
- Noble/Royalty Set

## v0.3.1 - Hotfix: apparel armor uplift
- Increased CE blunt and sharp armor on the main military sets after in-game comparison against recon and marine-grade armor.
- Boosted Shield Commander and High Commander defenses so they feel appropriately elite without turning into cataphract-tier gear.
- Raised core Doberkin combat apparel values to better match the intended 'military balanced / fun' gameplay profile.

## v0.3.0 - Apparel balance + Royalty noble recognition
- Rebalanced Doberkin apparel for Combat Extended using a fun/jouability profile rather than strict lethality.
- Normalized sharp and blunt armor values across civilian, basic, advanced, powered and commander apparel.
- Reduced several extreme vanilla armor ratings so Doberkin gear stays strong without trivializing CE ballistics.
- Differentiated Shield Commander gear as elite field-command apparel and High Commander gear as prestige apparel.
- Added conditional Royalty noble-apparel tags to the Shield Commander and High Commander sets.
- Royalty integration is patch-only: the mod behaves normally when the DLC is not installed.


## v0.2.1 - fix
- Fixed an incorrect use of PatchOperationAddIfMissing in the 07_CE_WeaponHandling_Patch.xml file.
- Replaced the injection of one-handed weapon tags with valid logic using PatchOperationConditional + PatchOperationAdd.
- Maintains compatibility of the DKF Reprimand, DKF Comrade Arms and DKF Commander's Sidearm weapons with shields in CE.

## v0.2.0 - one-handed / shield handling
- CE classification of Doberkin weapons for use with a shield
- DKF Reprimand, DKF Comrade Arms and DKF Commander's Sidearm confirmed as one-handed weapons via the `CE_OneHandedWeapon` tag
- all other patched weapons remain implicitly two-handed in CE
- added a `WorkshopUpload` folder containing a VDF model and a script to automatically inject the latest entry from the `CHANGELOG.md` file into the `changenote` field before uploading to Steam Workshop


## v0.1.2 - hotfix
- corrected ranged weapon description data for CE by replacing the full `verbs` block instead of targeting only `CombatExtended.Verb_ShootCE` entries
- fixes observed incorrect displayed range values on DKF Cluster and DKF Comrade Arms
- same fix applied to all patched ranged weapons for consistency and to avoid custom verb class leftovers from the source mod

## v0.1.1 - Differentiating weapon roles
- Rebalancing ammunition damage to better distinguish between SMGs, shotguns, heavy pistols, slug launchers, heavy machine guns, anti-tank rifles and energy weapons.
- Minor adjustments to ranges, warm-up times and burst modes to reinforce each weapon’s identity without altering the one-handed/two-handed status.
- No changes to clothing at this stage.

## v0.1.0
- Added Combat Extended melee support patch for Doberkin melee weapons.
- Kept XML formatting consistent with 4-space indentation.
- Verified no empty directories remain in the release package.
