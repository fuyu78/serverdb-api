> Parameters wrapped with square brackets ([]) are optional.
> 
# Initialization & Uninstalling:
- db!setup: This command does not requires any parameter and will only run if your server requires a setup. If you have inserted at least one key earlier, you no longer need to setup.
- db!uninstall: This command does not require any parameter. You will be prompted to type a text to confirm the uninstallation. This action is irreversible.


# Database Commands:
- db!insert <name> <value>: Inserts a key-value pair to your server's database. Both parameters are required and this command will take effect immediately. If specified key exists, it will be updated with new value.
- db!delete <key>: Delete an existing key in your server's database. This command will take effect immediately.
- db!keys: Lists all the keys in your server's database.

# Other Commands:
- db!help: Shows an interactive help embed in the channel the command is executed. Requires administrator permission to view help.
- db!support: Get an invite for our support server. Bot will DM you the invite, make sure to allow DMs coming from our bot. This command has an alias of db!ss
- db!website: DMs our website url to the command executer. This command has an alias of db!ws

## Further help:
- If you struggle using our bot or the API itself, please create an issue on this repository. You can also join our [support server](https://discord.gg/9aRBdpJ) to get faster responses.
