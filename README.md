# Prince of Persia: The Lost Crown Save Editor (PS4)

A save editor for *Prince of Persia: The Lost Crown* on PS4, built with Python and PyQt6. This tool provides a powerful graphical interface to modify player stats, unlock all abilities and amulets, and manage your inventory with a full item database.

## 🚀 Key Features

### 👤 Character & Progression Editor

Modify core player statistics and equipment levels to suit your playstyle:

* **Health Status:** Directly edit current HP or set it to max (9999).
* **Currency & Resources:** Modify Time Crystals, Xerxes Coins, and Damascus Ingots up to 999,999.
* **Equipment Upgrades:** Max out levels for your Sword, Bow, Quiver capacity, and Potion efficiency/capacity with a single click.

### ⚡ Abilities & Amulets

Total control over Sargon's progression through dedicated tabs:

* **Abilities:** Instantly unlock all 24+ abilities, including Double Jump, Air Dash, Clairvoyance, and various Focus Abilities (Maelstrom, Heal, etc.).
* **Amulets:** Unlock any of the 38+ "Stones of Knowledge" (amulets) and increase your Max Amulet Slots up to 12.

### 📦 Inventory Editor

A robust system for managing items, consumables, and quest objects:

* **Searchable Database:** Browse and filter hundreds of items, including Soma Tree Petals/Seeds, Memory Shards, and Key Items.
* **Quantity Management:** Add items with custom quantities (up to 999,999x).
* **Lore & Skins:** Access the database to add Lore items or Character Skins (Crimson, Citrine, Emerald, etc.) directly to your save.

## 🖥 User Interface

The editor features a professional, modern dark theme designed for ease of use:

* **Aesthetic:** Deep charcoal and black background with high-contrast amber/gold accents (#ffb74d).
* **Organized Tabs:** Clean navigation between Character, Abilities, Amulets, and Inventory editors.
* **Interactive Controls:** Custom spinboxes, checkboxes, and a searchable table for efficient editing.

## 🛠 Tech Stack

* **Language:** Python 3.x
* **GUI Framework:** PyQt6
* **Data Handling:** JSON-based save data manipulation with recursive key searching.

## 📝 How to Use

1. **Open:** Load your decrypted PS4 save file using the "Open Save File" button.
2. **Edit:** Navigate through the tabs to adjust your stats, unlock abilities, or add items.
3. **Save:** Use "Save Changes" to apply modifications. The tool automatically creates a `.bak` backup of your original save for safety.

---

*Created by ArsaModz* :)
