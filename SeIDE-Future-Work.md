Here are the things that should start to show up in SeIDE over the next couple months. In no particular order...

## Locators
  * Add Locators via plugins - this is non trivial in difficulty since the current locator strategy didn't have this in mind. Or dynamically adding things at all for that matter
  * User defined locators likely will also fall out of this
  * A Locator panel in Options to see what they are

The big tricky bit for this is how to include user-defined and plugin-provided locators into the server

## Formatters
  * Actually, I think I'm decently happy with things right now

## Plugin Management
  * Continue to built out the Plugins tab of the Options screen to provide useful plugin management information

## User Extensions
  * This is in pretty good shape

## Preferences
  * Rewrite the way preferences are handled to be through a Prefwindow rather than a Dialog
  * Add support for Integer preferences

## Dumber is Better (or Pluginification)
  * Some functionality is not core to SeIDE itself and would be much better maintained as a separate plugin
  * I'm sure there will be an ongoing need to be adding IDs to things and abstracting certain parts to make adding onto SeIDE easier