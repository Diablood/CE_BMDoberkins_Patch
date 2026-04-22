# Changelog

## v1.0.0 – CE Complete Overhaul

### 🔫 Weapons
- Full Combat Extended integration for all Doberkin ranged weapons
- Replaced all legacy/custom verbs with stable `Verb_ShootCE`
- Standardized full `<verbs>` replacement across all weapons
- Added proper CE firemodes where relevant (single / burst / auto)
- Fixed multiple issues:
  - invalid targeting
  - missing CE UI elements
  - pawn control lock on heavy weapons

### 💥 Ammunition
- Complete overhaul of all ammunition:
  - FMJ, AP, HP, HE, Frag, Overcharge
- Rebalanced damage and penetration across all calibers
- Defined clear ammo roles (anti-personnel, anti-armor, explosive, energy)
- Fixed inconsistencies and outdated definitions

### 📦 Logistics
- Reworked all ammo stack limits (no more 5000 stacks everywhere)
- Adjusted mass and bulk for realistic loadouts
- Heavy and energy weapons now properly constrained by logistics

### 🏭 Crafting
- Fully rebalanced all ammo recipes
- Introduced production tiers:
  - AmmoBench → standard ammunition
  - FabricationBench → advanced / energy / heavy ammunition
- Adjusted resource cost and work amount for consistency

### ⚙️ Balance
- Harmonized warmup times across all weapons
- Normalized recoil values
- Adjusted cooldowns for better gameplay flow
- Reinforced weapon roles:
  - SMG / CQB
  - Rifle / standard combat
  - Heavy / suppression
  - Anti-material
  - Energy / high-tech
  - Elite / command

### 🛠 Technical
- Fixed invalid XML (e.g. recoil on non-CE verbs)
- Removed obsolete XPath operations
- Cleaned all leftover references to legacy systems
- Ensured full CE UI compatibility

### 🎯 Design
- Preserved original Doberkin identity
- Reduced unnecessary UI clutter
- Firemodes added only when meaningful
- Balanced for long-term gameplay (not short test scenarios)

---

## v0.4.0 - Combat Extended full weapon conversion
- Full conversion of all Doberkin ranged weapons to Combat Extended (CE)
- Replaced all remaining custom verbs with `Verb_ShootCE`
- Fixed invalid verb targeting
- Standardized `<verbs>` replacement

---

## v0.3.x – Apparel & Royalty integration
- CE armor rebalance
- Royalty noble apparel support
- Apparel fixes and consistency improvements

---

## v0.2.x – Weapon handling & CE integration
- One-handed weapon support
- Shield compatibility
- CE weapon classification improvements

---

## v0.1.x – Initial CE patch
- Initial Combat Extended compatibility
- Melee support patch
- Weapon role differentiation