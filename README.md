# Bouk's Phase 6 Lootapalooza ![](./skinnay_rip.png)

The base of this document is ripped directly from  [Skinnay's Classic Gear List](https://gist.github.com/skinnay-dev/39f71f3cce1c64b95142f7e0e0d97bca), modified slightly, and updated to fit our current understanding of hunters in classic.  Please see his list for pre-phase 6 gear lists.

Phase 6 BiS is much simpler than previous phases as T3 is far and away better than most other gear in the game.  Stat weights and dps values are based on [Sixx's DPS sheet](https://docs.google.com/spreadsheets/d/1BIlB2P1kyV_QdD4ULQzvZvS6hK6BDouUQkyHQzCvBGI/edit#gid=333718892) and assume full buffs, consumables, and uptime on boss debuffs with 20/31/0 spec<!-- Todo link config -->. Weapon calculations assume absolute BiS armor and likewise, armor calculations assume absolutely BiS weapons.  DPS numbers are from stable rotations without use of haste effects or active trinkets. 

As these sets are being simmed under pretty contrived settings (100% debuff, pet uptime, etc) the absolute DPS values of each set is fairly meaningless.  Gear upgrades should be compared relative to the pieces and sets they are replacing.  Likewise, Blessing of Kings (and Windfury when weaving) raises the top end DPS of all sets but do not meaningfully change how the sets compare to eachother.  As such, all sets are simmed with Blessing of Kings.  We've put the simmed DPS of top end weave sets with Windfury (WF) in the notes column because melee hits go brrrrt.

Phase 6 introduces [Consecrated Sharpening Stones.
](https://classic.wowhead.com/item=23122/consecrated-sharpening-stone)  Our best current knowledge indicates these work for ranged AP as well as melee.  As such, we've simmed all sets with them applied (except WF sims).

We assume [20/31/0](https://classic.wowhead.com/talent-calc/hunter/53000200505-05251030513051) due to Slaying talents affecting very few raid bosses in Naxx and AQ rather than the p3/4 [13/31/7](https://classic.wowhead.com/talent-calc/hunter/530002003-05251030513051-32002) spec.

# Armor

| Gear set | Weave DPS | Ranged DPS | Notes |
|---|---|---|---|
| [P6 R12 MW, True](https://sixtyupgrades.com/set/3eyrLWdJfvxBSKiyRGV7cE) | 1407.4 | 1211.0 | 1528.1 with WF and WCB |
| [P6 MW, Realistic](https://sixtyupgrades.com/set/qyzXyWwpmv3PidFcxqnR65) | 1394.3 | 1199.7 | 1474.7 with WF |
| [P6 R12, True](https://sixtyupgrades.com/set/tpGfZE1SAThnieDcynaQHg) | | 1242.4 | |
| [P6, Realistic](https://sixtyupgrades.com/set/fJSDZNQ46z9tzPsxcGRmTV) | | 1223.5 | |
| [P6, T2](https://sixtyupgrades.com/set/6tCwbG87bHeGpaS5cfxFPq) | | 1174.4 | +9 dps / hunter / T2 set |
| [P5 BiS R12](https://sixtyupgrades.com/set/jrNhws7xF4oNJyij7sWcG4) | 1280.4 | 1089.4 | Weave simmed with Barb |

# Weapons

Some hunters floated the idea of weaving with dual-wielded weapons in phase 6 due to the introduction of Consecrated Sharpening Stones.  We were unable to build a set for which this beat 2 handers at melee weaving with many different combinations of slow mainhands, Windfury on MH, Orc racial, etc.  Slow 2 handers are far and away better for weaving.

## Melee Weaving Weapon DPS

| Weapon | Normal Weave | Max Weave | Max with WCB |
|---|---|---|---|
| Eye of Nerub | +57 <!--1368--> | +47 <!--1407--> | +85 <!--1445--> |
| Severence _(Orc)_ <sup>[1](#severance)</sup> | +40 | +60 | +54 |
| Barb of the Sand Reaver | +40 <!--1351--> | +27 <!--1387--> | +63 <!--1423--> |
| Corrupted Ashbringer | +40 <!--1351--> | +42 <!--1402--> | +61 <!--1431--> |
| Claymore of Unholy Might | +30 <!--1341--> | +28 <!--1388--> | +57 <!--1417--> |
| Severence | +26 <!--1337--> | +26 <!--1386--> | +54 <!--1414--> |
| Gri'leks Carver _(Dragonkin)_ | +33 <!--1344--> | -5 <!--1355--> | +43 <!--1403--> |
| Ashkandi | +23 <!--1334--> | +19 <!--1379--> | +48 <!--1408--> |
| Zin'rokh | +20 <!--1331--> | -2 <!--1358--> | |
| Huntsman's Harpoon | +17 <!--1328--> | +2 <!--1362--> | |
| Lok'delar / Peacemaker | +4 <!--1315--> | +11 <!--1371--> | |
| Barbarous Blade (baseline) | +0 <!--1311--> | +0 <!--1360--> | |
This table changes very little from p5 -> p6 for normal weavers.  For hunters max weaving, the faster attack speed on KT xbow actually shifts the relative strength of a couple weapons, favoring weapons which delay your max weave rotation less.  This is most apparent in that Gril'leks actually loses out to Ashkandi--with and without Warchief's Blessing, even against Dragonkin--due to its insanely slow speed delaying your ranged shots. 

<a name="severance">1</a>: [Severance](https://classic.wowhead.com/item=22815/severance) is a 3.6 speed 2 handed axe with 43 strength and 2% crit.  In the contrived setting we're simming things in, [using Severance and putting a hitscope onto your Nerubain Slavemaker](https://sixtyupgrades.com/set/cu7DhXxuLdRSsQsvEtN1Z9) is technically the best max weaving gear set for an Orc with Windfury.  It beats Eye of Nerub by 2 DPS if you have Windfury but loses to Nerub when both sets have WCB by ~3 DPS.  It drastically loses to Eye as soon as your max weave uptime dips from 100% (which will happen in any fight you proc Quick Shots or use Rapid Fire during).  

## Ranged Stat Stick Weapon eAP

| Weapon | Base | Kings | ZG | Kings + ZG |
|---|---|---|---|---|
Kingsfall | 132 | 138 | 142 | 149
Iblis, Blade of the Fallen Seraph | 115 |  |  | 
Harbringer of Doom | 109 | 114 | 117 | 120
Claw of the Frost Wyrm (OH) | 107 |  |  | 
Blessed Qiraji Pugio | 105 |  |  | 
Maexxna's Fang | 84 |  |  | 
Hatchet of Sundered Bone | 77 |  |  | 
Silithid Claw (MH) | 71 |  |  | 
Hakkari MH / Fang of the Faceless / R14 | 69 |  |  | 
Brutality Blade | 65 | 68 | 70 | 74
Core Hound Tooth / Ancient Qiraji Ripper | 61 |  |  | 
Tooth of Eranikus (MH) | 48 |  |  | 
16 agi weapons<sup>[2](#agi-weapons)</sup> | 44 | 49 | 51 | 56
Dal'Rend's Set (each) | 45 |  |  | 
1% crit weapons<sup>[3](#crit-weapons)</sup> | 40 |  |  | 
Bone Slicing Hatchet | 36 | 40 | 41 | 46

<a name="agi-weapons">2</a>: _Dragonfang Blade / Doom's Edge (Unique) / Scythe of the Unseen Path_

<a name="crit-weapons">3</a>: _Assassination Blade / Dawn's Edge / Heartseeker / Thekal's Grasp (MH) / Dal'Rend's Sacred Charge (MH)_

Values in the above table are p6 eAP.

| Stat | eAP | Kings | ZG | Kings + ZG |
|---|---|---|---|---|
| 1 Agi | 2.76 | 3.05 | 3.19 | 3.53 |
| 1% Crit | 40.23 | 40.83 | 41.12 | 41.79 |
| 1% Hit | 47.18 | 48.38 | 48.97 | 50.35 |


<!-- TODO check WSG legs when hit needed -->



<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>