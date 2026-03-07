# 🚀 UXAN Lethal Company Cheats

A sleek, powerful, and multiplayer-ready client-side utility mod specifically developed for Lethal Company. 

No more getting lost in dark corridors, running out of battery, or dealing with low-value scrap! This mod provides a massive tactical advantage and includes exclusive network exploits for public servers.


<img width="4160" height="1024" alt="Gemini_Generated_Image_l4w4ydl4w4ydl4w4" src="https://github.com/user-attachments/assets/918576bf-2ebc-497a-aa83-9c0f8c5cfda8" />


## ✨ Features

### 🕹️ Active Abilities (Keybinds)
* **Smart GPS / NavMesh Line (F10):** Draws a neon blue laser guide directly to the nearest exit door when lost inside, or directly to the ship when lost outside. *(100% Client-Side Safe)*
* **Advanced ESP (F9):** *(100% Client-Side Safe)*
  * 🟢 **Scrap:** Green boxes and snaplines showing the value and distance of items within 20 meters.
  * 🔴 **Enemies:** Red boxes showing the type and distance of creatures within 60 meters.
* **Scrap Value Hack (F11):** Instantly updates the value of any scrap you are holding to **$1500**. *(Note: Requires Host privileges to sync value with the ship's desk).*

### 🛡️ Passive Abilities (Always Active)
* **🎰 The Casino Heist (ATM Exploit):** If the server is running the `LethalCasino` mod, this cheat intercepts the network RPCs. Using the ATM to "Buy Chips" will silently request negative chips, bypassing server checks and instantly adding **$35000+** to the value of your held scrap! *(Works on any server).*
* **🔨 Thor's Hammer:** Shovel hit force is cranked up to 100. One-tap Thumpers, Spiders, and even Eyeless Dogs. *(Works perfectly on multiplayer servers).*
* **⚡ Flash Speed & Infinite Stamina:** Sprint speed is multiplied by 3.5x, and your stamina never depletes. Mimics and other fast monsters don't stand a chance.
* **🔋 Infinite Battery:** All battery-powered items (flashlights, walkie-talkies, jetpacks) are permanently locked to 100% charge locally.
* **🪂 Half Fall Damage:** Intercepts the game's physics engine to reduce all fall damage taken by exactly 50%.
* **🎯 Custom Crosshair:** A sleek white '+' sign added to the center of the screen, making shovel hits and item throws flawlessly accurate.

---

## 📸 Screenshots

| Smart NavMesh GPS | Advanced ESP (Boxes & Lines) |
| :---: | :---: |
| <img width="2559" height="1439" alt="gps" src="https://github.com/user-attachments/assets/599cad19-86a9-4e1b-bf0a-f915d5ec09cc" /> | <img width="2559" height="1439" alt="esp" src="https://github.com/user-attachments/assets/c3e66896-a938-4ce8-a114-7647d38f76e3" />


---

## ⚙️ Installation

This mod requires the **BepInEx** framework to function.

### Manual Installation:
1. Ensure you have [BepInEx](https://github.com/BepInEx/BepInEx) installed in your Lethal Company directory.
2. Download the `uxan_menu.dll` file from the **Releases** tab.
3. Drop the downloaded DLL file into your `Lethal Company/BepInEx/plugins/` folder.
4. Launch the game!

### Via Thunderstore Mod Manager:
1. Open your Lethal Company profile on Thunderstore.
2. Navigate to `Settings` -> `Browse profile folder`.
3. Go into the `BepInEx/plugins/` folder and paste the `uxan_menu.dll` file there.
4. Launch the game using the "Start Modded" button.

---

## ⌨️ Controls

| Key | Function |
| :--- | :--- |
| **F9** | Toggle ESP (Boxes, Lines, and Distance Info) |
| **F10** | Toggle Smart NavMesh GPS (Escape Route) |
| **F11** | Set Held Item Value to $1500 |

---

## 🛠️ Developer Notes

This project was developed in C# utilizing **.NET Standard 2.1** and **HarmonyLib**. Because it is strictly client-side, it only needs to be installed by the user; the host does not need to have it installed for it to work.

**Developer:** Uxan 
