# Obsidian Reference Map Test

This is an Obsidian notes vault for testing features of the [Obsidian Reference Map](https://github.com/anoopkcn/obsidian-reference-map) plugin. When first cloning this repo or when pulling changes, update your local plugin submodule to get the appropriate commit being tracked by your working tree:

```Shell
git submodule update --init --recursive
```

Change directories to the submodule and install it:

```Shell
cd vault/.obsidian/plugins/obsidian-reference-map
npm install
```

The default build task in VSCode has been configured as `npm run dev` for the plugin folder, which is in a submodule in the appropriate folder to be loaded as an Obsidian plugin. It will run upon startup of VSCode when in this folder, if you allow startup tasks in your user configuration.

Open the `vault` folder in Obsidian. You may have to mark the vault as trusted before the plugin will load. Tests are organized by feature. The only feature currently (partially) tested right now is the "Get references using citekey" feature. Eventually these tests may be migrated into a test suite for the plugin.
