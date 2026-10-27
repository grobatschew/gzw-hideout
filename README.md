# GZW Hideout Tracker

A small single-page tracker for the Hideout building material requirements in Gray Zone Warfare patch 0.5 Rogue Ops.

Set your station levels for up to four characters and get a bill of materials for what's left to build, with an "I have" count for what you have stashed and a "Farm" column for what you still need to collect. 
Progress is saved in your browser and can be moved between devices with export/import.

**Live page: https://grobatschew.github.io/gzw-hideout/**

Hideout upgrade data comes from the [Gray Zone Warfare Wiki](https://gray-zone-warfare.fandom.com/wiki/Hideout). Unofficial fan project, not affiliated with the game's developers.

## How to use

1. **Pick a character.** Use the Character buttons (1 to 4) at the top. Each character keeps its own station levels and stash. To use names instead of numbers, open **Options > Character names**.
2. **Set your station levels.** On the **Station levels** tab, pick the level you have built for each station. 0 means not built yet.
   - Tick **Subtract material when upgrading station** to have your "I have" counts reduced automatically when you pick a higher level. Lowering a level gives nothing back.
   - **Reset levels** sets all stations of the selected character back to 0.
3. **Plan your farming.** The **Bill of materials** tab (the default) lists the money and materials still needed to max every station.
   - **Total Required** is what is left to build.
   - **I have** is your stash. Type a number, use the + / - buttons, or hover the field and use the mouse wheel.
   - **Farm** is Total Required minus I have. A tick means you have enough.
   - Click a column header to sort. **Copy list** copies the remaining materials as text.
4. **See what each station needs.** The **By station** tab shows the remaining upgrade levels per station and marks the next one. Maxed stations are hidden.
5. **Back up or move your progress.** **Options > Copy export string** copies all four characters, including names, as one string. **Options > Import...** loads such a string and replaces everything. Older single-character strings only replace the selected character.

Everything is stored in your browser's local storage. Clearing site data erases it, so export a string now and then as a backup.

## Disclaimer

This project was created with Claude Sonnet 5.5 by Anthropic. Material requirements were copied from the wiki and may be incomplete, outdated or contain mistakes, so check them against the game.
