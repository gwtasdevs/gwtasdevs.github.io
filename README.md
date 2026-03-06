# Guild Wars TAS Tools

TAS toolbox releases can be found [here](https://github.com/gwtasdevs/GWToolboxpp/releases).

A new release will be created automatically whenever Toolbox is updated. Releases marked as <span style="color: #9e6a03; border: 1px solid #9e6a03; border-radius: 624.938rem; padding: 0 0.5rem; line-height: 22px; font-size: 0.75rem;">Pre-release</span> correspond to updates to the Toolbox dev branch.

## Installation
- Install [Toolbox](https://www.gwtoolbox.com) normally
- Download the files from the [latest TAS version](https://github.com/gwtasdevs/GWToolboxpp/releases/latest)
- Replace `GWToolboxdll.dll` in `C:\Users\<name>\Documents\GWToolboxpp`
- Replace `gwca.dll` in `C:\Users\<name>\Documents\GWToolboxpp\<name>`
- Place any plugins e.g. `SpeedrunScriptingTools.dll` in `C:\Users\<name>\Documents\GWToolboxpp\<name>\plugins`

### Automatic Updates
If you enable automatic updates for toolbox, then you should recieve automatic, TAS-enabled updates. You will still need to manually update the plugins when needed.

## Features
- Minipets can be targeted
- Toolbox can be used in guild halls
- Blocklists for `/useskill` are removed
- Useful TAS plugins are provided:
  * `SST`: allows writing in-game scripts
  * `RawDialogs`: adds a command `/rawdialog <dialog_id>` that will send the raw dialog packet, allowing to send dialogs when the NPC is in combat.


## Advanced
The code to modify `gwca.dll` and allow minipet targeting can be found [here](https://github.com/gwtasdevs/GWCA)

