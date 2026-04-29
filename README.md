# Guild Wars TAS Tools

TAS Toolbox releases can be found [here](https://github.com/gwtasdevs/GWToolboxpp/releases).

A new release will be created automatically whenever Toolbox is updated. Releases marked as <span style="color: #9e6a03; border: 1px solid #9e6a03; border-radius: 624.938rem; padding: 0 0.5rem; line-height: 22px; font-size: 0.75rem;">Pre-release</span> correspond to updates to the Toolbox dev branch.

## Installation
- Install [Toolbox](https://www.gwtoolbox.com) normally
- Download the files from the [latest TAS version](https://github.com/gwtasdevs/GWToolboxpp/releases/latest)
- Replace `GWToolboxdll.dll` in `C:\Users\<name>\Documents\GWToolboxpp`
- Replace `gwca.dll` in `C:\Users\<name>\Documents\GWToolboxpp\<name>`
- Place any plugins e.g. `SpeedrunScriptingTools.dll` in `C:\Users\<name>\Documents\GWToolboxpp\<name>\plugins`

### Automatic Updates
If you enable automatic updates for Toolbox, then you should recieve automatic, TAS-enabled updates. You will still need to manually update the plugins when needed.

## Features
- Minipets can be targeted
- Invisible NPCs can be targeted
- Duping window updated to track aggro groups separately (useful for double duping)
- Toolbox can be used in guild halls
- Blocklists for `/useskill` are removed
- Multiple `/useskill` is supported (type `/useskill n` multiple times, `/useskill 0|stop|off` to stop all)
- Allow using chat commands when guild wars is not the focussed window
- Useful TAS plugins are provided:
  * `AgentPopTimer`: displays the cooldown to spawn another agent (i.e. spawn your minipet or pop a ghost-in-the-box)
  * `DeathPenaltyTimer`: displays a timer showing the window of time after being revived where dying will not cause your death penalty to increase
  * `DhuumCalculator`: adds a window showing projections of how long Dhuum will take to die vs complete Dhuum's rest
  * `DialogsWindow`: adds a window with buttons for sending commonly used dialogs, e.g. underworld quests & teles
  * `Follow`: adds a chat command `/follow` which makes you follow whoever is targeted
  * `GWSplits`: uses the `SpeedrunScriptingTools` system to define splits for tracking time during runs
  * `PitsSoulsWindow`: shows respawn timers for souls relevant for the pits qust in UW
  * `ProjectileIndicator`: displays the areas on the floor where enemy projectiles will hit you
  * `RawDialogs`: adds a command `/rawdialog <dialog_id>` that will send the raw dialog packet, allowing to send dialogs when the NPC is in combat.
  * `ShadowstepPredictor`: adds an overlay on the skillbar showing whether a given sahdowstep will succeed
  * `Slowload`: allows setting a hotkey to delay loading an instance until it is pressed
  * `SpeedrunScriptingTools`: allows writing in-game scripts

## Additonal Plugins
More useful plugins for speedruns can be found [here](https://github.com/gam415/GWToolboxPlugins).

## Advanced
The code to modify `gwca.dll` and allow minipet targeting can be found [here](https://github.com/gwtasdevs/gwca-patcher).
