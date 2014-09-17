# Subtitle Edit Plugins

You can write your own plugins for Subtitle Edit in any .NET language.


## What can be done with plugins

At the moment plugins can be made in these menus: File, Tools, Sync, Translate, Spell check.

A new subtitle format can also be added via a plugin.

If you want to extend Subtitle Edit somewhere else, please open an issue.


## Compiling

Please compile the plugins for the "Any CPU" platform.

Framework version: If possible, please provide both a version compiled with .NET 2 (can be used with 2-3.5) and a version compiled with .NET 4 (can be used with 4+).


## Requirements

Use `Nikse.SubtitleEdit.PluginLogic` as Entry point namespace, take a look [here](https://github.com/SubtitleEdit/plugins/blob/master/LinesUnbreaker/Plugin.cs).

The DLL filename must be `<classname>.dll` - e.g. `SyncViaOtherSubtitle.dll`.
