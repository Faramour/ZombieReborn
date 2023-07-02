# ZombieReborn

**NOTE: Lua VScript was disabled in the Mirage update, and as of the Nuke update we now have strong reason to believe a completely new scripting system is on the way. Therefore this project should generally be considered paused until the CS2 scripting situation has stabilized.**

An experimental implementation of Zombie Escape in Counter-Strike 2 using the Lua [VScript API](https://cs2.poggu.me/dumped-data/vscript-list).

[Join our Discord](https://discord.gg/QsSGf9ZEVs) for development discussion and to keep up to date!

## Installation

Copy both the `scripts` and `cfg` directories to your `game/csgo` folder. If you've already made changes to your server cfg's, you may want to just copy the contents of ours in instead.

Knockback will not function out of the box, as Movement Unlocker is required similar to CS:GO. See instructions on manually patching Movement Unlocker [here](../../wiki/Patching-Movement-Unlocker) until there is some plugin API available to do it in.

## Documentation

You can find the documentation of various Zombie:Reborn features [here](../../wiki/Documentation).

## Current issues

You can find the current issues with CS2 we'd like to report to Valve [here](../../wiki/CS2-Issues).

## The Future?

It is currently unknown how the plugin ecosystem is going to work on CS2, see the [AlliedModders wiki entry](https://wiki.alliedmods.net/Introduction_to_SourceMod_Plugins#Will_SourceMod_support_Source_2.3F_Will_plugins_for_existing_games_continue_to_work_if_they_are_ported.3F) on this for more information. We currently foresee a few possible outcomes of how this repository may be useful:

- Allowing for testing of the Zombie Escape gamemode during these next few months of the CS2 beta, allowing us to test maps & identify potential engine issues
- In the event a SourceMod equivalent is not yet ready on CS2 launch, this can be used to have ZE servers running day one
- In the event of a SourceMod equivalent choosing to expand on VScript, we will have a solid codebase already existing in Lua that we can switch to using custom functions where applicable
