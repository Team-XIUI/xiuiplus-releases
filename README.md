# XIUI+

A customizable in-client HUD for Final Fantasy XI on Ashita v4, with player and party displays, targets, chat, minimap, timers and inventory tools.

[Download the latest DLL](https://github.com/Shuu-37/xiuiplus-releases/releases/latest/download/XIUIplus.dll) · [Latest release](https://github.com/Shuu-37/xiuiplus-releases/releases/latest) · [All releases](https://github.com/Shuu-37/xiuiplus-releases/releases)

Each release provides `XIUIplus.dll` and `SHA256SUMS.txt`. Assets, default settings and notices are embedded in the DLL.

## Requirements and installation

- Windows, Final Fantasy XI and Ashita v4.
- Unload the plugin with `/unload XIUIplus`, or close the game before updating it.
- Copy `XIUIplus.dll` into Ashita's `plugins` folder, then run `/load XIUIplus`. Add that command to your startup script if you want automatic loading.
- Existing settings and positions are preserved. Saved data lives under `config/XIUIplus/`.

When upgrading from XIUI Native, run `/unload xiuinative` first and remove its old `plugins/xiuinative.dll`. Install `XIUIplus.dll` and update any startup load command to `/load XIUIplus`. Existing XIUI Native data migrates automatically on the next plugin load; conflicting older files are retained under `legacy/`.

## Settings and profiles

Use `/xiuip edit` or `/xiuiplus edit` to configure the HUD. `/xiui+`, `/xiui` and earlier command aliases remain supported.

Profiles can be shared as `.xiuiplus` files. Imports also support older `.xiui` files, XIUI1/XIUI2 share keys and supported original XIUI Lua setups.

Original XIUI contributors and artwork are credited in game; third-party notices remain embedded in the plugin.

This public repository hosts release downloads, release notes and installation instructions. Development is maintained privately.
