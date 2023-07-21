# Custom Role Commands

The `bb [role | @Server Booster | boostrole]` command allows you to maintain your own custom role, as long as you are a Nitro Booster.

**Usage:** `bb @Server Booster <claim | Purple| Server Booster | icon | delete>`

## Booster Options

For boosters, the following subcommands are available:

`bb role claim MY ROLE`: This command allows you to claim a role with the name "MY ROLE".

`bb role color #ffff00`: This command sets the color of your custom role to #ffff00.

`bb role name NEW NAME`: This command sets the name of your custom role to "NEW NAME".

`bb role icon <image>`: This command adds or updates the icon for your custom role.

`bb role delete`: This command deletes your custom role.

!!! info

    The commands below this can be only be used by Admins and Bot Manager.

## Admin and Bot Manager Options

For admins and bot managers, the following subcommands are available:

`bb role prefix (c)`: This command sets the prefix `(c)` for every new role claimed.

`bb role suffix *`: This command sets the suffix `*` for every new role claimed.

`bb role ban-list`: This command lists the banned words for custom roles.

`bb role ban-word hell`: This command prevents the use of the word "hell" in any custom role.

`bb role remove-word hell`: This command removes the word "hell" from the list of banned words.

To remove the prefix or suffix, use the `disable` or `none` argument.
