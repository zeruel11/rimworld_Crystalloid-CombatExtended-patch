## This file describes what changes between old crystalloid (B17 version) and new crystalloid rewrite 1.0 version in relation to the patch made by Saebbi for B18. Mostly this is just a reminder for myself since AtomicRavioli didn't mention the changes. Considering getting in touch.

PawnDefs
- Pawn Crystal changed to Constructs, new Preserver and Crystal Spectre
- PawnKinds_CrystalSlave and PawnKinds_CrystalSpacer defs are now combined into PawnKinds_Refugees
- PawnKinds_CrystalLoyalist changed into PawnKinds_Loyalist and are mostly unchanged, CrystalloidFlayer no longer exists
- PawnKinds_CrystalRebel now divided into PawnKinds_Outlander, PawnKinds_Mercenary, and PawnKinds_Pirate. CrystalIndependent faction are also divided into OutlanderCivil and Pirate (or is that new?)

ThingDefs
- Weapons_CrystalBuildableGuns mostly stays the same. Weapons_CrystalGuns and Weapons_CrystalMelee no longer exists.

ThingDefs_Race
- The new Races_CrystalBase only defines base crystal parent. Old Races_Crystal contains other defs for Crystal_Prism and Crystal_PrismMini. Those are now moved into Races_CrystalConstruct, together with other constructs such as Crystal_Guardian and Crystal_GuardianP (used to be in Races_CrystalDeveloped) and the new Crystal_NeutralPrism, Crystal_Preserver, and Crystal_Specter
- Races_CrystalHumanlike are basically the same thing, albeit much simpler in rewrite version. Defs names are unchanged. Alien_Ascendant no longer exist