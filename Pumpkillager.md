# 🎃 Pumpkillager's Quest

**Pumpkillager's Quest** is a SpookyJam 2022 submission that adds an immersive, Halloween-themed questline to your world! With custom encounters, cosmetic rewards, and a challenging boss fight, you'll find yourself swept up in a spooky story just by harvesting pumpkins.

---

## ✨ Features & Overview

* **The Pumpkillager:** A mysterious figure who might appear when you break a pumpkin. He brings a questline that requires multi-block rituals and preparation to survive.
* **Vanilla Asset Integration:** The mod uses custom player head textures for new blocks and custom renderers to morph entity sizes, meaning no new underlying assets are permanently added. If you desire, you can remove the mod after finishing the quest, and you'll still keep the rewards!
* **Natural Encounters:** To help you find the Pumpkillager naturally, there is a config option that gives pigs a small chance to spawn on top of a pumpkin block, sprinkling more pumpkins around your world.
* **Quest Books & Rituals:** Use quest books obtained from NPCs to build multi-block rituals. (Tip: Right-click the book on the ground to see a holographic preview of the required structure!)

---

## 📖 How to Start

There is a **1/10 chance** to encounter the Pumpkillager when harvesting a pumpkin block. 

* **Spawning Requirements:** The pumpkin block *must* be surrounded by empty space in all four cardinal directions (North, East, South, West) and above it. This prevents him from accidentally spawning inside custom pumpkin buildings.
* **The First Encounter:** Upon spawning, he will give you a quest book. Read it, gather the required materials, and follow the instructions to begin the rituals!

---

## ⚙️ Configuration Options

You can customize your experience in the mod's configuration file:

* `spumpkillagerSpawnChance` (default = 0.1): The chance (between 0.001 and 1.0) a Pumpkillager spawns when breaking a pumpkin.
* `enablePumpkillagerSpawnDuringCreative` (default = false): Set to true to allow him to spawn while playing in Creative mode.
* `finalBossMaxHealth` (default = 300.0): Adjust the health pool of the final boss (min 1.0, max 10000.0).
* `experienceAmountRewardFinalBoss` (default = 250): The amount of XP dropped by the final boss on death.
* `chanceForPumpkinBlockToSpawnOnPigSpawn` (default = 0.05): The chance a pig spawns on top of a pumpkin. Set to `0` to disable this feature entirely.

---

## 💻 Commands

* `/pumpkillager reset <player>`: Resets the quest progress for the specified player.
* `/pumpkillager book <book>`: Generates a specific quest book item manually.

---

## ⚠️ <SPOILERS AHEAD> Quest Walkthrough ⚠️

> [!WARNING]
> **Spoiler Warning!** > The section below contains a full step-by-step walkthrough of the questline, including the final boss fight. Read at your own risk!

**1. The First Encounter**
Break a standalone pumpkin block for a chance to spawn the Pumpkillager. He will hand you your first quest book.

**2. The First Ritual**
Read the book. It will show you how to complete the first ritual. Right-click the book on the ground to see a hologram of the required blocks.

**3. The Prisoner Camp Coordinates**
After completing the first ritual, the Pumpkillager will appear again. When he leaves, he will drop a piece of paper containing coordinates to a hidden prisoner camp.

**4. The Floating Island**
Travel to the coordinates. You will find a prisoner camp floating in the sky. Use the three water streams cascading down, or your own method, to ascend.

**5. The Guards**
Enter the camp carefully. It is heavily guarded. If you kill the guards, they will drop their custom heads as cosmetic loot.

**6. Rescue Jax o' Saturn**
Find and speak with the prisoner trapped inside the tree. He will reveal his real name (Jax o' Saturn) and give you a new book, a bow, and some arrows.

**7. Gather Supplies**
Before leaving the floating island, look around for decoration heads and candles. You will absolutely need the candles for the final ritual.

**8. The Final Ritual Preparation**
The new book from Jax o' Saturn contains instructions for the final ritual. Use the right-click hologram feature to set it up. Make sure it is nighttime/dark before placing the final pumpkin or lighting the final candle!

**9. The Boss Fight**
Upon activating the ritual, the Pumpkillager will confront you. 
* **Strategy:** You must shoot him with the spectral arrow provided by Jax to weaken him. 
* **The Waves:** He will summon various waves of mobs to protect him at the start of the fight, and again when he reaches 75%, 50%, and 25% health. Ensure you have your best armor, a shield, and potions!

**10. Victory!**
Defeat the Pumpkillager, claim your rewards, and save the world!

---

## 🔗 Technical Details & Links
* **Library Requirement:** This mod requires the **Collective** library mod to function.
* **Credits:** Created by Serilum (Part of The Vanilla Experience modpack).
* **Source & Downloads:** Available for Fabric, Forge, and NeoForge on [CurseForge](https://www.curseforge.com/minecraft/mc-mods/pumpkillagers-quest).
