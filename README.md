# PlugMan

PlugMan is a simple, easy to use plugin that lets server admins manage plugins from either in-game or console without the need to restart the server.

## Features
* Enable, disable, restart, load, reload, and unload plugins from in-game or console.
* List plugins alphabetically, with version if specified.
* Get useful information on plugins such as commands, version, author(s), etc.
* Easily manage plugins without having to constantly restart your server.
* List commands a plugin has registered.
* Tab completion for command names and plugin names.
* Permissions Support - All commands default to OP.

## Commands
| Command | Description |
| --------------- | ---------------- |
| /plugman help | Show help information. |
| /plugman list [-v] | List plugins in alphabetical order. Use "-v" to include versions. |
| /plugman info [plugin] | Displays information about a plugin. |
| /plugman usage [plugin] | List commands that a plugin has registered. |
| /plugman enable [plugin|all] | Enable a plugin. |
| /plugman disable [plugin|all] | Disable a plugin. |
| /plugman restart [plugin|all] | Restart (disable/enable) a plugin. |
| /plugman load [plugin] | Load a plugin. |
| /plugman reload [plugin|all] | Reload (unload/load) a plugin. |
| /plugman unload [plugin] | Unload a plugin. |

## Permissions
| Permission Node | Default | Description |
| ------------------------- | ---------- | ---------------- |
| plugman.admin | OP | Allows use of all PlugMan commands. |
| plugman.update | OP | Allows user to see update messages. |
| plugman.help | OP | Allow use of the help command. |
| plugman.list | OP | Allow use of the list command. |
| plugman.info | OP | Allow use of the info command. |
| plugman.usage | OP | Allow use of the usage command. |
| plugman.enable | OP | Allow use of the enable command. |
| plugman.enable.all | OP | Allow use of the enable all command. |
| plugman.disable | OP | Allow use of the disable command. |
| plugman.disable.all | OP | Allow use of the disable all command. |
| plugman.restart | OP | Allow use of the restart command. |
| plugman.restart.all | OP | Allow use of the restart all command. |
| plugman.load | OP | Allow use of the load command. |
| plugman.reload | OP | Allow use of the reload command. |
| plugman.reload.all | OP | Allow use of the reload all command. |
| plugman.unload | OP | Allow use of the unload command. |

## Configuration
| File | URL |
| ----- | ------- |
| config.yml | https://github.com/rylinaux/PlugMan/blob/master/src/main/resources/config.yml |
| messages.yml | https://github.com/rylinaux/PlugMan/blob/master/src/main/resources/messages.yml |