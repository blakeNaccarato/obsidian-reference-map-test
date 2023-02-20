# Obsidian Reference Map Test

This is an Obsidian notes vault for testing features of the [Obsidian Reference Map](https://github.com/anoopkcn/obsidian-reference-map) plugin. Clone this repo and open the `vault` folder as a vault in Obsidian. On first clone, or when pulling changes, run the following command to update the plugin submodule to the submodule commit being tracked:

```Shell
git submodule update --init --recursive
```

Run the default build task in VSCode, configured as `npm run dev` for the plugin folder, which is in a submodule in the appropriate folder to be loaded as an Obsidian plugin. It will run upon startup of VSCode when in this folder, if you allow startup tasks in your user configuration.

Open the `vault` folder in Obsidian. You may have to mark the vault as trusted before the plugin will load. Tests are organized by feature. The only feature currently (partially) tested right now is the "Get references using citekey" feature. Eventually these tests may be migrated into a test suite for the plugin.
