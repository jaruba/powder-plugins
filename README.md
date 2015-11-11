# Powder Player Plugins

The official list of all [Powder Player](https://github.com/jaruba/PowderPlayer) plugins.

If you have made a new plugin, please submit a pull request adding the relevant information to `plugins.json`.

Upon acceptence of the PR, your plugin will instantly become available to all Powder Player users around the world.

Example of a correct `plugins.json` [can be seen here](https://github.com/jaruba/powder-plugins/blob/gh-pages/demo-plugins.json).

Description of all required fields:

```
{
    "repo": "my-cool-plugin", // repo name as it is shown on github
    "author": "jaruba", // author name as it is shown on github

    // it should be noted, that for this example, the link:
    // https://github.com/jaruba/my-cool-plugin
    // must exist as it is where it will search for the plugin releases

    "title": "My Cool Plugin", // plugin title
    "version": "0.0.1", // latest plugin version
    "appVersion": 0.95, // minimum Powder Player version it works on
    "description": "Does some really cool things!" // plugin description
},
```
