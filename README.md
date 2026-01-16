# Prince of Persia: The Lost Crown Save Editor (PS4)

A powerful, modern, and user-friendly save editor for **Prince of Persia: The Lost Crown (PS4)**. This tool allows players to modify character stats, unlock abilities, manage amulets, and edit their inventory through a custom-built dark-themed GUI.

## 🚀 Features

### 🛡️ Character & Stats Editor

* **Health Management:** Modify current HP or instantly set it to max.
* **Currency Editor:** Adjust Time Crystals, Xerxes Coins, and Damascus Ingots.
* **Equipment Upgrades:** Level up your Sword, Bow, Quiver, and Potions (Efficiency & Capacity) with a single click.

### ⚔️ Abilities & Amulets

* **Instant Unlocks:** Unlock all Athra Surges and Time Powers.
* **Amulet Management:** Toggle specific amulets or unlock the entire collection.
* **Slot Editor:** Modify the maximum number of amulet slots available.

### 🎒 Advanced Inventory Editor

* **Database Search:** Filter through a comprehensive list of game items using a real-time search bar.
* **Bulk Actions:** Add individual items, update quantities, or use the "Add All" feature to populate your inventory.
* **Hex ID Support:** View and manage items via their internal Hex IDs for precision.

### 🛠️ Technical Safety

* **Automatic Backups:** Every time you save, the editor creates a `.bak` file of your original save to prevent data loss.
* **JSON Parsing:** Cleanly handles the extraction and injection of game data between the file's binary headers and footers.

---

## 📸 Preview

The editor features a **Modern Dark Theme** designed for high visibility and ease of use:

* **Amber Accents** for primary navigation.
* **Scannable Tables** for inventory management.
* **Responsive Layout** optimized for 1280x720 resolution.

---

## 🛠️ Installation & Usage

1. **Requirements:**
* Python 3.10 or higher.
* PyQt6 library.


2. **Setup:**
```bash
pip install PyQt6

```


3. **Run the Editor:**
```bash
python main.py

```


4. **Instructions:**
* Transfer your PS4 save file (`.AlkSave`) to your PC.
* Click **Open Save File** and select your save.
* Modify your desired stats in the various tabs.
* Click **Save Changes** to overwrite the file (a backup will be created automatically).



---

## ⚠️ Disclaimer

This tool is intended for single-player use and modding purposes. Always keep a backup of your original save files. Use at your own risk.

**Developed by:** ArsaModz
