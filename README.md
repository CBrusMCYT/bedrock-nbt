# BedrockNBT

**Minecraft Bedrock NBT & World Editor**

> Edit NBT & World Minecraft Bedrock (.mcworld) directly in your browser. No install, no upload, works offline.

> **Note:** For now the language is still Indonesian. The UI inside the app is still in Indonesian, English version coming soon.

## ✨ Features

### NBT Editor
- Open `level.dat`, `.nbt`, `.mcstructure`, and playerdata `.dat` for Bedrock
- NBTExplorer-style tree view: edit, add, duplicate, delete, undo, search

### World Editor (.mcworld)
- Open Bedrock worlds (`.mcworld`)
- Edit player, block entities, entities, and `level.dat`
- Export & import structures (`.mcstructure`) from your world

### Item Builder
- Custom enchantments up to level **32767**
- Durability, lore, item components, blocks
- Structure Block presets
- Create One Slash items like Sharpness 32767 in one click

### PWA & Offline
- Installable as a PWA — Add to Home Screen
- Works fully offline after first load
- Fast, lightweight, no backend

## 🚀 How to Use

1. Open the demo link in Chrome
2. Drop your `.mcworld` / `level.dat` file
3. Edit what you want
4. Export and import the result back to Minecraft

## ⚠️ Important

- Always back up your world before editing. World writing is still experimental.
- Exporting a world produces `name_edit.mcworld` — import that file into Minecraft.
- For best experience, open via HTTPS. Opening `index.html` directly from file manager may disable offline mode.

## 🛠️ Tech Stack

- Vanilla HTML / CSS / JavaScript
- LevelDB reader for `.mcworld`
- Service Worker + PWA Manifest
- No framework, no server, no database

## 📄 License

MIT License — free to use, fork, and modify.
